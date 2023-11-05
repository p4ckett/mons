# 💊 mons coding language [W.I.P]
## Fast - Smooth - Clean / PRIVATE

<br>
<br>
<br>

<img src="https://github.com/HotCakeX/Harden-Windows-Security/raw/main/images/Gifs/1pxRainbowLine.gif" width= "300000" alt="horizontal super thin rainbow RGB line">

<br>
<br>

### IMPORTANT INT
```coffeescript
int $ 000000000 & int $ 105940105
int $ 000000000 & int $ 031953033
```

<br>

- https://440.gitbook.io/untitled/update-2

<br>
<br>

### add commands to your BOT
- you will first need to make ruleset and enable it
```coffeescript
mons.commands {chat}, - ruleset.V
mons.commands {chat-any}, - ruleset.V
```
after that we will make commands
```coffeescript
command.local (ban) # we created ban command
command.local (mute) # we created mute command
command.local (timeout) # we created timeout command
command.local (note) # we created note command

# how a note command works
you: p.note @user bla bla bla
bot: NO MSG

# because we did not set any output messages
# (p Is your prefix for now you can change your prefix any time)

# let's add message
command.local (note) b.msg(Note added to user Successfully)
i, any[error] e.msg(reason)

# now let's try

you: p.note @user bla bla bla
bot: Note added to user Successfully
```

<br>
<br>

### LOG message examples
```
e.msg(action) - will send the taken action to your LOGS
e.msg(error) - will send ERRORS to your LOGS
e.msg error(any) - will send any ERROR to your LOGS
e.msg(apikeyEXP) - this will tell if your mons API key expired (IMPORTANT)
```

<br>

### You need API key to use mons.
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | (yourapikey) | **Required**. Your API key |

<br>
<br>

### example
```coffeescript
main.pr (7), <IDP> > main.pr (1), <QPS> > main.pr (9), <VEQ>
main.pr (2), <QBG> > main.pr (8), <LPT> > main.pr (6), <BGH>
main.pr (4), <ITR> > main.pr (3), <VNC> > main.pr (0), <BXZ>

api_key (yourapikey)
```
<br>
<br>

- to run your code
`mons yourcode.mons`

<br>
<br>

### If you wanna make KEY system on your discord server or guilded
```coffeescript
s.f key_sys {require_key},
i, key(sent), = check
 keyDB(yourkeyDATABASE),
i, key = correct (action),

 s.f (usedkey), i, keyused
 e.msg (msg),
  i, msg.f e.msg (5849),

# in (action) you can put (accessCHANNELS)
# few examples 
# (giveROLE)
# (giveLINK)

# big example
s.f key_sys {require_key},
i, key(sent), = check
 keyDB(mykeyDB),
i, key = correct (giveROLE), e.msg(action)

# the e.msg(action) will send the taken action LOG.
```

<br>
<br>

## chat.reply example
```coffeescript
chat.reply (/),
chat.reply (state), $ main (23405780237901872039138045912034810973109571),
chat.reply (state), $ main (23578971039180951730591809380917350983247839),
chat.reply (state), $ main (85492809384098102973989080392580982295839812),

# False/Error - cRP means chatREPLY
chat.reply $stateFalse = e.msg (cRP 23509),
chat.reply $stateError = e.msg (cRP 90250),

# for example
chat.reply (state), $ main(85492809384098102973989080392580982295839812),

this state will reply to messages sent by MEMBERS

# example
anyone: Hello
bot: Hello

# in mons chat reply states we have AI replies, which is easy to use
# 85492809384098102973989080392580982295839812 | is reply AI
# 23578971039180951730591809380917350983247839 | is chat AI
# 23405780237901872039138045912034810973109571 | is helper AI

# If everything in states configured perfectly, it will work.
```

<br>
<br>
<br>

Example | mons.scan & sending ERRORS to LOGS
```coffeescript
mons.scan {apiscan}, {websitescan},
i, mons.scan (error), e.msg (sE 45941), & e, mons.scan (noscan), e.msg (sN 50133),
```

## Way Gates
- Way Gates is PROXIES for mons coding language
- create waygate.cf paste proxies and set load
- example
  ```load.waygate (waygate.cf), [S],```
  - [S], means SILENT
  - "$" means PRIORITY on mons coding language
  
### Bigger Example
```coffeescript
 way.gate [S],
 way.gate [S],

 $ load.waygate (waygate.cf), [S],

 way.gate (gates), l.ber {[state]},
 way.gate (gates), l.seed {[loop]},
 way.gate (gates), l.warp {[instant]},

$ way.gate load /waygate.cf [S],
$ way.gate check /waygate.cf [S],
```
<br>
<br>

