## 💊 mons coding language
# Fast - Smooth - Clean

<br>

<img src="https://github.com/HotCakeX/Harden-Windows-Security/raw/main/images/Gifs/1pxRainbowLine.gif" width= "300000" alt="horizontal super thin rainbow RGB line">

<br>

Rulesets example

```coffeescript
[ruleset.V], which means ruleset.VALID
[ruleset.B], which means ruleset.BLOCK
```
State Loading and Looping Example
```coffeescript
state ID {load},
state ID {loop},
```
If you want to detect any errors and send the reason to admin panel
```coffeescript
i, error(any), e.msg(reason),
```

## Easy baritone for Minecraft
- create baritone.mbp
- make sure the folder is in same folder
```coffeescript
read.folder(baritone), read.mbp(baritone.mbp),
baritone.mons {github}, - ruleset.V
baritone.mons folder(baritone), (baritone.mbp), - ruleset.V
baritone.mons (update.loop),
baritone.mons {allowInventory.cb}, - ruleset.V
```
- baritone repo - https://github.com/cabaletta/baritone
  
<p align="center">
  <a href="#Baritone"><img src="https://img.shields.io/badge/MC-1.12.2-brightgreen.svg" alt="Minecraft"/></a>
  <a href="#Baritone"><img src="https://img.shields.io/badge/MC-1.13.2-yellow.svg" alt="Minecraft"/></a>
  <a href="#Baritone"><img src="https://img.shields.io/badge/MC-1.14.4-yellow.svg" alt="Minecraft"/></a>
  <a href="#Baritone"><img src="https://img.shields.io/badge/MC-1.15.2-yellow.svg" alt="Minecraft"/></a>
  <a href="#Baritone"><img src="https://img.shields.io/badge/MC-1.16.5-yellow.svg" alt="Minecraft"/></a>
  <a href="#Baritone"><img src="https://img.shields.io/badge/MC-1.17.1-yellow.svg" alt="Minecraft"/></a>
  <a href="#Baritone"><img src="https://img.shields.io/badge/MC-1.18.2-yellow.svg" alt="Minecraft"/></a>
  <a href="#Baritone"><img src="https://img.shields.io/badge/MC-1.19.2-brightgreen.svg" alt="Minecraft"/></a>
  <a href="#Baritone"><img src="https://img.shields.io/badge/MC-1.19.4-brightgreen.svg" alt="Minecraft"/></a>
  <a href="#Baritone"><img src="https://img.shields.io/badge/MC-1.20.1-brightgreen.svg" alt="Minecraft"/></a>
</p>

**Quick download links:**

