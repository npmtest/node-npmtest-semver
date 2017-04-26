# npmtest-semver

#### basic test coverage for  [semver (v5.3.0)](https://github.com/npm/node-semver#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-semver.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-semver) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-semver.svg)](https://travis-ci.org/npmtest/node-npmtest-semver)

#### The semantic version parser used by npm.

[![NPM](https://nodei.co/npm/semver.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/semver)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-semver/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-semver/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-semver/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-semver/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-semver/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-semver/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-semver/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-semver/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-semver/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-semver/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-semver/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-semver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-semver/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-semver/build/test-report.html](https://npmtest.github.io/node-npmtest-semver/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-semver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-semver/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-semver/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-semver/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-semver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-semver/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-semver/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-semver/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "semver": "./bin/semver"
    },
    "bugs": {
        "url": "https://github.com/npm/node-semver/issues"
    },
    "dependencies": {},
    "description": "The semantic version parser used by npm.",
    "devDependencies": {
        "tap": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9b2ce5d3de02d17c6012ad326aa6b4d0cf54f94f",
        "tarball": "https://registry.npmjs.org/semver/-/semver-5.3.0.tgz"
    },
    "files": [
        "bin",
        "range.bnf",
        "semver.js"
    ],
    "gitHead": "d21444a0658224b152ce54965d02dbe0856afb84",
    "homepage": "https://github.com/npm/node-semver#readme",
    "license": "ISC",
    "main": "semver.js",
    "maintainers": [
        {
            "name": "isaacs"
        },
        {
            "name": "othiym23"
        }
    ],
    "name": "semver",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/npm/node-semver.git"
    },
    "scripts": {
        "test": "tap test/*.js"
    },
    "version": "5.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