We can simply make outputs go as response on apps
Only apps - Guilded/Telegram/Discord
You need to understand API's

- create ACCOUNT for the BOT you're making

```coffeescript
v.b {windows}, (currentVer),
local.int 4-brb.xcp / main.int 5-prlx.lcbm
api.mbp {guilded}, (mons.chatV1), - ruleset.V
api.mbp {guilded}, (mons.chatV6), - ruleset.V
```

You need to keep the API up to date and the versions.
For example
- Guilded updated API to 1.11.0
- Update the api.mbp

<br>
### NOTE: To work on telegram you need Telegram Bot API
<br>

<br>
<br>

## To get your BOT in VC | telegram/guilded/discord
- you can use all at the same time.
- just remove the "#"
```coffeescript
 local.vc -3 /state 34{para}, /pass
 local.vc -3 /state 45{para}, /exec
 local.vc 3 /state 45{load}, /t
 local.vc 3 /state 34 {load}, /t
 local.vc state -3 (f),
 local.vc state 3 (t),

 <-3>, <3>

# for discord
token_load = token.mbp

# for guilded
user_load = user.mbp

# for telegram
user_tele = uste.mbp

 m $59445 - f [L],
 m $45904 - f [L],
 m $40392 - f [L],

api_key (yourapikey)
```
<br>
<br>

## Rulesets example
```coffeescript
[ruleset.V], which means ruleset.VALID
[ruleset.B], which means ruleset.BLOCK
```
<br>
<br>

## State Loading and Looping Example
```coffeescript
state ID {load},
state ID {loop},
```
<br>
<br>

## To detect any errors and send the reason to admin panel
```coffeescript
i, error(any), e.msg(reason),
```
<br>
<br>

## internal.r (IMPORTANT)
```coffeescript
(internal.r), ! fire.fbs $
(boot.r), [b.s.s4],

server.line [potocle], ]][in], 50923810 + 00000 - ruleset.V
proto.b{[timeline]},
```
<br>
<br>

## Locals
```coffeescript
iplocal.mbp (static),
datalocal.mbp (static),
dataprivate.mbp (static),

local.bmo (break), fa
local.bmo (load), fa

api_key (yourapikey)
```

## Ping / Network
```coffeescript
system.ping [S],
system.network [S],
```
<br>
<br>

## Data Holders (EXAMPLE)
```coffeescript
data.holder {dbfr},
data.holder {bflk},
data.holder {prsn},
data.holder {bfma},
```
<br>
<br>

## Load, exec, userlevel
```coffeescript
<p3bload>, <exec>, <userexeclevel>
```
<br>
<br>

## Commands.build (IMPORTANT)
```coffeescript
 commands.build <2385710237120498358123934571238359812398>
 commands.build <3157102987340198540917230098091809581237>
 commands.build <1239418739548619283712345986781239871234>
```
<br>
<br>

## Important Loops
```coffeescript

# main.pr execl Loops
loop main.pr ^execl _$BMFNASMFK > 58912834
loop main.pr ^execl _$JFZXCBNMA > 23509812
loop main.pr ^execl _$VNOEWPLAS > 85293124

# main.pr Loops
main.pr (7), <IDP> > main.pr (1), <QPS> > main.pr (9), <VEQ>
main.pr (2), <QBG> > main.pr (8), <LPT> > main.pr (6), <BGH>
main.pr (4), <ITR> > main.pr (3), <VNC> > main.pr (0), <BXZ>

# forece.local Loops
b$skcm.loop_ in server $ force.local; fire ^ intbBBS
boj.v - rbrmmxl.lsl $ connection; 3
boj.v - rbrmmxl.lsl $ connection; 0

api_key (yourapikey)
```
<br>
<br>

## Important state ID's
```coffeescript
 state $349178524356917823123 {mtr},
 state.id{if.local}, = mtr_load (base), - ruleset.V
 state $324967912873987395691 {mtr},
 state.id{if.local}, = mtr_load (base), - ruleset.V
 state $289395801802398025709 {flp},
 state.id{if.local}, = flp_load (base), - ruleset.V
```
<br>
<br>

## Important datalocal.mbp
```coffeescript
  # data local
  3259078124,
  2394791782,
  2348799878,
  3490659032,
  2935012305,
  3592930412,
  3590230412,
  3591239503,
  4306592032,
  5090912312,
  4960239012,
  0259023211,
  5940130555,
  1204935012,
  5991283549,
```
<br>
<br>

