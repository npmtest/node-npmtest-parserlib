# npmtest-parserlib

#### test coverage for  [parserlib (v1.1.1)](https://github.com/CSSLint/parser-lib)  [![npm package](https://img.shields.io/npm/v/npmtest-parserlib.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-parserlib) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-parserlib.svg)](https://travis-ci.org/npmtest/node-npmtest-parserlib)

#### CSS3 SAX-inspired parser

[![NPM](https://nodei.co/npm/parserlib.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/parserlib)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-parserlib/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-parserlib/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-parserlib/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-parserlib/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-parserlib/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-parserlib/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-parserlib/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-parserlib/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-parserlib/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-parserlib/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-parserlib/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-parserlib/build/test-report.html](https://npmtest.github.io/node-npmtest-parserlib/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-parserlib/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-parserlib/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-parserlib/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-parserlib/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-parserlib/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-parserlib/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-parserlib/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-parserlib/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicholas C. Zakas"
    },
    "bugs": {
        "url": "https://github.com/CSSLint/parser-lib/issues"
    },
    "contributors": [
        {
            "name": "Nick Schonning"
        }
    ],
    "dependencies": {},
    "description": "CSS3 SAX-inspired parser",
    "devDependencies": {
        "babybird": "0.0.1",
        "browserify": "^13.0.0",
        "concat-stream": "^1.5.1",
        "factor-bundle": "^2.5.0",
        "jshint": "^2.9.1",
        "moment": "^2.11.2",
        "shelljs": "^0.7.5",
        "ytestrunner": "^0.3.3",
        "yuitest": "^0.7.9"
    },
    "directories": {},
    "dist": {
        "shasum": "a64cfa724062434fdfc351c9a4ec2d92b94c06f4",
        "tarball": "https://registry.npmjs.org/parserlib/-/parserlib-1.1.1.tgz"
    },
    "files": [
        "dist",
        "src"
    ],
    "gitHead": "e709784d9f8c8f9e360bcddacc8c4b750376ce9f",
    "homepage": "https://github.com/CSSLint/parser-lib",
    "keywords": [
        "parser",
        "css",
        "css3",
        "sax",
        "style",
        "stylesheet"
    ],
    "license": "MIT",
    "main": "./src/index.js",
    "maintainers": [
        {
            "name": "cscott"
        },
        {
            "name": "nschonni"
        },
        {
            "name": "nzakas"
        },
        {
            "name": "stubbornella"
        },
        {
            "name": "xhmikosr"
        }
    ],
    "name": "parserlib",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/CSSLint/parser-lib.git"
    },
    "scripts": {
        "build": "node scripts/build.js",
        "coverage": "ytestrunner -c",
        "lint": "jshint scripts src tests",
        "prepublish": "npm test",
        "pretest": "npm run lint",
        "test": "npm run lint && npm run test-yuitest",
        "test-yuitest": "ytestrunner"
    },
    "version": "1.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
