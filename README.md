# npmtest-blanket

#### basic test coverage for  [blanket (v1.2.3)](https://github.com/alex-seville/blanket)  [![npm package](https://img.shields.io/npm/v/npmtest-blanket.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-blanket) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-blanket.svg)](https://travis-ci.org/npmtest/node-npmtest-blanket)

#### seamless js code coverage

[![NPM](https://nodei.co/npm/blanket.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/blanket)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-blanket/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-blanket/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-blanket/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-blanket/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-blanket/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-blanket/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-blanket/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-blanket/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-blanket/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-blanket/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-blanket/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-blanket/build/test-report.html](https://npmtest.github.io/node-npmtest-blanket/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-blanket/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-blanket/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-blanket/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-blanket/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-blanket/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-blanket/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-blanket/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-blanket/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alex-Seville",
        "url": "http://blanketjs.org"
    },
    "bugs": {
        "url": "https://github.com/alex-seville/blanket/issues"
    },
    "config": {
        "blanket": {
            "pattern": "test",
            "data-cover-flags": {
                "debug": false
            },
            "loader": "./node-loaders/coffee-script",
            "data-cover-reporter-options": {
                "shortnames": true
            }
        },
        "travis-cov": {
            "threshold": 70,
            "removeKey": "branchFcn"
        }
    },
    "dependencies": {
        "acorn": "^1.0.3",
        "falafel": "~1.2.0",
        "foreach": "^2.0.5",
        "isarray": "0.0.1",
        "object-keys": "^1.0.6",
        "xtend": "~4.0.0"
    },
    "description": "seamless js code coverage",
    "devDependencies": {
        "async": "~1.4.0",
        "coffee-react": "^4.0.0",
        "coffee-script": "~1.9.3",
        "grunt": "~0.4.5",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-clean": "~0.6.0",
        "grunt-contrib-concat": "~0.5.1",
        "grunt-contrib-jshint": "~0.11.2",
        "grunt-contrib-uglify": "~0.9.1",
        "load-grunt-tasks": "~3.2.0",
        "mocha": "~2.2.5",
        "phantomjs": "1.9.17",
        "react": "^0.13.3",
        "requirejs": "~2.1.19",
        "travis-cov": "*",
        "uglify-save-license": "~0.4.1"
    },
    "directories": {},
    "dist": {
        "shasum": "151b4987c3bd84552bb5f03b90ef5f7e5931e473",
        "tarball": "https://registry.npmjs.org/blanket/-/blanket-1.2.3.tgz"
    },
    "engines": {
        "node": ">=0.10.7"
    },
    "gitHead": "0155c14cf19bef4df2b175f8173ea467b644a3fe",
    "homepage": "https://github.com/alex-seville/blanket",
    "keywords": [
        "coverage"
    ],
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "alexseville"
        }
    ],
    "name": "blanket",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/alex-seville/blanket.git"
    },
    "scripts": {
        "build": "grunt build",
        "test": "grunt --verbose blanketTest"
    },
    "version": "1.2.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