## sld ID'S
```coffeescript
sld [349209, 34592, 32000, 92500],
sld [938412, 18359, 75481, 34858],
sld [125849, 59422, 57829, 10394],
```
<br>
<br>

## LOGS/LIMITERS/RULES/VERSIONS
```coffeescript
 l.mons = {READ.limiter.p}, {READ.rules.ini} - ruleset.V
 l.mons = {LOCAL.tornetwork}, {PRIVATE.tornetwork} - ruleset.V
 l.mons = {BREAK.behvnm300}, {BREAK.idlfle} - ruleset.V

 m.mons = {VERSION.private}, {VERSION.updater} ruleset.V
 m.mons = {VERSION.betaCLOSED}, {VERSION.alphaCLOSED} - ruleset.B
 m.mons = {VERSION.NEWmons} {VERSION.NEWshort} - ruleset.V

 p.mons = {LOG.chat}, {LOG.text} - ruleset.B
 p.mons = {LOG.users}, {LOG.version} - ruleset.B
 p.mons = {LOG.logsend}, {LOG.vv} - ruleset.V

api_key (yourapikey)
```

<br>
<br>

## NEEDS TO BE LOADED
```coffeescript
<rule.ids>, <rule.rules>, <rule.sync>
state [03I30] = warn.msg (locked),
state.false = warn.msg (sys m00 req3_$xbp local13),

rID [SYNC] (3340)
ruleID (7,200) rules.ini

304.inter{[½$]} & 305.inter{[£½]}

load.first <peb.eldo>, <peb.monsv>, <peb.mons> [S],
load.second <mons.lib>, <mbp.mons>, <vc.mons>, <fa.mons>, <bno.mons> [S],
load.third <recommendation.service>, <location.service>, <local>, [S],

sscl.all [30405, 30493, 95340, 34932, 35404],
sscl.all [85491, 13493, 34915, 58129, 47123],

sscl.all [remove.invalid],

     feb 4.3.2.15.6.3.5.8.6.2.1.6.8.9.5.1.4.7
     feb 4.7.4.94.3.5.7.8.1.3.7.7.6.4.4.1.2.4
     feb 4.1.3.23.5.7.8.3.1.2.6.8.5.3.3.7.9.1
     feb 4.6.7.54.3.1.5.6.7.1.5.3.5.5.3.1.2.5
     feb 4.1.6.83.4.1.5.7.8.8.6.1.3.6.8.9.4.1

paste.local {inb0},
 server.none - ruleset.B
 paste.local {inb1},
paste.local {inb0},
 server.none - ruleset.B
 paste.local {inb1},
paste.local {inb0},
 server.none - ruleset.B
 paste.local {inb1},
paste.local {inb0},
 server.none - ruleset.B
 paste.local {inb1},
paste.local {inb0},
 server.none - ruleset.B
 paste.local {inb1},

     feb.lock = all [S],

     seb.lock 94002100340589340359234 & seb.lock 98235989384190394859999

<limit.ids> sl$ective -_$userarea #$ 54000 
v.b (int), b dual $ IDS {3450},
 sl$ective -_$userarea #$ 54000 
 v.b (int), b dual $ IDS {3450},
lID [SYNC] (9540) sl$ective -_$userarea #$ 54000 
v.b (int), b dual $ IDS {3450},
limiterID [SYNC] (1,500) limiter.p sl$ective -_$userarea #$ 54000 
v.b (int), b dual $ IDS {3450},
 sl$ective -_$userarea #$ 54000 
 v.b (int), b dual $ IDS {3450},
{sync.rules}, {sync.limiter}, sl$ective -_$userarea #$ 54000 
v.b (int), b dual $ IDS {3450},
 sl$ective -_$userarea #$ 54000 
 v.b (int), b dual $ IDS {3450},
l [LocationHere], sl$ective -_$userarea #$ 54000 
v.b (int), b dual $ IDS {3450},
local pub = {} pub.mons = (239435),
<rq.admin>, <rq.hwid>, <rq.location> [S],

re.locate = (sys30)
$b {bin.localID940342}, {bin.localID390400}

api_key (yourapikey)
```
<br>
<br>

## Long example
```coffeescript
bct.wfm [SN], bct.ry f = r.apanel - ruleset.V
bct.sfm [RD], bct.ry f = r.apanel - ruleset.V
bct.wfs [RD], bct.ry f = r.apanel - ruleset.V
bct.rly [RY], bct.ry f = r.apanel - ruleset.V
bct.lup [LP], bct.ry f = r.apanel - ruleset.V
```
<br>
<br>

