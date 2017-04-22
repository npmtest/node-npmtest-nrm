# npmtest-nrm

#### basic test coverage for  [nrm (v1.0.2)](https://github.com/Pana/nrm)  [![npm package](https://img.shields.io/npm/v/npmtest-nrm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nrm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nrm.svg)](https://travis-ci.org/npmtest/node-npmtest-nrm)

#### NPM registry manager can help you easy and fast switch between different npm registries, now include: cnpm, taobao, nj(nodejitsu), rednpm, edunpm

[![NPM](https://nodei.co/npm/nrm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nrm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nrm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nrm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nrm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nrm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nrm/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nrm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nrm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nrm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nrm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nrm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nrm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nrm/build/test-report.html](https://npmtest.github.io/node-npmtest-nrm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nrm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nrm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nrm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nrm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nrm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nrm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nrm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nrm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nrm",
    "version": "1.0.2",
    "description": "NPM registry manager can help you easy and fast switch between different npm registries, now include: cnpm, taobao, nj(nodejitsu), rednpm, edunpm",
    "bin": "./cli.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/Pana/nrm.git"
    },
    "scripts": {
        "star": "npm star nrm"
    },
    "keywords": [
        "NPM",
        "registry"
    ],
    "author": "Pana",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/Pana/nrm/issues"
    },
    "homepage": "https://github.com/Pana/nrm",
    "dependencies": {
        "async": "^1.5.2",
        "commander": "^2.9.0",
        "extend": "^3.0.0",
        "ini": "^1.1.0",
        "node-echo": "^0.1.1",
        "npm": "^3.10.3",
        "only": "0.0.2",
        "open": "0.0.5",
        "request": "^2.72.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
