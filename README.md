# npmtest-wemo-client

#### basic test coverage for  [wemo-client (v0.11.2)](https://github.com/timonreinhard/wemo-client)  [![npm package](https://img.shields.io/npm/v/npmtest-wemo-client.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-wemo-client) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-wemo-client.svg)](https://travis-ci.org/npmtest/node-npmtest-wemo-client)

#### Client library for interacting with Belkin Wemo devices

[![NPM](https://nodei.co/npm/wemo-client.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wemo-client)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-wemo-client/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-wemo-client/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-wemo-client/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-wemo-client/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-wemo-client/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-wemo-client/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-wemo-client/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-wemo-client/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-wemo-client/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-wemo-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-wemo-client/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-wemo-client/build/test-report.html](https://npmtest.github.io/node-npmtest-wemo-client/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-wemo-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-wemo-client/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-wemo-client/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wemo-client/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wemo-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wemo-client/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-wemo-client/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-wemo-client/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "wemo-client",
    "version": "0.11.2",
    "description": "Client library for interacting with Belkin Wemo devices",
    "main": "index.js",
    "directories": {
        "examples": "./examples"
    },
    "scripts": {
        "test": "istanbul test _mocha",
        "test-cov": "istanbul cover _mocha",
        "test-e2e": "mocha ./test-e2e",
        "lint": "eslint *.js",
        "prepush": "npm run lint && npm test",
        "postmerge": "npm install",
        "preversion": "npm test",
        "postversion": "git push && git push --tags"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/timonreinhard/wemo-client.git"
    },
    "author": "Timon Reinhard",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/timonreinhard/wemo-client/issues"
    },
    "homepage": "https://github.com/timonreinhard/wemo-client",
    "keywords": [
        "wemo"
    ],
    "dependencies": {
        "debug": "~2.2.0",
        "entities": "^1.1.1",
        "node-ssdp": "~2.8.0",
        "xml2js": "~0.4.16",
        "xmlbuilder": "^8.2.2"
    },
    "devDependencies": {
        "codeclimate-test-reporter": "^0.1.1",
        "eslint": "^3.2.2",
        "husky": "^0.10.2",
        "istanbul": "^0.4.4",
        "mitm": "^1.3.0",
        "mocha": "^3.0.2",
        "must": "^0.13.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
