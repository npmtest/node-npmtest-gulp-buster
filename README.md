# npmtest-gulp-buster

#### basic test coverage for  [gulp-buster (v1.1.0)](https://github.com/UltCombo/gulp-buster)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-buster.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-buster) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-buster.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-buster)

#### Cache buster hashes generator for gulp. Blazing fast and fully configurable.

[![NPM](https://nodei.co/npm/gulp-buster.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-buster)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-buster/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-buster/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-buster/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-buster/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-buster/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-buster/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-buster/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-buster/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-buster/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-buster/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-buster/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-buster/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-buster/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-buster/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-buster/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-buster/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-buster/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-buster/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-buster/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-buster/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-buster/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ult Combo"
    },
    "bugs": {
        "url": "https://github.com/UltCombo/gulp-buster/issues"
    },
    "dependencies": {
        "bluebird": "^3.3.5",
        "gulp-util": "^3.0.7",
        "lodash.defaults": "^4.0.1",
        "object-assign": "^4.0.1",
        "through": "^2.3.8"
    },
    "description": "Cache buster hashes generator for gulp. Blazing fast and fully configurable.",
    "devDependencies": {
        "istanbul": "^0.4.3",
        "mocha": "^2.4.5",
        "should": "^8.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f58afae8051725fbe86792b2ff95637c38c7de1e",
        "tarball": "https://registry.npmjs.org/gulp-buster/-/gulp-buster-1.1.0.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "gitHead": "86bd6b3340327f6eb19b0e25d7a01faa2dd9a99f",
    "homepage": "https://github.com/UltCombo/gulp-buster",
    "keywords": [
        "gulpplugin",
        "cachebuster",
        "cache buster",
        "cache",
        "fingerprint",
        "fingerprinting",
        "revision",
        "revisioning",
        "workflow",
        "webdev",
        "web development"
    ],
    "license": "WTFPL",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "ult_combo"
        }
    ],
    "name": "gulp-buster",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/UltCombo/gulp-buster.git"
    },
    "scripts": {
        "test": "mocha",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- -R dot",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly"
    },
    "version": "1.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
