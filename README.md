# npmtest-jest-cli

#### basic test coverage for  [jest-cli (v19.0.2)](http://facebook.github.io/jest/)  [![npm package](https://img.shields.io/npm/v/npmtest-jest-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jest-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jest-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-jest-cli)

#### Painless JavaScript Testing.

[![NPM](https://nodei.co/npm/jest-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jest-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jest-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jest-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jest-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jest-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jest-cli/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-jest-cli/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-jest-cli/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jest-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jest-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jest-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jest-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jest-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jest-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jest-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-jest-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jest-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jest-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jest-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jest-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jest-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jest-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jest-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jest-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "jest": "./bin/jest.js"
    },
    "bugs": {
        "url": "https://github.com/facebook/jest/issues"
    },
    "dependencies": {
        "ansi-escapes": "^1.4.0",
        "callsites": "^2.0.0",
        "chalk": "^1.1.1",
        "graceful-fs": "^4.1.6",
        "is-ci": "^1.0.9",
        "istanbul-api": "^1.1.0-alpha.1",
        "istanbul-lib-coverage": "^1.0.0",
        "istanbul-lib-instrument": "^1.1.1",
        "jest-changed-files": "^19.0.2",
        "jest-config": "^19.0.2",
        "jest-environment-jsdom": "^19.0.2",
        "jest-haste-map": "^19.0.0",
        "jest-jasmine2": "^19.0.2",
        "jest-message-util": "^19.0.0",
        "jest-regex-util": "^19.0.0",
        "jest-resolve-dependencies": "^19.0.0",
        "jest-runtime": "^19.0.2",
        "jest-snapshot": "^19.0.2",
        "jest-util": "^19.0.2",
        "micromatch": "^2.3.11",
        "node-notifier": "^5.0.1",
        "slash": "^1.0.0",
        "string-length": "^1.0.1",
        "throat": "^3.0.0",
        "which": "^1.1.1",
        "worker-farm": "^1.3.1",
        "yargs": "^6.3.0"
    },
    "description": "Painless JavaScript Testing.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "cc3620b62acac5f2d93a548cb6ef697d4ec85443",
        "tarball": "https://registry.npmjs.org/jest-cli/-/jest-cli-19.0.2.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "homepage": "http://facebook.github.io/jest/",
    "keywords": [
        "ava",
        "babel",
        "coverage",
        "easy",
        "expect",
        "facebook",
        "immersive",
        "instant",
        "jasmine",
        "jest",
        "jsdom",
        "mocha",
        "mocking",
        "painless",
        "qunit",
        "runner",
        "sandboxed",
        "snapshot",
        "tap",
        "tape",
        "test",
        "testing",
        "typescript",
        "watch"
    ],
    "license": "BSD-3-Clause",
    "main": "build/jest.js",
    "maintainers": [
        {
            "name": "cpojer"
        },
        {
            "name": "dmitriiabramov"
        },
        {
            "name": "fb"
        },
        {
            "name": "gaearon"
        },
        {
            "name": "jeffmo"
        },
        {
            "name": "kentaromiura"
        },
        {
            "name": "zpao"
        }
    ],
    "name": "jest-cli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/facebook/jest.git"
    },
    "scripts": {},
    "version": "19.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
