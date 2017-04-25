# npmtest-react-onclickoutside

#### basic test coverage for  [react-onclickoutside (v5.11.1)](https://github.com/Pomax/react-onclickoutside)  [![npm package](https://img.shields.io/npm/v/npmtest-react-onclickoutside.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-onclickoutside) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-onclickoutside.svg)](https://travis-ci.org/npmtest/node-npmtest-react-onclickoutside)

#### An onClickOutside wrapper for React components

[![NPM](https://nodei.co/npm/react-onclickoutside.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-onclickoutside)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-onclickoutside/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-onclickoutside/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-onclickoutside/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-onclickoutside/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-onclickoutside/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-onclickoutside/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-onclickoutside/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-onclickoutside/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-onclickoutside/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-onclickoutside/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-onclickoutside/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-onclickoutside/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-onclickoutside/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-onclickoutside/build/test-report.html](https://npmtest.github.io/node-npmtest-react-onclickoutside/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-onclickoutside/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-onclickoutside/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-onclickoutside/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-onclickoutside/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-onclickoutside/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-onclickoutside/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-onclickoutside/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-onclickoutside/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Pomax <pomax@nihongoresources.com>"
    ],
    "bugs": {
        "url": "https://github.com/Pomax/react-onclickoutside/issues"
    },
    "dependencies": {
        "create-react-class": "^15.5.x"
    },
    "description": "An onClickOutside wrapper for React components",
    "devDependencies": {
        "babel-preset-es2015": "^6.14.0",
        "chai": "^3.5.0",
        "eslint": "^3.4.0",
        "karma": "^1.4.0",
        "karma-babel-preprocessor": "^6.0.1",
        "karma-chai": "^0.1.0",
        "karma-mocha": "^1.3.0",
        "karma-phantomjs-launcher": "^1.0.0",
        "karma-spec-reporter": "0.0.26",
        "karma-webpack": "^2.0.2",
        "mocha": "^3.2.0",
        "phantomjs-prebuilt": "^2.1.7",
        "react": "^15.5.x",
        "react-addons-test-utils": "^15.5.x",
        "react-dom": "^15.5.x",
        "react-test-renderer": "^15.5.x",
        "require-hijack": "^1.2.1",
        "webpack": "^1.12.14"
    },
    "directories": {},
    "dist": {
        "shasum": "00314e52567cf55faba94cabbacd119619070623",
        "tarball": "https://registry.npmjs.org/react-onclickoutside/-/react-onclickoutside-5.11.1.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "b0cb305fecbff7076b67fce3e84b803744b9fa8e",
    "homepage": "https://github.com/Pomax/react-onclickoutside",
    "keywords": [
        "react",
        "onclick",
        "outside",
        "onclickoutside"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "pomax"
        }
    ],
    "name": "react-onclickoutside",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Pomax/react-onclickoutside.git"
    },
    "scripts": {
        "lint": "eslint index.js ./test",
        "precommit": "npm run lint",
        "test": "npm run lint && karma start test/karma.conf.js --single-run && npm run test:nodom",
        "test:nodom": "mocha test/no-dom-test.js"
    },
    "version": "5.11.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
