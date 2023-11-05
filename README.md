## Example

bct.wfm [SN], bct.ry f = r.apanel - ruleset.V
bct.sfm [RD], bct.ry f = r.apanel - ruleset.V
bct.wfs [RD], bct.ry f = r.apanel - ruleset.V
bct.rly [RY], bct.ry f = r.apanel - ruleset.V
bct.lup [LP], bct.ry f = r.apanel - ruleset.V

# r panel (role_panel) roles [admin/owner/mod],

list ram/mem/cpu/ssd/nwk 

ram, memory, cpu, ssd, network -

# states - load/loop

state 34901105097857941039478 {load},
state 39028540496798093785989 {loop},

# loop.state and rulesets

loop.state (mainstates), 
$ state.states - ruleset.V
loop.state (mainstates), 
$ all.states - ruleset.V

- ruleset.V means ruleset.VALID
- ruleset.B means ruleset.BLOCK

# library

 lib - /libraryV1/old/
 lib - /libraryV2/old/
 lib - /libraryV3/old/
 lib - /libraryV4/old/
 lib - /libraryV5/old/
 lib - /libraryV6/old/
 lib - /libraryV7/current/
load.latest (library), ruleset.V

- No version limit.

# chat reply states

chat.reply (/),
chat.reply (state), $ main (2340578023799909571),
chat.reply (state), $ main (2357897150983247839),
chat.reply (state), $ main (8549280392580939812),

chat.reply $stateFalse = e.msg (cRP 23509),
chat.reply $stateError = e.msg (cRP 90250),
chat.reply $stateBlackList = e.msg (cRP 935000),

# call.id / call states

 states - ruleset.V
 # sSs
 call.id $ 59 [S],
 call.id $ 50 [S],
 call.id $ 30 [S],
 call.id $ 12 [S],
 call.id $ 91 [S],

 # spotify search

  spotify.search [S],
  spotify.search (waitforInput), - ruleset.V
   spotify.search (InputReceived) = e.src (Input), 
    spotify.search (output), = e.msg (link),
     spotify.search (SongNotFound), = e.msg (msg),

- will search and send the song link as output in chat.

# local int and _ux2 / base and data, priority - t or - f
- t means true - f means false

# pass generator

gen.pgen folder(passgen), r(pgen.mbp),
<Uppercase>, <lowercase>, <Numbers >, <Symbols>, <ExcludeSimilarCharacters>, <ExcludeAmbiguousSymbols>

# location service
- can use Google maps and SnapMap

  gs.sn {serviceID.9349}, (location.service) = run.t
location.service (run.as), service
cl.sn {location.service}, (main.base),
cl.sn {location.service}, provide from (SnapMap, GoogleMap),
cl.sn {location.service}, example "https://maps.app.goo.gl/"
cl.sn {location.service}, search (https://www.google.com/maps/place),
cl.sn {location.service}, search.example = (https://www.google.com/maps/place/Houston,+TX,+USA),
cl.sn {location.service}, map.embed (locationservice.mbp),
cl.sn {location.service}, map.link = (https://maps.app.goo.gl/)
cl.sn {location.service}, service.reactive [true], [S],
cl.sn {location.service}, example open.app (snapchat), {[android]}, [S],
cl.sn {location.service}, example open.app (snapchat), {[snapmap]}, [S],
cl.sn {location.service}, provide output (Text, Voice), [ANY], [S],
cl.sn {location.service}, request (nearby), [nearby.places],
cl.sn {location.service}, request (nearby), [nearby.restaurants],
cl.sn {location.service}, request (nearby), [nearby.parks],
cl.sn {location.service}, request (nearby), [nearby.hotels],
cl.sn {location.service}, request (nearby), [nearby.bars],
cl.sn {location.service}, request (nearby), [nearby.pubs],
cl.sn {location.service}, request (nearby), [nearby.museum],
cl.sn {location.service}, request (nearby), [nearby.hospital],
cl.sn {location.service}, request (nearby), [nearby.stores],
cl.sn {location.service}, request (nearby), [nearby.any],

location.service folder(location),
location.service readfolder(locationservice.mbp),
pub.lc {[done]},

#  recommendation service

gs.sn {serviceID.9350}, (recommendation.service) = run.t
recommendation.service folder(rc),
recommendation.service readfolder(rc.mbp),

if.any {req}, - over.bbs {gs.sn}, [trace.1],
if.any {req}, - over.bbs {gs.sn}, [provide], (output),
gs.sn {provide.requested}, (bbs.local),
gs.sn {[received]} text(any), voice(any),
gs.sn {recommendation.service}, service.reactive [true], [S],

gs.sn {recommendation.service}, request (song),
gs.sn {recommendation.service}, request (game),
gs.sn {recommendation.service}, request (movie),
gs.sn {recommendation.service}, request (video),
gs.sn {recommendation.service}, request (topic),

recommendation.service (run.as), service
recommendation.service (provide.full),
i, link{[invalid]}, e.msg(igsn 1), sp.b (recommendation.done), = send
i, recommendation.notfound p.msg(reason),
i, error(any), e.msg(reason),

# compact.message ruleset

compact.message (any), - ruleset.V
compact.message (main), - ruleset.V
compact.message (recommendation), - ruleset.V

# base invalid local_load if error send message to admin panel

base.bl {invalid} i, local_load = e.msg(l34),
