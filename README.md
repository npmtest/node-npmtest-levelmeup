# npmtest-levelmeup

#### basic test coverage for  [levelmeup (v1.0.0)](https://github.com/workshopper/levelmeup#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-levelmeup.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-levelmeup) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-levelmeup.svg)](https://travis-ci.org/npmtest/node-npmtest-levelmeup)

#### Level Me Up Scotty! An intro to Node.js databases via a set of self-guided workshops.

[![NPM](https://nodei.co/npm/levelmeup.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/levelmeup)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-levelmeup/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-levelmeup/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-levelmeup/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-levelmeup/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-levelmeup/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-levelmeup/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-levelmeup/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-levelmeup/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-levelmeup/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-levelmeup/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-levelmeup/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-levelmeup/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-levelmeup/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-levelmeup/build/test-report.html](https://npmtest.github.io/node-npmtest-levelmeup/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-levelmeup/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-levelmeup/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-levelmeup/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-levelmeup/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-levelmeup/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-levelmeup/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-levelmeup/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-levelmeup/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rod Vagg",
        "url": "https://github.com/rvagg"
    },
    "bin": {
        "levelmeup": "./bin/levelmeup"
    },
    "bugs": {
        "url": "https://github.com/workshopper/levelmeup/issues"
    },
    "contributors": [
        {
            "name": "Rod Vagg",
            "url": "https://github.com/rvagg"
        },
        {
            "name": "Eugene Ware",
            "url": "https://github.com/eugeneware"
        },
        {
            "name": "James Halliday",
            "url": "https://github.com/substack"
        },
        {
            "name": "Jake Verbaten",
            "url": "https://github.com/raynos"
        },
        {
            "name": "Julian Gruber",
            "url": "https://github.com/juliangruber"
        },
        {
            "name": "Robert Kowalski",
            "url": "https://github.com/robertkowalski"
        },
        {
            "name": "Lars-Magnus Skog",
            "url": "https://github.com/ralphtheninja"
        },
        {
            "name": "Martin Heidegger",
            "url": "https://github.com/martinheidegger"
        },
        {
            "name": "Masashi Hirano",
            "url": "https://github.com/masashi-t-h"
        },
        {
            "name": "Akihito Takeuchi",
            "url": "https://github.com/akihito-takeuchi"
        }
    ],
    "dependencies": {
        "deep-diff": "^0.3.4",
        "echomunge": "~0.2.0",
        "exec-module": "^2.0.0",
        "is-stream": "^1.1.0",
        "level": "^1.5.0",
        "level-sublevel": "^6.6.1",
        "lodash.sample": "^4.2.1",
        "multilevel": "^7.3.0",
        "rimraf": "~2.5.4",
        "through2": "^2.0.1",
        "workshopper-adventure": "^5.1.3"
    },
    "description": "Level Me Up Scotty! An intro to Node.js databases via a set of self-guided workshops.",
    "devDependencies": {
        "standard": "^8.4.0",
        "twitter": "^1.7.0",
        "workshopper-adventure-test": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "656cc741cd3d64ded0634a211fea35e0198b9434",
        "tarball": "https://registry.npmjs.org/levelmeup/-/levelmeup-1.0.0.tgz"
    },
    "gitHead": "9b54002e52200a3744750ae76d2c5a60c40bc989",
    "homepage": "https://github.com/workshopper/levelmeup#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "rvagg"
        },
        {
            "name": "juliangruber"
        },
        {
            "name": "ralphtheninja"
        }
    ],
    "name": "levelmeup",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/workshopper/levelmeup.git"
    },
    "scripts": {
        "fetch-horse": "./scripts/fetch_horse.js",
        "lint": "standard",
        "test": "standard && workshopper-adventure-test"
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
