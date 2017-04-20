# npmdoc-frisby

#### api documentation for  [frisby (v0.8.5)](http://frisbyjs.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-frisby.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-frisby) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-frisby.svg)](https://travis-ci.org/npmdoc/node-npmdoc-frisby)

#### Frisby.js: REST API Endpoint Testing built on Jasmine

[![NPM](https://nodei.co/npm/frisby.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/frisby)

- [https://npmdoc.github.io/node-npmdoc-frisby/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-frisby/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-frisby/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-frisby/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-frisby/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-frisby/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "frisby",
    "version": "0.8.5",
    "description": "Frisby.js: REST API Endpoint Testing built on Jasmine",
    "homepage": "http://frisbyjs.com",
    "author": "Vance Lucas <vance@vancelucas.com>",
    "license": {
        "type": "BSD"
    },
    "contributors": [
        "Eric Boehs <ericboehs@gmail.com>",
        "Kevin Morey"
    ],
    "repository": {
        "type": "git",
        "url": "http://github.com/vlucas/frisby"
    },
    "keywords": [
        "testing",
        "api",
        "REST",
        "jasmine",
        "bdd",
        "frisby"
    ],
    "dependencies": {
        "request": ">=2.51",
        "jsonschema": "1.0.0",
        "stack-trace": "0.0.x",
        "mock-request": ">= 0.1.2",
        "nock": "*",
        "underscore": "1.6.x",
        "qs": "1.2.x"
    },
    "devDependencies": {
        "jasmine-node": "~1.14.5",
        "form-data": "~0.1.4"
    },
    "main": "./lib/frisby",
    "engines": {
        "node": ">= 0.10.0"
    },
    "scripts": {
        "test": "jasmine-node spec/"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
