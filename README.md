lolfire-api
===========

LoLfire.com League of Legends Open API Docs

# This API is on development, it can change and get some methods renamed or deprecated. Maybe it will work with API keys.

This is a JSON API.

### Error handling

When an error occurs, the response contaits a {err: [object Object]} response;
When region is down, the response will be: 'Region down, come back later'

### Methods

- Get API Status
/api/v1/status

- Get summoner data
/api/v1/:region/summoner/:summonername

- Get summoner stats with acctId provided in (Get summoner data)
/api/v1/:region/stats/:summonerid

- Get summoner aggregatedStats. They only contain stats when summoner reach level 30
/api/v1/:region/aggregatedstats/:summonerid

- Get summoner matches history
/api/v1/:region/matches/:summonerid

- Get Summoner Teams
/api/v1/:region/teams/:summonerid

- Get Team Data by Id
/api/v1/:region/teamdata/:teamid
