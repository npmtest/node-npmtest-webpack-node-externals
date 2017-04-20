# npmtest-webpack-node-externals

#### basic test coverage for  [webpack-node-externals (v1.5.4)](https://github.com/liady/webpack-node-externals)  [![npm package](https://img.shields.io/npm/v/npmtest-webpack-node-externals.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webpack-node-externals) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webpack-node-externals.svg)](https://travis-ci.org/npmtest/node-npmtest-webpack-node-externals)

#### Easily exclude node_modules in Webpack bundle

[![NPM](https://nodei.co/npm/webpack-node-externals.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webpack-node-externals)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webpack-node-externals/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-node-externals/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-node-externals/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webpack-node-externals/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-node-externals/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webpack-node-externals/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webpack-node-externals/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-webpack-node-externals/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-webpack-node-externals/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-node-externals/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-webpack-node-externals/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-webpack-node-externals/build/test-report.html](https://npmtest.github.io/node-npmtest-webpack-node-externals/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-webpack-node-externals/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webpack-node-externals/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-webpack-node-externals/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webpack-node-externals/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webpack-node-externals/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webpack-node-externals/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-webpack-node-externals/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-webpack-node-externals/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "webpack-node-externals",
    "version": "1.5.4",
    "description": "Easily exclude node_modules in Webpack bundle",
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/liady/webpack-node-externals.git"
    },
    "dependencies": {},
    "devDependencies": {
        "chai": "^3.5.0",
        "mocha": "^2.5.3",
        "mock-fs": "3.10.0",
        "ncp": "^2.0.0",
        "webpack": "^1.13.1"
    },
    "scripts": {
        "unit": "mocha --colors ./test/*.spec.js",
        "unit-watch": "mocha --colors -w ./test/*.spec.js",
        "test": "npm run unit-watch"
    },
    "keywords": [
        "webpack",
        "node_modules",
        "node",
        "bundle",
        "externals"
    ],
    "author": {
        "name": "Liad Yosef",
        "url": "https://github.com/liady"
    },
    "files": [
        "LICENSE",
        "README.md",
        "index.js"
    ],
    "bugs": {
        "url": "https://github.com/liady/webpack-node-externals/issues"
    },
    "homepage": "https://github.com/liady/webpack-node-externals",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
