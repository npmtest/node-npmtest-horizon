# npmtest-horizon

#### basic test coverage for  [horizon (v2.0.0)](https://github.com/rethinkdb/horizon#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-horizon.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-horizon) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-horizon.svg)](https://travis-ci.org/npmtest/node-npmtest-horizon)

#### An open-source developer platform for building realtime, scalable web apps.

[![NPM](https://nodei.co/npm/horizon.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/horizon)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-horizon/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-horizon/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-horizon/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-horizon/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-horizon/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-horizon/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-horizon/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-horizon/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-horizon/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-horizon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-horizon/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-horizon/build/test-report.html](https://npmtest.github.io/node-npmtest-horizon/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-horizon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-horizon/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-horizon/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-horizon/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-horizon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-horizon/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-horizon/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-horizon/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "RethinkDB"
    },
    "bin": {
        "hz": "src/main.js",
        "horizon": "src/main.js"
    },
    "bugs": {
        "url": "https://github.com/rethinkdb/horizon/issues"
    },
    "dependencies": {
        "@horizon/server": "2.0.0",
        "argparse": "^1.0.3",
        "bluebird": "^3.4.1",
        "chalk": "^1.1.3",
        "hasbin": "^1.2.1",
        "joi": "^8.0.5",
        "jsonwebtoken": "^5.5.4",
        "mime-types": "^2.0.4",
        "open": "0.0.5",
        "rethinkdb": "^2.1.1",
        "toml": "^2.3.0"
    },
    "description": "An open-source developer platform for building realtime, scalable web apps.",
    "devDependencies": {
        "chai": "^3.5.0",
        "eslint": "^2.3.0",
        "istanbul": "^0.4.3",
        "mocha": "2.4.5",
        "mock-fs": "^3.10.0",
        "sinon": "1.17.3",
        "strip-ansi": "^3.0.1",
        "toml": "^2.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "0049b36faeae7779f048d7cc07d0b77b4ca9c3d7",
        "tarball": "https://registry.npmjs.org/horizon/-/horizon-2.0.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0",
        "npm": ">=3.0.0"
    },
    "homepage": "https://github.com/rethinkdb/horizon#readme",
    "license": "MIT",
    "main": "src/main.js",
    "maintainers": [
        {
            "name": "rethinkdb"
        }
    ],
    "name": "horizon",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rethinkdb/horizon.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha test",
        "lint": "eslint src test",
        "test": "mocha test test/unit --timeout 10000"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
