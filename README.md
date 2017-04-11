# test coverage for  [primus (v7.0.0)](http://primus.io)  [![npm package](https://img.shields.io/npm/v/npmtest-primus.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-primus) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-primus.svg)](https://travis-ci.org/npmtest/node-npmtest-primus)
#### Primus is a simple abstraction around real-time frameworks. It allows you to easily switch between different frameworks without any code changes.

[![NPM](https://nodei.co/npm/primus.png?downloads=true)](https://www.npmjs.com/package/primus)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-primus/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-primus/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-primus/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-primus/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-primus/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-primus/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-primus/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-primus/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-primus/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-primus/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-primus%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-primus/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-primus/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-primus%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-primus/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-primus/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-primus/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Arnout Kazemier"
    },
    "bugs": {
        "url": "https://github.com/primus/primus/issues"
    },
    "dependencies": {
        "access-control": "~1.0.0",
        "asyncemit": "~3.0.1",
        "create-server": "~1.0.1",
        "diagnostics": "~1.1.0",
        "eventemitter3": "~2.0.2",
        "forwarded-for": "~1.0.1",
        "fusing": "~1.0.0",
        "setheader": "~0.0.4",
        "ultron": "~1.1.0",
        "yeast": "~0.1.2"
    },
    "description": "Primus is a simple abstraction around real-time frameworks. It allows you to easily switch between different frameworks without any code changes.",
    "devDependencies": {
        "binary-pack": "~1.0.2",
        "browserchannel": "~2.0.0",
        "browserify": "~14.1.0",
        "chai": "~3.5.0",
        "condenseify": "~1.1.1",
        "demolish": "~1.0.2",
        "derequire": "~2.0.3",
        "deumdify": "~1.2.3",
        "ejson": "~2.1.2",
        "emits": "~3.0.0",
        "engine.io": "~2.1.0",
        "engine.io-client": "~2.1.0",
        "faye-websocket": "~0.11.0",
        "inherits": "~2.0.3",
        "mocha": "~3.2.0",
        "pre-commit": "~1.2.0",
        "primus-msgpack": "~1.0.2",
        "pumpify": "~1.3.5",
        "querystringify": "~1.0.0",
        "recovery": "~0.2.6",
        "request": "~2.81.0",
        "rocambole": "~0.7.0",
        "rocambole-node-remove": "~1.0.0",
        "sockjs": "~0.3.18",
        "sockjs-client": "~1.1.1",
        "through2": "~2.0.1",
        "tick-tock": "~1.0.0",
        "url-parse": "~1.1.7",
        "uws": "~0.14.0",
        "ws": "~2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d37adff33954277139e76df222828160e0b563e3",
        "tarball": "https://registry.npmjs.org/primus/-/primus-7.0.0.tgz"
    },
    "gitHead": "30d4a46cb2c7e1ae53524519cdf9d1ca5c133d8f",
    "homepage": "http://primus.io",
    "keywords": [
        "abstraction",
        "browserchannel",
        "engine.io",
        "framework",
        "comet",
        "streaming",
        "pubsub",
        "pub",
        "sub",
        "ajax",
        "xhr",
        "polling",
        "http",
        "faye",
        "io",
        "primus",
        "prumus",
        "real-time",
        "realtime",
        "socket",
        "socket.io",
        "sockets",
        "sockjs",
        "spark",
        "transformer",
        "transformers",
        "websocket",
        "websockets",
        "ws",
        "uws"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jcrugzz",
            "email": "jcrugzz@gmail.com"
        },
        {
            "name": "swaagie",
            "email": "info@martijnswaagman.nl"
        },
        {
            "name": "lpinca",
            "email": "luigipinca@gmail.com"
        },
        {
            "name": "davedoesdev",
            "email": "dahalls@gmail.com"
        },
        {
            "name": "v1",
            "email": "info@3rd-Eden.com"
        },
        {
            "name": "3rdeden",
            "email": "npm@3rd-Eden.com"
        }
    ],
    "name": "primus",
    "optionalDependencies": {},
    "pre-commit": "test, integration",
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/primus/primus.git"
    },
    "scripts": {
        "build": "mkdir -p dist && browserify primus.js -s Primus -p deumdify | derequire > dist/primus.js",
        "integration": "npm run build && mocha test/*.integration.js",
        "prepublish": "npm run build",
        "test": "npm run build && mocha test/*.test.js",
        "update": "find transformers -name update.sh -exec bash {} \\;"
    },
    "version": "7.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
