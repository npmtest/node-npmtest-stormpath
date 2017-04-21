# npmtest-stormpath

#### basic test coverage for  [stormpath (v0.20.1)](https://github.com/stormpath/stormpath-sdk-node)  [![npm package](https://img.shields.io/npm/v/npmtest-stormpath.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-stormpath) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-stormpath.svg)](https://travis-ci.org/npmtest/node-npmtest-stormpath)

#### Official Stormpath SDK for Node.js

[![NPM](https://nodei.co/npm/stormpath.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/stormpath)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-stormpath/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-stormpath/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-stormpath/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-stormpath/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-stormpath/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-stormpath/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-stormpath/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-stormpath/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-stormpath/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-stormpath/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-stormpath/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-stormpath/build/test-report.html](https://npmtest.github.io/node-npmtest-stormpath/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-stormpath/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-stormpath/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-stormpath/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-stormpath/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stormpath/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stormpath/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-stormpath/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-stormpath/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stormpath, Inc.",
        "url": "http://www.stormpath.com"
    },
    "bugs": {
        "url": "https://github.com/stormpath/stormpath-sdk-node/issues"
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
    "description": "Official Stormpath SDK for Node.js",
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
    },
    "directories": {},
    "dist": {
        "shasum": "018dc778eec9f20702d9765c8b440cc95d413cf2",
        "tarball": "https://registry.npmjs.org/stormpath/-/stormpath-0.20.1.tgz"
    },
    "gitHead": "9ba364209e522d39fcc28ff689d67a12fb325f97",
    "homepage": "https://github.com/stormpath/stormpath-sdk-node",
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
    "main": "lib/stormpath.js",
    "maintainers": [
        {
            "name": "lhazlewood"
        },
        {
            "name": "rdegges"
        },
        {
            "name": "robertjd"
        },
        {
            "name": "timothyej"
        },
        {
            "name": "typerandom"
        }
    ],
    "name": "stormpath",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/stormpath/stormpath-sdk-node.git"
    },
    "scripts": {
        "coverage": "node ./node_modules/istanbul/lib/cli cover ./node_modules/mocha/bin/_mocha",
        "docs": "jsdoc -c ./docs/jsdoc.json -d ./apidocs/ -P ./package.json -r lib/ --readme ./docs/JSDOC.md",
        "test": "grunt"
    },
    "version": "0.20.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
