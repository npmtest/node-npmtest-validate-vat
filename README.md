# npmtest-validate-vat

#### basic test coverage for  validate-vat (v0.5.0)  [![npm package](https://img.shields.io/npm/v/npmtest-validate-vat.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-validate-vat) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-validate-vat.svg)](https://travis-ci.org/npmtest/node-npmtest-validate-vat)

#### A Europe VAT number validation lib

[![NPM](https://nodei.co/npm/validate-vat.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/validate-vat)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-validate-vat/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-validate-vat/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-validate-vat/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-validate-vat/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-validate-vat/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-validate-vat/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-validate-vat/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-validate-vat/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-validate-vat/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-validate-vat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-validate-vat/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-validate-vat/build/test-report.html](https://npmtest.github.io/node-npmtest-validate-vat/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-validate-vat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-validate-vat/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-validate-vat/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-validate-vat/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-validate-vat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-validate-vat/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-validate-vat/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-validate-vat/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "validate-vat",
    "version": "0.5.0",
    "description": "A Europe VAT number validation lib",
    "main": "lib/index.js",
    "dependencies": {},
    "devDependencies": {
        "coffee-script": "~1.12.2",
        "mocha": "~3.2.0",
        "expect.js": ">=0.2.0"
    },
    "scripts": {
        "test": "mocha --compilers coffee:coffee-script/register -R spec -t 10000 --recursive test",
        "prepublish": "coffee --output lib --compile src"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/viruschidai/validate-vat"
    },
    "keywords": [
        "VAT",
        "VIES",
        "Tax",
        "Number",
        "Validation",
        "node.js"
    ],
    "author": "Bill Gao",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/viruschidai/validate-vat/issues"
    },
    "directories": {
        "test": "test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
