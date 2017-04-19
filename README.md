# npmtest-generator-node-webkit

#### basic test coverage for  [generator-node-webkit (v1.0.4)](https://github.com/Dica-Developer/generator-node-webkit)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-node-webkit.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-node-webkit) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-node-webkit.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-node-webkit)

#### A generator for node-webkit

[![NPM](https://nodei.co/npm/generator-node-webkit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-node-webkit)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-node-webkit/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-node-webkit/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-node-webkit/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-node-webkit/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-node-webkit/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-node-webkit/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-node-webkit/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-node-webkit/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-node-webkit/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-node-webkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-node-webkit/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-node-webkit/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-node-webkit/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-node-webkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-node-webkit/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-node-webkit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-node-webkit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-node-webkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-node-webkit/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-node-webkit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-node-webkit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dica-Developer",
        "url": "https://github.com/Dica-Developer"
    },
    "bugs": {
        "url": "https://github.com/Dica-Developer/generator-node-webkit/issues"
    },
    "dependencies": {
        "decompress-zip": "^0.1.0",
        "follow-redirects": "^0.0.3",
        "fs-extra": "^0.16.3",
        "github": "^0.2.3",
        "html-wiring": "^1.1.0",
        "lodash": "^3.8.0",
        "request": "^2.53.0",
        "tar-fs": "^1.4.2",
        "temp": ">=0.8.1",
        "when": "^3.7.2",
        "yeoman-generator": "^0.18.7"
    },
    "description": "A generator for node-webkit",
    "devDependencies": {
        "chai": "^1.10.0",
        "coveralls": ">=2.11.2",
        "mocha": "^2.1.0",
        "mocha-lcov-reporter": ">=0.0.1",
        "temp": ">=0.8.1"
    },
    "directories": {},
    "dist": {
        "shasum": "97b5d8620fba87379a87c8789e92b8676000652e",
        "tarball": "https://registry.npmjs.org/generator-node-webkit/-/generator-node-webkit-1.0.4.tgz"
    },
    "engines": {
        "node": ">=0.10.0",
        "npm": ">=1.2.10"
    },
    "gitHead": "be9b3c9b3fb16c9ae516f88f1a6da67ee13bd6fc",
    "homepage": "https://github.com/Dica-Developer/generator-node-webkit",
    "keywords": [
        "yeoman-generator",
        "node-webkit"
    ],
    "license": "MIT",
    "main": "app/index.js",
    "maintainers": [
        {
            "name": "dica-developer"
        }
    ],
    "name": "generator-node-webkit",
    "optionalDependencies": {},
    "peerDependencies": {
        "yo": ">=1.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/Dica-Developer/generator-node-webkit.git"
    },
    "scripts": {
        "test": "mocha test -R mocha-lcov-reporter | coveralls"
    },
    "version": "1.0.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