`r panel (role_panel) roles [admin/owner/mod],`

## List: ram/memory/cpu/ssd/network
```coffeescript
p.ram {[main]},
p.mem {[main]},
p.cpu {[main]},
p.ram {[main]},
p.ssd {[main]},
p.nwk {[main]},
```
<br>
<br>

## States
- load/loop
```coffeescript
state 34901104939057019278380180948052307820934851340891350978180923413057941039478 {load},
state 39028540491702348259691836794871982377037509172834791657987123097107093785989 {loop},
```
<br>
<br>

## loop.state and rulesets
```coffeescript
loop.state (mainstates), $ state.states - ruleset.V
loop.state (mainstates), $ all.states - ruleset.V
```
<br>
<br>

- `ruleset.V` means ruleset.VALID
- `ruleset.B` means ruleset.BLOCK

## library (You will need to load this)
- create lib.mbp and paste.
```coffeescript
- lib - /libraryV1/old/
- lib - /libraryV2/old/
- lib - /libraryV3/old/
- lib - /libraryV4/old/
- lib - /libraryV5/old/
- lib - /libraryV6/old/
- lib - /libraryV7/current/
- load.latest (library), ruleset.V

api_key (yourapikey)
```
No version limit.

<br>
<br>

## chat reply states
```coffeescript
- chat.reply (/)
- chat.reply (state), $ main (2340578023799909571)
- chat.reply (state), $ main (2357897150983247839)
- chat.reply (state), $ main (8549280392580939812)
- chat.reply $stateFalse = e.msg (cRP 23509)
- chat.reply $stateError = e.msg (cRP 90250)
- chat.reply $stateBlackList = e.msg (cRP 935000)

api_key (yourapikey)
```
<br>
<br>

## call.id / call states
```coffeescript
- states - ruleset.V
- call.id $ 59 [S]
- call.id $ 50 [S]
- call.id $ 30 [S]
- call.id $ 12 [S]
- call.id $ 91 [S]
```
<br>
<br>

## Spotify search
```coffeescript
- spotify.search [S]
- spotify.search (waitforInput) - ruleset.V
  - spotify.search (InputReceived) = e.src (Input)
    - spotify.search (output) = e.msg (link)
    - spotify.search (SongNotFound) = e.msg (msg)

api_key (yourapikey)
```
Will search and send the song link as output in chat.

## local int and _ux2 / base and data, priority - t or - f

- `t` means true
- `f` means false

<br>
<br>

## pass generator
gen.pgen folder(passgen), r(pgen.mbp)
```coffeescript
- `<Uppercase>`
- `<lowercase>`
- `<Numbers >`
- `<Symbols>`
- `<ExcludeSimilarCharacters>`
- `<ExcludeAmbiguousSymbols>`

api_key (yourapikey)
```
<br>
<br>

## location service
Can use Google maps and SnapMap
```coffeescript
location_service = {
    'serviceID': 9349,
    'run': True,
    'main.base': 'cl.sn(location.service)',
    'provide': ['SnapMap', 'GoogleMap'],
    'example': 'https://maps.app.goo.gl/',
    'search': 'https://www.google.com/maps/place',
    'map.embed': 'locationservice.mbp',
    'map.link': 'https://maps.app.goo.gl/',
    'service.reactive': True,
    'example.open.app': {
        'snapchat': '[android]', - no IOS support
        'snapmap': '[snapmap]'
    },
    'provide.output': ['Text', 'Voice'],
    'request.nearby': ['nearby.places', 'nearby.restaurants', 'nearby.parks', 'nearby.hotels', 'nearby.bars', 'nearby.pubs', 'nearby.museum', 'nearby.hospital', 'nearby.stores', 'nearby.any'],
    'folder(location)': 'location',
    'readfolder(locationservice.mbp)': '',
    'pub.lc': '[done]'

api_key (yourapikey)
```
<br>
<br>

## Easy baritone for Minecraft
- create baritone.mbp

```coffeescript
read.folder(baritone), read.mbp(baritone.mbp),
baritone.mons {github}, - ruleset.V
baritone.mons folder(baritone), (baritone.mbp), - ruleset.V
baritone.mons (update.loop),
baritone.mons {allowInventory.cb}, - ruleset.V

api_key (yourapikey)
```
- baritone repo - https://github.com/cabaletta/baritone


[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
