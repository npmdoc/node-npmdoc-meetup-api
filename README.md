# npmdoc-meetup-api

#### api documentation for  meetup-api (v1.4.12)  [![npm package](https://img.shields.io/npm/v/npmdoc-meetup-api.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-meetup-api) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-meetup-api.svg)](https://travis-ci.org/npmdoc/node-npmdoc-meetup-api)

#### Meetup API library

[![NPM](https://nodei.co/npm/meetup-api.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/meetup-api)

- [https://npmdoc.github.io/node-npmdoc-meetup-api/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-meetup-api/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-meetup-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-meetup-api/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-meetup-api/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-meetup-api/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "meetup-api",
    "description": "Meetup API library",
    "version": "1.4.12",
    "license": "GPL-3.0",
    "directories": {
        "lib": "./lib",
        "example": "./examples"
    },
    "keywords": [
        "meetup",
        "api"
    ],
    "main": "index.js",
    "author": "Juan Pablo Kutianski <jkutianski@gmail.com>",
    "bugs": {
        "url": "http://github.com/jkutianski/meetup-api/issues"
    },
    "engine-strict": true,
    "engines": {
        "node": ">=4.0.0"
    },
    "dependencies": {
        "JSONStream": "1.3.x",
        "event-stream": "3.3.x",
        "superagent": "3.5.x",
        "websocket-stream": "4.0.x"
    },
    "optionalDependencies": {
        "oauth": "0.9.x",
        "proxy-agent": "2.0.x",
        "superagent-oauth": "0.2.x"
    },
    "devDependencies": {
        "forallasync": "1.0.x"
    },
    "repository": {
        "type": "git",
        "url": "http://github.com/jkutianski/meetup-api.git"
    },
    "scripts": {
        "test": "node ./test/testEndpoints.js"
    },
    "tonicExampleFilename": "tonicExample.js"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
