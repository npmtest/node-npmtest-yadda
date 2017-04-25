# npmtest-yadda

#### basic test coverage for  [yadda (v1.3.0)](http://acuminous.gitbooks.io/yadda-user-guide)  [![npm package](https://img.shields.io/npm/v/npmtest-yadda.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-yadda) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-yadda.svg)](https://travis-ci.org/npmtest/node-npmtest-yadda)

#### A true BDD framework for JavaScript

[![NPM](https://nodei.co/npm/yadda.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yadda)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-yadda/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-yadda/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-yadda/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-yadda/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-yadda/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-yadda/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-yadda/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-yadda/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-yadda/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-yadda/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-yadda/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-yadda/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-yadda/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-yadda/build/test-report.html](https://npmtest.github.io/node-npmtest-yadda/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-yadda/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-yadda/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-yadda/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yadda/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yadda/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yadda/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-yadda/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-yadda/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stephen Cresswell"
    },
    "bugs": {
        "url": "https://github.com/acuminous/yadda/issues"
    },
    "dependencies": {},
    "description": "A true BDD framework for JavaScript",
    "devDependencies": {
        "browserify": "10.2.6",
        "codeclimate-test-reporter": "^0.4.0",
        "eslint": "^3.12.2",
        "eslint-config-imperative": "^1.0.0",
        "eslint-plugin-imperative": "^1.0.0",
        "husky": "^0.13.0",
        "istanbul": "^0.4.5",
        "karma": "^0.13.22",
        "karma-browserify": "^5.0.2",
        "karma-mocha": "^0.2.2",
        "karma-phantomjs-launcher": "^1.0.0",
        "mocha": "^3.2.0",
        "phantomjs-prebuilt": "^2.1.5",
        "watchify": "^3.7.0"
    },
    "directories": {
        "example": "examples",
        "test": "test"
    },
    "dist": {
        "shasum": "cfd6eb04804a7373a0e9ac52ab09d3d52d3d4e6a",
        "tarball": "https://registry.npmjs.org/yadda/-/yadda-1.3.0.tgz"
    },
    "gitHead": "9da7c89c15f4d0cbc0b626cb2800c11ba53b90d3",
    "homepage": "http://acuminous.gitbooks.io/yadda-user-guide",
    "keywords": [
        "BDD",
        "Specification",
        "Natural",
        "Test",
        "Behaviour",
        "Driven",
        "Jasmine",
        "Mocha",
        "QUnit",
        "Nodeunit"
    ],
    "license": "Apache-2.0",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "cressie176"
        }
    ],
    "name": "yadda",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/acuminous/yadda.git"
    },
    "scripts": {
        "browserify": "node bin/browserify.js",
        "codeclimate": "codeclimate-test-reporter < coverage/lcov.info",
        "examples": "node bin/examples.js",
        "istanbul": "istanbul cover -x 'lib/plugins/**' -x 'lib/shims/**' -x 'lib/Platform.js' _mocha --report lcov --report html",
        "jshint": "jshint .",
        "karma": "karma start karma.conf.js",
        "lint": "eslint .",
        "prepush": "npm run lint && npm test",
        "test": "mocha"
    },
    "version": "1.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
