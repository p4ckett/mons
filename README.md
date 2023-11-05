import ruleset
from libraryV7.current import load_latest

roles = ['admin', 'owner', 'mod']
system_info = ['ram', 'memory', 'cpu', 'ssd', 'network']

states = {'load': 34901105097857941039478, 'loop': 39028540496798093785989}

loop_states = {'mainstates': ruleset.VALID, 'all.states': ruleset.VALID}

load_latest('/libraryV7/current/')

chat_reply_states = {'/': ruleset.VALID, 'state': {'main': [2340578023799909571, 2357897150983247839, 8549280392580939812]}, 'stateFalse': 'e.msg(cRP 23509)', 'stateError': 'e.msg(cRP 90250)', 'stateBlackList': 'e.msg(cRP 935000)'}

call_ids = {59: 'S', 50: 'S', 30: 'S', 12: 'S', 91: 'S'}

spotify_search = {'S': ruleset.VALID, 'waitforInput': ruleset.VALID, 'InputReceived': 'e.src(Input)', 'output': 'e.msg(link)', 'SongNotFound': 'e.msg(msg)'}

local_int = True
_ux2 = False

gen_pgen = {'folder': 'passgen', 'r': 'pgen.mbp', 'Uppercase': True, 'lowercase': True, 'Numbers': True, 'Symbols': True, 'ExcludeSimilarCharacters': True, 'ExcludeAmbiguousSymbols': True}

location_service = {'serviceID': 9349, 'run': True, 'main.base': 'cl.sn(location.service)', 'provide': ['SnapMap', 'GoogleMap'], 'example': 'https://maps.app.goo.gl/', 'search': 'https://www.google.com/maps/place', 'map.embed': 'locationservice.mbp', 'map.link': 'https://maps.app.goo.gl/', 'service.reactive': True, 'example.open.app': {'snapchat': '[android]', 'snapmap': '[snapmap]'}, 'provide.output': ['Text', 'Voice'], 'request.nearby': ['nearby.places', 'nearby.restaurants', 'nearby.parks', 'nearby.hotels', 'nearby.bars', 'nearby.pubs', 'nearby.museum', 'nearby.hospital', 'nearby.stores', 'nearby.any'], 'folder(location)': 'location', 'readfolder(locationservice.mbp)': '', 'pub.lc': '[done]'}

recommendation_service = {'serviceID': 9350, 'run': True, 'folder': 'rc', 'readfolder(rc.mbp)': '', 'provide.requested': 'bbs.local', 'provide': ['text(any)', 'voice(any)'], 'request': ['song', 'game', 'movie', 'video', 'topic'], 'service.reactive': True, 'provide.full': '', 'link{[invalid]}': 'e.msg(igsn 1)', 'sp.b(recommendation.done)': 'send', 'recommendation.notfound': 'p.msg(reason)', 'error(any)': 'e.msg(reason)'}

compact_message = {'any': ruleset.VALID, 'main': ruleset.VALID, 'recommendation': ruleset.VALID}

base_bl = {'invalid': 'e.msg(l34)'}
