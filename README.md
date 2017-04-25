# npmtest-elastical

#### basic test coverage for  [elastical (v0.0.13)](https://github.com/ramv/node-elastical/)  [![npm package](https://img.shields.io/npm/v/npmtest-elastical.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-elastical) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-elastical.svg)](https://travis-ci.org/npmtest/node-npmtest-elastical)

#### An ElasticSearch client.

[![NPM](https://nodei.co/npm/elastical.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/elastical)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-elastical/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-elastical/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-elastical/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-elastical/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-elastical/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-elastical/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-elastical/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-elastical/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-elastical/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-elastical/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-elastical/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-elastical/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-elastical/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-elastical/build/test-report.html](https://npmtest.github.io/node-npmtest-elastical/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-elastical/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-elastical/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-elastical/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-elastical/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-elastical/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-elastical/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-elastical/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-elastical/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ryan Grove",
        "url": "http://wonko.com/"
    },
    "copyright": "Copyright (c) 2013 Ryan Grove. All rights reserved.",
    "dependencies": {
        "diff": ">=1.0.3",
        "request": ">=2.9.200"
    },
    "description": "An ElasticSearch client.",
    "devDependencies": {
        "vows": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "e3725fc31c92e8d0c2b6bbee56ac91951ad67155",
        "tarball": "https://registry.npmjs.org/elastical/-/elastical-0.0.13.tgz"
    },
    "engines": [
        "node >=0.4.0",
        "npm >=1.0.0"
    ],
    "homepage": "https://github.com/ramv/node-elastical/",
    "keywords": [
        "elasticsearch",
        "elastic",
        "search",
        "client",
        "lucene"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/ramv/node-elastical/blob/master/LICENSE.md"
        }
    ],
    "main": "index",
    "maintainers": [
        {
            "name": "rgrove"
        },
        {
            "name": "rramv"
        }
    ],
    "name": "elastical",
    "optionalDependencies": {},
    "readmeFilename": "README.md",
    "repository": [
        {
            "type": "git",
            "url": "git://github.com/ramv/node-elastical.git"
        }
    ],
    "scripts": {
        "test": "node_modules/.bin/vows tests/offline-tests.js"
    },
    "version": "0.0.13",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
