# npmtest-mongodb-backup

#### basic test coverage for  [mongodb-backup (v1.6.9)](https://github.com/hex7c0/mongodb-backup)  [![npm package](https://img.shields.io/npm/v/npmtest-mongodb-backup.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mongodb-backup) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mongodb-backup.svg)](https://travis-ci.org/npmtest/node-npmtest-mongodb-backup)

#### backup for mongodb

[![NPM](https://nodei.co/npm/mongodb-backup.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mongodb-backup)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mongodb-backup/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongodb-backup/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mongodb-backup/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mongodb-backup/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mongodb-backup/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mongodb-backup/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mongodb-backup/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mongodb-backup/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mongodb-backup/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongodb-backup/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mongodb-backup/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mongodb-backup/build/test-report.html](https://npmtest.github.io/node-npmtest-mongodb-backup/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mongodb-backup/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mongodb-backup/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mongodb-backup/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mongodb-backup/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mongodb-backup/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mongodb-backup/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mongodb-backup/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mongodb-backup/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "hex7c0",
        "url": "https://hex7c0.github.io/"
    },
    "bugs": {
        "url": "https://github.com/hex7c0/mongodb-backup/issues"
    },
    "dependencies": {
        "bson": "1.0.1",
        "fstream": "1.0.10",
        "graceful-fs": "4.1.11",
        "logger-request": "3.7.3",
        "mongodb": "2.2.16",
        "tar": "2.2.1"
    },
    "description": "backup for mongodb",
    "devDependencies": {
        "grunt": "~1.0",
        "grunt-contrib-jshint": "~1.1",
        "grunt-contrib-uglify": "~2.0",
        "grunt-endline": "~0.6",
        "grunt-safer-regex": "~0.0",
        "istanbul": "~0.4",
        "mocha": "~3.2",
        "mongodb-restore": "~1.6",
        "supertest": "~2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "16cd626de1a8b0d332b266530bc45cf565a7a0e8",
        "tarball": "https://registry.npmjs.org/mongodb-backup/-/mongodb-backup-1.6.9.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "630c7b166e53fc4f32b0981f3770d3d02af0818b",
    "homepage": "https://github.com/hex7c0/mongodb-backup",
    "keywords": [
        "mongodb",
        "backup",
        "dump"
    ],
    "license": "Apache-2.0",
    "main": "index.min.js",
    "maintainers": [
        {
            "name": "hex7c0"
        }
    ],
    "name": "mongodb-backup",
    "optionalDependencies": {},
    "preferGlobal": false,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hex7c0/mongodb-backup.git"
    },
    "scripts": {
        "prepublish": "npm prune",
        "test": "mocha --bail --check-leaks --globals Promise --timeout 10000",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --timeout 10000"
    },
    "version": "1.6.9",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
