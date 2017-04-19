# npmtest-coverify

#### basic test coverage for  [coverify (v1.4.1)](https://github.com/substack/coverify)  [![npm package](https://img.shields.io/npm/v/npmtest-coverify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-coverify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-coverify.svg)](https://travis-ci.org/npmtest/node-npmtest-coverify)

#### code coverage browserify transform

[![NPM](https://nodei.co/npm/coverify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/coverify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-coverify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-coverify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-coverify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-coverify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-coverify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-coverify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-coverify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-coverify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-coverify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-coverify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-coverify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-coverify/build/test-report.html](https://npmtest.github.io/node-npmtest-coverify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-coverify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-coverify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-coverify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-coverify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-coverify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-coverify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-coverify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-coverify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bin": {
        "coverify": "bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/substack/coverify/issues"
    },
    "dependencies": {
        "convert-source-map": "^1.1.0",
        "falafel": "^1.0.1",
        "minimist": "^1.1.1",
        "slash": "^1.0.0",
        "source-map": "~0.4.2",
        "split2": "^0.2.1",
        "stream-combiner2": "^1.0.2",
        "through2": "~0.6.5"
    },
    "description": "code coverage browserify transform",
    "devDependencies": {
        "browserify": "^10.0.0",
        "tape": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b3e4b07ec1ce209c0eac99a58aabdf67d8b62726",
        "tarball": "https://registry.npmjs.org/coverify/-/coverify-1.4.1.tgz"
    },
    "gitHead": "14345744d4fe56be89cca88c0700249ea17263ff",
    "homepage": "https://github.com/substack/coverify",
    "keywords": [
        "code",
        "coverage",
        "browserify",
        "browserify-transform",
        "test"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "substack"
        },
        {
            "name": "chromakode"
        }
    ],
    "name": "coverify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/coverify.git"
    },
    "scripts": {
        "test": "test/run.sh"
    },
    "testling": {
        "files": "test/ok.js",
        "browsers": [
            "ie/8..latest",
            "firefox/3.5",
            "firefox/latest",
            "firefox/nightly",
            "chrome/10",
            "chrome/latest",
            "chrome/canary",
            "opera/12..latest",
            "opera/next",
            "safari/5.1..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest",
            "android-browser/4.2..latest"
        ]
    },
    "version": "1.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
