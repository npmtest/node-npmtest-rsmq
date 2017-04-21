# npmtest-rsmq

#### basic test coverage for  rsmq (v0.8.2)  [![npm package](https://img.shields.io/npm/v/npmtest-rsmq.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rsmq) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rsmq.svg)](https://travis-ci.org/npmtest/node-npmtest-rsmq)

#### A really simple message queue based on Redis

[![NPM](https://nodei.co/npm/rsmq.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rsmq)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rsmq/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rsmq/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rsmq/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rsmq/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rsmq/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rsmq/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rsmq/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rsmq/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rsmq/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rsmq/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rsmq/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rsmq/build/test-report.html](https://npmtest.github.io/node-npmtest-rsmq/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rsmq/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rsmq/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rsmq/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rsmq/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rsmq/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rsmq/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rsmq/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rsmq/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "rsmq",
    "description": "A really simple message queue based on Redis",
    "version": "0.8.2",
    "license": "MIT",
    "author": "P. Liess <smrchy+npm@gmail.com>",
    "engines": {
        "node": "> 0.10.20"
    },
    "scripts": {
        "test": "mocha ./test/test.js"
    },
    "dependencies": {
        "redis": "^2.6.5",
        "lodash": "^4.17.4"
    },
    "optionalDependencies": {
        "hiredis": "^0.5.0"
    },
    "devDependencies": {
        "mocha": "*",
        "should": "*",
        "async": "*"
    },
    "keywords": [
        "queue",
        "messagequeue",
        "jobs",
        "message-queue",
        "redis"
    ],
    "repository": {
        "type": "git",
        "url": "http://github.com/smrchy/rsmq.git"
    },
    "bugs": {
        "url": "https://github.com/smrchy/rsmq/issues"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