| Forge                                                                                                         | Fabric                                                                                                        |
|---------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| [1.12.2 Forge](https://github.com/cabaletta/baritone/releases/download/v1.2.19/baritone-api-forge-1.2.19.jar) |                                                                                                               |
| [1.16.5 Forge](https://github.com/cabaletta/baritone/releases/download/v1.6.5/baritone-api-forge-1.6.5.jar)   | [1.16.5 Fabric](https://github.com/cabaletta/baritone/releases/download/v1.6.5/baritone-api-fabric-1.6.5.jar) |
| [1.17.1 Forge](https://github.com/cabaletta/baritone/releases/download/v1.7.3/baritone-api-forge-1.7.3.jar)   | [1.17.1 Fabric](https://github.com/cabaletta/baritone/releases/download/v1.7.3/baritone-api-fabric-1.7.3.jar) |
| [1.18.2 Forge](https://github.com/cabaletta/baritone/releases/download/v1.8.5/baritone-api-forge-1.8.5.jar)   | [1.18.2 Fabric](https://github.com/cabaletta/baritone/releases/download/v1.8.5/baritone-api-fabric-1.8.5.jar) |
| [1.19.2 Forge](https://github.com/cabaletta/baritone/releases/download/v1.9.4/baritone-api-forge-1.9.4.jar)   | [1.19.2 Fabric](https://github.com/cabaletta/baritone/releases/download/v1.9.4/baritone-api-fabric-1.9.4.jar) |
| [1.19.3 Forge](https://github.com/cabaletta/baritone/releases/download/v1.9.1/baritone-api-forge-1.9.1.jar)   | [1.19.3 Fabric](https://github.com/cabaletta/baritone/releases/download/v1.9.1/baritone-api-fabric-1.9.1.jar) |
| [1.19.4 Forge](https://github.com/cabaletta/baritone/releases/download/v1.9.3/baritone-api-forge-1.9.3.jar)   | [1.19.4 Fabric](https://github.com/cabaletta/baritone/releases/download/v1.9.3/baritone-api-fabric-1.9.3.jar) |
| [1.20.1 Forge](https://github.com/cabaletta/baritone/releases/download/v1.10.1/baritone-api-forge-1.10.1.jar)   | [1.20.1 Fabric](https://github.com/cabaletta/baritone/releases/download/v1.10.1/baritone-api-fabric-1.10.1.jar) |



# Locals
```coffeescript
iplocal.mbp (static),
datalocal.mbp (static),
dataprivate.mbp (static),

local.bmo (break), fa
local.bmo (load), fa
```

# Ping / Network
```coffeescript
system.ping [S],
system.network [S],
```

# Data Holders (EXAMPLE)
```coffeescript
data.holder {dbfr},
data.holder {bflk},
data.holder {prsn},
data.holder {bfma},
```

# Load, exec, userlevel
```coffeescript
<p3bload>, <exec>, <userexeclevel>
```

# Commands.build (IMPORTANT)
```coffeescript
 commands.build <2385710237120498358123934571238359812398>
 commands.build <3157102987340198540917230098091809581237>
 commands.build <1239418739548619283712345986781239871234>
```

# Important Loops
```coffeescript
loop main.pr ^execl _$BMFNASMFK > 58912834
loop main.pr ^execl _$JFZXCBNMA > 23509812
loop main.pr ^execl _$VNOEWPLAS > 85293124

main.pr (7), <IDP> > main.pr (1), <QPS> > main.pr (9), <VEQ>
main.pr (2), <QBG> > main.pr (8), <LPT> > main.pr (6), <BGH>
main.pr (4), <ITR> > main.pr (3), <VNC> > main.pr (0), <BXZ>
```

# Important state ID's
```coffeescript
 state $349178524356917823123 {mtr},
 state.id{if.local}, = mtr_load (base), - ruleset.V
 state $324967912873987395691 {mtr},
 state.id{if.local}, = mtr_load (base), - ruleset.V
 state $289395801802398025709 {flp},
 state.id{if.local}, = flp_load (base), - ruleset.V
```

# sld ID'S
```coffeescript
sld [349209, 34592, 32000, 92500],
sld [938412, 18359, 75481, 34858],
sld [125849, 59422, 57829, 10394],
```
# LOGS/LIMITERS/RULES/VERSIONS
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
```

# NEEDS TO BE LOADED

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

```


## Long example
```coffeescript
bct.wfm [SN], bct.ry f = r.apanel - ruleset.V
bct.sfm [RD], bct.ry f = r.apanel - ruleset.V
bct.wfs [RD], bct.ry f = r.apanel - ruleset.V
bct.rly [RY], bct.ry f = r.apanel - ruleset.V
bct.lup [LP], bct.ry f = r.apanel - ruleset.V
```

`r panel (role_panel) roles [admin/owner/mod],`

# List: ram/memory/cpu/ssd/network

```coffeescript
p.ram {[main]},
p.mem {[main]},
p.cpu {[main]},
p.ram {[main]},
p.ssd {[main]},
p.nwk {[main]},
```

# States
- load/loop
```coffeescript
state 34901104939057019278380180948052307820934851340891350978180923413057941039478 {load},
state 39028540491702348259691836794871982377037509172834791657987123097107093785989 {loop},
```

## loop.state and rulesets

```coffeescript
loop.state (mainstates), $ state.states - ruleset.V
loop.state (mainstates), $ all.states - ruleset.V
```

- `ruleset.V` means ruleset.VALID
- `ruleset.B` means ruleset.BLOCK

## library

```coffeescript
- lib - /libraryV1/old/
- lib - /libraryV2/old/
- lib - /libraryV3/old/
- lib - /libraryV4/old/
- lib - /libraryV5/old/
- lib - /libraryV6/old/
- lib - /libraryV7/current/
- load.latest (library), ruleset.V
```
No version limit.

## chat reply states

```coffeescript
- chat.reply (/)
- chat.reply (state), $ main (2340578023799909571)
- chat.reply (state), $ main (2357897150983247839)
- chat.reply (state), $ main (8549280392580939812)
- chat.reply $stateFalse = e.msg (cRP 23509)
- chat.reply $stateError = e.msg (cRP 90250)
- chat.reply $stateBlackList = e.msg (cRP 935000)
```

## call.id / call states

```coffeescript
- states - ruleset.V
- call.id $ 59 [S]
- call.id $ 50 [S]
- call.id $ 30 [S]
- call.id $ 12 [S]
- call.id $ 91 [S]
```

## Spotify search

```coffeescript
- spotify.search [S]
- spotify.search (waitforInput) - ruleset.V
  - spotify.search (InputReceived) = e.src (Input)
    - spotify.search (output) = e.msg (link)
    - spotify.search (SongNotFound) = e.msg (msg)
```
Will search and send the song link as output in chat.

## local int and _ux2 / base and data, priority - t or - f

- `t` means true
- `f` means false

## pass generator

gen.pgen folder(passgen), r(pgen.mbp)
```coffeescript
- `<Uppercase>`
- `<lowercase>`
- `<Numbers >`
- `<Symbols>`
- `<ExcludeSimilarCharacters>`
- `<ExcludeAmbiguousSymbols>`
```

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
```
