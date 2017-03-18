# battle.net swagger
Swagger schemes for the Blizzard (tm) battle.net API's

# Development stuff
## Notes on blizzard's API
Some random notes on the API design that stand out.
- Didn't see a way a HTTP header for the API key instead of a query parameter
- [d3] Calling the profile method with an invalid battle-tag gives a HTTP 200 with an error document instead of a HTTP 404

## TODO
- Determine if the swagger files should mimic the mashery structure and have an API per region or just use tags for the methods available in a region.
- [d3] Add definitions
- [d3] Add return data
- [d3] Add data APIs
- [gamedata] Actually start on the scheme 
- [profile] Actually start on the scheme 
- [sc2] Actually start on the scheme 
- [wow] Actually start on the scheme 

# Contributing
If you want to contribute, please fork this repo and send a pull request.
All help is highly appreciated (and ofcourse is credited).

## Contributors
- [barredijkstra](https://github.com/barredijkstra/)