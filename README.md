# npmtest-redux-promise

#### basic test coverage for  [redux-promise (v0.5.3)](https://github.com/acdlite/redux-promise)  [![npm package](https://img.shields.io/npm/v/npmtest-redux-promise.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-redux-promise) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-redux-promise.svg)](https://travis-ci.org/npmtest/node-npmtest-redux-promise)

#### FSA-compliant promise middleware for Redux.

[![NPM](https://nodei.co/npm/redux-promise.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redux-promise)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-redux-promise/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-promise/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-redux-promise/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-redux-promise/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-redux-promise/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-redux-promise/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-redux-promise/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-redux-promise/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-redux-promise/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-redux-promise/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-redux-promise/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-redux-promise/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-redux-promise/build/test-report.html](https://npmtest.github.io/node-npmtest-redux-promise/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-redux-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-redux-promise/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-redux-promise/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redux-promise/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-promise/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-redux-promise/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-redux-promise/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrew Clark"
    },
    "bugs": {
        "url": "https://github.com/acdlite/redux-promise/issues"
    },
    "dependencies": {
        "flux-standard-action": "^0.6.1"
    },
    "description": "FSA-compliant promise middleware for Redux.",
    "devDependencies": {
        "babel": "^5.6.14",
        "babel-core": "^5.6.15",
        "babel-eslint": "^5.0.0",
        "chai": "^3.0.0",
        "chai-as-promised": "^5.1.0",
        "eslint": "^0.24.0",
        "eslint-config-airbnb": "0.0.6",
        "mocha": "^2.2.5",
        "sinon": "^1.15.4"
    },
    "directories": {},
    "dist": {
        "shasum": "e97e6c9d3bf376eacb79babe6d906da20112d6d8",
        "tarball": "https://registry.npmjs.org/redux-promise/-/redux-promise-0.5.3.tgz"
    },
    "gitHead": "d2338adac128436a623e3e40a6624074d8d01a52",
    "homepage": "https://github.com/acdlite/redux-promise",
    "keywords": [
        "redux",
        "promise",
        "middleware",
        "redux-middleware",
        "fsa",
        "flux"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "acdlite"
        }
    ],
    "name": "redux-promise",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/acdlite/redux-promise.git"
    },
    "scripts": {
        "prepublish": "make clean build",
        "test": "make test"
    },
    "version": "0.5.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
