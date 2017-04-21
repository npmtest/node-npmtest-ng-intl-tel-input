# npmtest-ng-intl-tel-input

#### basic test coverage for  [ng-intl-tel-input (v2.0.0)](http://hodgepodgers.github.io/ng-intl-tel-input)  [![npm package](https://img.shields.io/npm/v/npmtest-ng-intl-tel-input.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ng-intl-tel-input) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ng-intl-tel-input.svg)](https://travis-ci.org/npmtest/node-npmtest-ng-intl-tel-input)

#### AngularJS directive implementing intl-tel-input (https://github.com/Bluefieldscom/intl-tel-input)

[![NPM](https://nodei.co/npm/ng-intl-tel-input.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ng-intl-tel-input)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ng-intl-tel-input/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ng-intl-tel-input/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ng-intl-tel-input/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ng-intl-tel-input/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ng-intl-tel-input/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ng-intl-tel-input/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ng-intl-tel-input/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ng-intl-tel-input/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ng-intl-tel-input/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ng-intl-tel-input/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ng-intl-tel-input/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ng-intl-tel-input/build/test-report.html](https://npmtest.github.io/node-npmtest-ng-intl-tel-input/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ng-intl-tel-input/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ng-intl-tel-input/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ng-intl-tel-input/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ng-intl-tel-input/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ng-intl-tel-input/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ng-intl-tel-input/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ng-intl-tel-input/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ng-intl-tel-input/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ng-intl-tel-input",
    "version": "2.0.0",
    "description": "AngularJS directive implementing intl-tel-input (https://github.com/Bluefieldscom/intl-tel-input)",
    "main": "dist/ng-intl-tel-input.js",
    "scripts": {
        "test": "npm run jshint && npm run karma",
        "build": "npm run concat && npm run uglify",
        "start": "nohup http-server",
        "jshint": "jshint .",
        "karma": "karma start karma.conf.js",
        "concat": "node ./node_modules/concat-cli/index.js -f ng-intl-tel-input.{module,provider,directive}.js -o dist/ng-intl-tel-input.js",
        "uglify": "uglify -s dist/ng-intl-tel-input.js -o dist/ng-intl-tel-input.min.js",
        "webdriver-update": "webdriver-manager update",
        "protractor": "protractor protractor.conf.js",
        "mversion": "mversion "
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/hodgepodgers/ng-intl-tel-input.git"
    },
    "keywords": [
        "ng-intl-tel-input",
        "intl-tel-input",
        "international",
        "telephone",
        "validator",
        "angularjs"
    ],
    "author": "bighappyface <anomalous20@gmail.com>",
    "contributors": [
        {
            "name": "SyntaxStacks <johnbobsexipants@gmail.com>"
        }
    ],
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/hodgepodgers/ng-intl-tel-input/issues"
    },
    "homepage": "http://hodgepodgers.github.io/ng-intl-tel-input",
    "devDependencies": {
        "bower": "^1.4.1",
        "chai": "^3.2.0",
        "chai-as-promised": "^5.1.0",
        "concat-cli": "^1.0.1",
        "http-server": "^0.8.0",
        "jasmine-core": "^2.3.4",
        "jshint": "2.8.0",
        "karma": "^0.13.6",
        "karma-chrome-launcher": "^0.2.0",
        "karma-jasmine": "^0.3.6",
        "karma-phantomjs-launcher": "^0.2.1",
        "karma-sinon": "^1.0.4",
        "mocha": "^2.2.5",
        "mversion": "^1.10.0",
        "phantomjs": "^1.9.17",
        "phantomjs-polyfills": "^1.0.1",
        "protractor": "~2.4.0",
        "sinon": "^1.15.4",
        "uglify": "^0.1.5"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
