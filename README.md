# npmdoc-demeteorizer

#### basic api documentation for  [demeteorizer (v4.3.0)](https://github.com/OnModulus/demeteorizer#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-demeteorizer.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-demeteorizer) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-demeteorizer.svg)](https://travis-ci.org/npmdoc/node-npmdoc-demeteorizer)

#### Converts a Meteor app into a "standard" Node.js application.

[![NPM](https://nodei.co/npm/demeteorizer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/demeteorizer)

- [https://npmdoc.github.io/node-npmdoc-demeteorizer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-demeteorizer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-demeteorizer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-demeteorizer/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-demeteorizer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-demeteorizer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Modulus"
    },
    "bin": {
        "demeteorizer": "./bin/demeteorizer"
    },
    "bugs": {
        "url": "https://github.com/OnModulus/demeteorizer/issues"
    },
    "contributors": [
        {
            "name": "Brandon Cannaday"
        },
        {
            "name": "Bret Fisher"
        },
        {
            "name": "Matt Hernandez"
        },
        {
            "name": "Tarang Patel"
        },
        {
            "name": "Vincil Bishop"
        }
    ],
    "dependencies": {
        "commander": "2.9.0",
        "cross-spawn": "5.0.1",
        "fs-extra": "0.30.0",
        "hoek": "4.x.x",
        "semver": "5.1.0"
    },
    "description": "Converts a Meteor app into a \"standard\" Node.js application.",
    "devDependencies": {
        "code": "4.0.0",
        "lab": "11.2.1",
        "proxyquire": "1.7.10",
        "sinon": "1.17.6",
        "standard": "8.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "27751a48eab483d34c06642b0e343832f5d0f993",
        "tarball": "https://registry.npmjs.org/demeteorizer/-/demeteorizer-4.3.0.tgz"
    },
    "engines": {
        "node": ">=4",
        "npm": ">=3.10.8"
    },
    "gitHead": "c10c41a9c587dfed8617383ef2d1f99d5c819c49",
    "homepage": "https://github.com/OnModulus/demeteorizer#readme",
    "keywords": [
        "meteor"
    ],
    "license": "MIT",
    "main": "./lib/demeteorizer",
    "maintainers": [
        {
            "name": "fiveisprime"
        },
        {
            "name": "harlanj"
        },
        {
            "name": "jackboberg"
        }
    ],
    "name": "demeteorizer",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/OnModulus/demeteorizer.git"
    },
    "scripts": {
        "gen-coverage": "lab --coverage --reporter lcov --output coverage/lcov.info",
        "pretest": "standard",
        "test": "lab --threshold 100"
    },
    "version": "4.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
