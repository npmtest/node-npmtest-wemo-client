# npmtest-wemo-client

#### basic test coverage for  [wemo-client (v0.11.2)](https://github.com/timonreinhard/wemo-client)  [![npm package](https://img.shields.io/npm/v/npmtest-wemo-client.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-wemo-client) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-wemo-client.svg)](https://travis-ci.org/npmtest/node-npmtest-wemo-client)

#### Client library for interacting with Belkin Wemo devices

[![NPM](https://nodei.co/npm/wemo-client.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wemo-client)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-wemo-client/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-wemo-client/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-wemo-client/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-wemo-client/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-wemo-client/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-wemo-client/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-wemo-client/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-wemo-client/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-wemo-client/tree/gh-pages/build)|

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
    "author": {
        "name": "Timon Reinhard"
    },
    "bugs": {
        "url": "https://github.com/timonreinhard/wemo-client/issues"
    },
    "dependencies": {
        "debug": "~2.2.0",
        "entities": "^1.1.1",
        "node-ssdp": "~2.8.0",
        "xml2js": "~0.4.16",
        "xmlbuilder": "^8.2.2"
    },
    "description": "Client library for interacting with Belkin Wemo devices",
    "devDependencies": {
        "codeclimate-test-reporter": "^0.1.1",
        "eslint": "^3.2.2",
        "husky": "^0.10.2",
        "istanbul": "^0.4.4",
        "mitm": "^1.3.0",
        "mocha": "^3.0.2",
        "must": "^0.13.2"
    },
    "directories": {
        "examples": "./examples"
    },
    "dist": {
        "shasum": "b36efba5fcf98ed7ef7a07c8c0cdc02428442154",
        "tarball": "https://registry.npmjs.org/wemo-client/-/wemo-client-0.11.2.tgz"
    },
    "gitHead": "c8980e826ab5293affb94e9ee85dd2fd5f6bf9ca",
    "homepage": "https://github.com/timonreinhard/wemo-client",
    "keywords": [
        "wemo"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "timonreinhard"
        }
    ],
    "name": "wemo-client",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/timonreinhard/wemo-client.git"
    },
    "scripts": {
        "lint": "eslint *.js",
        "postmerge": "npm install",
        "postversion": "git push && git push --tags",
        "prepush": "npm run lint && npm test",
        "preversion": "npm test",
        "test": "istanbul test _mocha",
        "test-cov": "istanbul cover _mocha",
        "test-e2e": "mocha ./test-e2e"
    },
    "version": "0.11.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
