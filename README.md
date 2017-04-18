# npmtest-deferred

test coverage for  [deferred (v0.7.6)](https://github.com/medikoo/deferred#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-deferred.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-deferred) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-deferred.svg)](https://travis-ci.org/npmtest/node-npmtest-deferred)
#### Modular and fast Promises implementation

[![NPM](https://nodei.co/npm/deferred.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/deferred)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-deferred/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-deferred/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-deferred/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-deferred/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-deferred/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-deferred/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-deferred/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-deferred/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-deferred/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-deferred/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-deferred/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-deferred/build/test-report.html](https://npmtest.github.io/node-npmtest-deferred/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-deferred/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-deferred/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-deferred/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-deferred/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-deferred/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-deferred/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-deferred/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-deferred/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mariusz Nowak",
        "url": "http://www.medikoo.com/"
    },
    "bugs": {
        "url": "https://github.com/medikoo/deferred/issues"
    },
    "dependencies": {
        "d": "1",
        "es5-ext": "~0.10.14",
        "event-emitter": "~0.3.5",
        "next-tick": "1",
        "timers-ext": "~0.1.1"
    },
    "description": "Modular and fast Promises implementation",
    "devDependencies": {
        "tad": "~0.2.7",
        "xlint": "~0.2.2",
        "xlint-jslint-medikoo": "~0.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "9fd46d3d3d93dd7ec3d8561460dc7e403c1042c4",
        "tarball": "https://registry.npmjs.org/deferred/-/deferred-0.7.6.tgz"
    },
    "gitHead": "17af2e74dfae2ae8fc2110c577155f05df2b3501",
    "homepage": "https://github.com/medikoo/deferred#readme",
    "keywords": [
        "async",
        "asynchronous",
        "deferred",
        "flow",
        "future",
        "futures",
        "promise",
        "promises",
        "continuations"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "medikoo"
        }
    ],
    "name": "deferred",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/medikoo/deferred.git"
    },
    "scripts": {
        "lint": "node node_modules/xlint/bin/xlint --linter=node_modules/xlint-jslint-medikoo/index.js --no-cache --no-stream",
        "lint-console": "node node_modules/xlint/bin/xlint --linter=node_modules/xlint-jslint-medikoo/index.js --watch",
        "test": "node ./node_modules/tad/bin/tad"
    },
    "version": "0.7.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
