LoLFire RESTful JSON API
===========

LOLFIRE SOURCE CODE BIATCHES! https://github.com/alexperezpaya/lolfire-source

LoLfire.com League of Legends Open API Docs

Hello Developer!

We love that people is using our API, but we need a source of income to support the webpage. We don't want you to pay for the api, and we don't want to put adds in. So we are suggesting you to donate
Please! Support the API, we want more machines, you want a fast api for your application.
We are doing the hard work so please consider donating.

#Sorry guys ;( We are not giving API Support by the moment, because we are not getting any donations and we are paying expensive server. I'm 17 and i can't afford it. ASAP as we get enoght money, you can run the lolfire-source to host your own API.


[![Donate :P](https://www.paypalobjects.com/es_ES/ES/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=YAZ274WXMFDY6)
#Thank you! <3


### This API is on development, it can change and get some methods renamed or deprecated.

### Error handling

When an error occurs, the response contaits a {err: [object Object]} response;
When region is down, the response will be: 'Region down, come back later'

### Methods

- Get API Status

http://lolfire.com/api/v1/status

- Get summoner data

http://lolfire.com/api/v1/:region/summoner/:summonername

Where region is a region name, get list of supported regions ins api/v1/status.

Example: http://lolfire.com/api/v1/euw/summoner/NSZombie

- Get summoner stats with acctId provided in (Get summoner data)

http://lolfire.com/api/v1/:region/stats/:acctId

Example: http://lolfire.com/api/v1/euw/stats/36910949

- Get summoner aggregatedStats. They only contain stats when summoner reach level 30

http://lolfire.com/api/v1/:region/aggregatedstats/:acctId

Example: http://lolfire.com/api/v1/euw/aggregatedstats/36910949

- Get summoner matches history

http://lolfire.com/api/v1/:region/matches/:acctId

Example: http://lolfire.com/api/v1/euw/matches/36910949

- Get Summoner Teams

http://lolfire.com/api/v1/:region/teams/:summonerId

Example: http://lolfire.com/api/v1/euw/teams/38277725

- Get Team Data by Id

http://lolfire.com/api/v1/:region/teamdata/:teamId

Example: http://lolfire.com/api/v1/euw/teamdata/TEAM-e542c760-ce84-11e2-8461-782bcb4ce61a

# ACTIVE MATCHES!

http://lolfire.com/api/v1/:region/active/:internalName

No example, find a player in a game and test it! :P

Now only working with europewest. Will be working on eune and na soon!
