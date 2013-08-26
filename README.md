google.geolocation-ts
==

This repository makes the Google Geolocation TypeScript definitions from [DefinitelyTyped](https://github.com/borisyankov/DefinitelyTyped) available on [Bower](http://bower.io) as `google.geolocation-ts`. If you want Google Geolocation type definitions by you're not using Bower, get the type definitions from the DefinitelyTyped repository as they will always be at least as current as my copy and quite likely ahead.

This repository will be periodically refreshed from DefinitelyTyped as changes are made.

Getting the Google Geolocation type definitions
--
Method 1:
`bower install google.geolocation-ts`

Method 2:

Add `google.geolocation-ts` to your bower.json `"dependencies"` list:

    {
      "name": "myApp",
      "version": "0.1.0",
      "dependencies": {
        "google.geolocation-ts": "latest"
      }
    }

TypeScript and Google Geolocation versions
--
I make no promises regarding the version of TypeScript and Google Geolocation currently supported by these type definitions. I have no plans to support multiple versions (although I may create tags as necessary) as this is just a copy of a subset of DefinitelyTyped.