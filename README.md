# npmtest-massive

#### basic test coverage for  massive (v2.6.0)  [![npm package](https://img.shields.io/npm/v/npmtest-massive.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-massive) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-massive.svg)](https://travis-ci.org/npmtest/node-npmtest-massive)

#### A small query tool for Postgres that embraces json and makes life simpler

[![NPM](https://nodei.co/npm/massive.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/massive)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-massive/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-massive/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-massive/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-massive/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-massive/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-massive/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-massive/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-massive/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-massive/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-massive/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-massive/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-massive/build/test-report.html](https://npmtest.github.io/node-npmtest-massive/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-massive/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-massive/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-massive/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-massive/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-massive/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-massive/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-massive/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-massive/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "massive",
    "version": "2.6.0",
    "description": "A small query tool for Postgres that embraces json and makes life simpler",
    "main": "index.js",
    "bin": {
        "massive": "bin/massive.js"
    },
    "directories": {
        "example": "example",
        "test": "test"
    },
    "scripts": {
        "test": "mocha",
        "lint": "eslint .",
        "posttest": "npm run lint",
        "coverage": "istanbul cover _mocha -- -R dot"
    },
    "keywords": [
        "postgres",
        "pg",
        "postgresql"
    ],
    "author": "Rob Conery <robconery@gmail.com>",
    "contributors": [
        "Karl Seguin <karl@openmymind.net>",
        "John Atten <xivsolutions@gmail.com>",
        "Dian Fay <dian.m.fay@gmail.com>"
    ],
    "license": "BSD-3-Clause",
    "dependencies": {
        "args-js": "^0.10.12",
        "async": "^2.1.4",
        "commander": "^2.6.0",
        "deasync": "^0.1.1",
        "glob": "^7.0.5",
        "pg": "^6.1.0",
        "pg-query-stream": "^0.7.0",
        "promise-polyfill": "^6.0.2",
        "strip-bom": "^2.0.0",
        "underscore": "^1.8.2"
    },
    "devDependencies": {
        "eslint": "^2.13.1",
        "istanbul": "^0.4.2",
        "mocha": "^2.5.3",
        "sinon": "^1.12.2"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/robconery/massive-js.git"
    },
    "eslintConfig": {
        "extends": "eslint:recommended",
        "env": {
            "node": true,
            "mocha": true
        },
        "rules": {
            "semi": 2
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
