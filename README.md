# npmtest-node-polyglot

#### test coverage for  [node-polyglot (v2.2.2)](https://github.com/airbnb/polyglot.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-node-polyglot.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-polyglot) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-polyglot.svg)](https://travis-ci.org/npmtest/node-npmtest-node-polyglot)

#### Give your JavaScript the ability to speak many languages.

[![NPM](https://nodei.co/npm/node-polyglot.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-polyglot)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-polyglot/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-polyglot/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-polyglot/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-polyglot/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-polyglot/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-polyglot/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-polyglot/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-polyglot/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-polyglot/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-polyglot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-polyglot/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-polyglot/build/test-report.html](https://npmtest.github.io/node-npmtest-node-polyglot/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-polyglot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-polyglot/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-polyglot/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-polyglot/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-polyglot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-polyglot/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-polyglot/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-polyglot/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Spike Brehm"
    },
    "bugs": {
        "url": "https://github.com/airbnb/polyglot.js/issues"
    },
    "dependencies": {
        "for-each": "^0.3.2",
        "has": "^1.0.1",
        "string.prototype.trim": "^1.1.2",
        "warning": "^3.0.0"
    },
    "description": "Give your JavaScript the ability to speak many languages.",
    "devDependencies": {
        "chai": "^3.5.0",
        "docco": "^0.7.0",
        "eslint": "^3.12.2",
        "eslint-config-airbnb-base": "^10.0.1",
        "eslint-plugin-import": "^2.2.0",
        "mocha": "^3.2.0",
        "safe-publish-latest": "^1.1.1",
        "should": "^11.1.2",
        "uglify-js": "2.7.3"
    },
    "directories": {},
    "dist": {
        "shasum": "1a3f76d7392f836ea0823836ede817e6ea6ec26c",
        "tarball": "https://registry.npmjs.org/node-polyglot/-/node-polyglot-2.2.2.tgz"
    },
    "gitHead": "bcd829f8b0a5a70846f790ac2f3c73da3feb8fef",
    "homepage": "https://github.com/airbnb/polyglot.js#readme",
    "keywords": [
        "i18n",
        "internationalization",
        "internationalisation",
        "translation",
        "interpolation",
        "translate",
        "polyglot"
    ],
    "license": "BSD-2-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "airbnb"
        },
        {
            "name": "ljharb"
        },
        {
            "name": "spikebrehm"
        }
    ],
    "name": "node-polyglot",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/airbnb/polyglot.js.git"
    },
    "scripts": {
        "docs": "docco -o docs/ index.js",
        "lint": "eslint *.js test/*.js",
        "prepublish": "safe-publish-latest",
        "pretest": "npm run --silent lint",
        "test": "npm run --silent tests-only",
        "tests-only": "mocha test/*.js --reporter spec"
    },
    "version": "2.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
