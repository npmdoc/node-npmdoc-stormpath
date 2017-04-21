# npmdoc-stormpath

#### api documentation for  [stormpath (v0.20.1)](https://github.com/stormpath/stormpath-sdk-node)  [![npm package](https://img.shields.io/npm/v/npmdoc-stormpath.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-stormpath) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-stormpath.svg)](https://travis-ci.org/npmdoc/node-npmdoc-stormpath)

#### Official Stormpath SDK for Node.js

[![NPM](https://nodei.co/npm/stormpath.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/stormpath)

- [https://npmdoc.github.io/node-npmdoc-stormpath/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-stormpath/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stormpath/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stormpath/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-stormpath/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-stormpath/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "stormpath",
    "version": "0.20.1",
    "main": "lib/stormpath.js",
    "description": "Official Stormpath SDK for Node.js",
    "keywords": [
        "stormpath",
        "api",
        "wrapper",
        "sdk",
        "client",
        "user",
        "user management",
        "user login",
        "identity",
        "identity management",
        "account",
        "account login",
        "login",
        "authentication",
        "authorization",
        "access control",
        "password",
        "password hash"
    ],
    "license": "Apache-2.0",
    "homepage": "https://github.com/stormpath/stormpath-sdk-node",
    "bugs": "https://github.com/stormpath/stormpath-sdk-node/issues",
    "author": {
        "name": "Stormpath, Inc.",
        "url": "http://www.stormpath.com"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/stormpath/stormpath-sdk-node.git"
    },
    "scripts": {
        "coverage": "node ./node_modules/istanbul/lib/cli cover ./node_modules/mocha/bin/_mocha",
        "docs": "./node_modules/.bin/jsdoc -c ./docs/jsdoc.json -d ./apidocs/ -P ./package.json -r lib/ --readme ./docs/JSDOC.md",
        "test": "grunt"
    },
    "dependencies": {
        "async": "~1.5.2",
        "deep-extend": "^0.4.1",
        "jwt-simple": "~0.4.0",
        "memcached": "~2.2.2",
        "moment": "^2.15.2",
        "njwt": "^0.4.0",
        "properties-parser": "~0.3.1",
        "redis": "~2.6.2",
        "request": "~2.74.0",
        "stormpath-config": "0.0.27",
        "underscore": "~1.5.2",
        "underscore.string": "~3.2.3",
        "uuid": "^3.0.0",
        "xtend": "^4.0.1"
    },
    "devDependencies": {
        "benchmark": "^2.0.0",
        "chai": "~3.5.0",
        "coveralls": "^2.11.11",
        "expand-home-dir": "0.0.3",
        "fake-fs": "^0.5.0",
        "grunt": "~1.0.1",
        "grunt-cli": "~1.2.0",
        "grunt-contrib-jshint": "~0.11.3",
        "grunt-contrib-watch": "~1.0.0",
        "grunt-mocha-istanbul": "~5.0.1",
        "grunt-mocha-test": "~0.12.7",
        "httpster": "^1.0.3",
        "ink-docstrap": "^1.1.4",
        "istanbul": "^0.4.4",
        "js-yaml": "~3.6.1",
        "jsdoc": "^3.4.0",
        "jshint-stylish": "~2.2.0",
        "load-grunt-tasks": "~3.5.0",
        "lodash": "^4.0.1",
        "mocha": "~2.5.3",
        "mocha-sinon": "~1.1.0",
        "nock": "~8.0.0",
        "nodemon": "^1.9.1",
        "sinon": "~1.17.3",
        "sinon-chai": "~2.8.0",
        "time-grunt": "~1.4.0",
        "timekeeper": "~0.1.1",
        "tmp": "0.0.28"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
