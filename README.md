# npmtest-gulp-strip-comments

#### basic test coverage for  [gulp-strip-comments (v2.4.5)](https://github.com/RnbWd/gulp-strip-comments)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-strip-comments.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-strip-comments) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-strip-comments.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-strip-comments)

#### Strip comments from code

[![NPM](https://nodei.co/npm/gulp-strip-comments.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-strip-comments)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-strip-comments/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-strip-comments/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-strip-comments/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-strip-comments/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-strip-comments/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-strip-comments/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-strip-comments/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-strip-comments/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-strip-comments/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-strip-comments/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-strip-comments/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-strip-comments/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-strip-comments/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-strip-comments/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-strip-comments/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-strip-comments/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-strip-comments/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-strip-comments/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-strip-comments/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-strip-comments/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-strip-comments/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-strip-comments",
    "description": "Strip comments from code",
    "version": "2.4.5",
    "authors": [
        "David Wisner <dwisner6@gmail.com>",
        "Vitaly Tomilov <vitaly.tomilov@gmail.com>"
    ],
    "bugs": {
        "url": "https://github.com/RnbWd/gulp-strip-comments/issues"
    },
    "dependencies": {
        "decomment": "^0.8.7",
        "gulp-util": "^3.0.8",
        "through2": "^2.0.1"
    },
    "devDependencies": {
        "coveralls": "^2.11.9",
        "istanbul": "^0.4.3",
        "jasmine-node": "^1.14.5"
    },
    "files": [
        "index.js"
    ],
    "homepage": "https://github.com/RnbWd/gulp-strip-comments",
    "keywords": [
        "strip comments",
        "gulpplugin",
        "strip",
        "gulp",
        "comment",
        "decomment",
        "remove",
        "clean",
        "stream",
        "minimize",
        "reduce",
        "remove",
        "comments"
    ],
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/RnbWd/gulp-strip-comments"
    },
    "scripts": {
        "test": "jasmine-node test",
        "coverage": "istanbul cover ./node_modules/jasmine-node/bin/jasmine-node test",
        "travis": "istanbul cover ./node_modules/jasmine-node/bin/jasmine-node test --captureExceptions && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
