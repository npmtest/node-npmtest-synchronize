# npmtest-synchronize

#### basic test coverage for  [synchronize (v2.0.0)](http://alexeypetrushin.github.com/synchronize)  [![npm package](https://img.shields.io/npm/v/npmtest-synchronize.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-synchronize) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-synchronize.svg)](https://travis-ci.org/npmtest/node-npmtest-synchronize)

#### Turns asynchronous function into synchronous

[![NPM](https://nodei.co/npm/synchronize.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/synchronize)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-synchronize/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-synchronize/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-synchronize/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-synchronize/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-synchronize/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-synchronize/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-synchronize/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-synchronize/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-synchronize/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-synchronize/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-synchronize/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-synchronize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-synchronize/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-synchronize/build/test-report.html](https://npmtest.github.io/node-npmtest-synchronize/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-synchronize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-synchronize/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-synchronize/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-synchronize/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-synchronize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-synchronize/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-synchronize/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-synchronize/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alexey Petrushin",
        "url": "http://petrush.in"
    },
    "bugs": {
        "url": "https://github.com/alexeypetrushin/synchronize/issues"
    },
    "dependencies": {
        "fibers": "1.0.x"
    },
    "description": "Turns asynchronous function into synchronous",
    "devDependencies": {
        "chai": "1.3.x",
        "mocha": "1.0.x"
    },
    "directories": {},
    "dist": {
        "shasum": "b5eb89964c4bad6e42caa4143cad26cef1edf422",
        "tarball": "https://registry.npmjs.org/synchronize/-/synchronize-2.0.0.tgz"
    },
    "gitHead": "4b83165d51a29d82d0e8d681175ccccc97ff84b3",
    "homepage": "http://alexeypetrushin.github.com/synchronize",
    "keywords": [
        "Fibers",
        "Sync",
        "Async",
        "Control Flow"
    ],
    "license": "MIT",
    "main": "./sync",
    "maintainers": [
        {
            "name": "alexey.petrushin"
        }
    ],
    "name": "synchronize",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/alexeypetrushin/synchronize.git"
    },
    "scripts": {
        "test": "mocha -R spec test/*.js"
    },
    "version": "2.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
