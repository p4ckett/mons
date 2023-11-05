## example
```
bct.wfm [SN], bct.ry f = r.apanel - ruleset.V
bct.sfm [RD], bct.ry f = r.apanel - ruleset.V
bct.wfs [RD], bct.ry f = r.apanel - ruleset.V
bct.rly [RY], bct.ry f = r.apanel - ruleset.V
bct.lup [LP], bct.ry f = r.apanel - ruleset.V
```

## r panel (role_panel) roles [admin/owner/mod]


# List: ram/mem/cpu/ssd/nwk

```
p.ram {[main]},
p.mem {[main]},
p.cpu {[main]},
p.ram {[main]},
p.ssd {[main]},
p.nwk {[main]},
```

## States
# load/loop

```
state 34901104939057019278380180948052307820934851340891350978180923413057941039478 {load},
state 39028540491702348259691836794871982377037509172834791657987123097107093785989 {loop},
```

## loop.state and rulesets

```
loop.state (mainstates), $ state.states - ruleset.V
loop.state (mainstates), $ all.states - ruleset.V
```

- `ruleset.V` means ruleset.VALID
- `ruleset.B` means ruleset.BLOCK

## library

- lib - /libraryV1/old/
- lib - /libraryV2/old/
- lib - /libraryV3/old/
- lib - /libraryV4/old/
- lib - /libraryV5/old/
- lib - /libraryV6/old/
- lib - /libraryV7/current/
- load.latest (library), ruleset.V

No version limit.

## chat reply states

- chat.reply (/)
- chat.reply (state), $ main (2340578023799909571)
- chat.reply (state), $ main (2357897150983247839)
- chat.reply (state), $ main (8549280392580939812)
- chat.reply $stateFalse = e.msg (cRP 23509)
- chat.reply $stateError = e.msg (cRP 90250)
- chat.reply $stateBlackList = e.msg (cRP 935000)

## call.id / call states

- states - ruleset.V
- `sSs`
- call.id $ 59 [S]
- call.id $ 50 [S]
- call.id $ 30 [S]
- call.id $ 12 [S]
- call.id $ 91 [S]

## Spotify search

- spotify.search [S]
- spotify.search (waitforInput) - ruleset.V
  - spotify.search (InputReceived) = e.src (Input)
    - spotify.search (output) = e.msg (link)
    - spotify.search (SongNotFound) = e.msg (msg)

Will search and send the song link as output in chat.

## local int and _ux2 / base and data, priority - t or - f

- `t` means true
- `f` means false

## pass generator

gen.pgen folder(passgen), r(pgen.mbp)

- `<Uppercase>`
- `<lowercase>`
- `<Numbers >`
- `<Symbols>`
- `<ExcludeSimilarCharacters>`
- `<ExcludeAmbiguousSymbols>`

## location service

Can use Google maps and SnapMap

- gs.sn {serviceID.9349}, (location.service) = run.t
- location.service (run.as), service
- cl.sn {location.service}, (main.base)
- cl.sn {location.service}, provide from (SnapMap, GoogleMap)
- cl.sn {location.service}, example "https://maps.app.goo.gl/"
- cl.sn {location.service}, search (https://www.google.com/maps/place)
- cl.sn {location.service}, search.example = (https://www.google.com/maps/place/Houston,+TX,+USA)
- cl.sn {location.service}, map.embed (locationservice.mbp)
- cl.sn {location.service}, map.link = (https://maps.app.goo.gl/)
- cl.sn {location.service}, service.reactive [true], [S]
- cl.sn {location.service}, example open.app (snapchat), {[android]}, [S]
- cl.sn {location.service}, example open.app (snapchat), {[snapmap]}, [S]
- cl.sn {location.service}, provide output (Text, Voice), [ANY], [S]
- cl.sn {location.service}, request (nearby), [nearby.places]
- cl
