# npmdoc-gulp-assetpaths

#### api documentation for  [gulp-assetpaths (v0.3.0)](https://github.com/qwales1/gulp-assetpaths)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-assetpaths.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-assetpaths) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-assetpaths.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-assetpaths)

#### A Gulp plugin to change asset paths from one environment to another.

[![NPM](https://nodei.co/npm/gulp-assetpaths.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-assetpaths)

- [https://npmdoc.github.io/node-npmdoc-gulp-assetpaths/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-assetpaths/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-assetpaths/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-assetpaths/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-assetpaths/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-assetpaths/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Chris Wales",
        "url": "https://github.com/qwales1"
    },
    "bugs": {
        "url": "https://github.com/qwales1/gulp-assetpaths/issues"
    },
    "dependencies": {
        "gulp-regex-replace": "^0.2.3",
        "gulp-util": "^3.0.7",
        "through2": "^2.0.1"
    },
    "description": "A Gulp plugin to change asset paths from one environment to another.",
    "devDependencies": {
        "event-stream": "^3.3.4",
        "mocha": "^3.0.2",
        "should": "^11.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "906bb2920558766ec9c3dcc03760e5df5557f7b6",
        "tarball": "https://registry.npmjs.org/gulp-assetpaths/-/gulp-assetpaths-0.3.0.tgz"
    },
    "engines": {
        "node": ">=0.8.0",
        "npm": ">=1.2.10"
    },
    "gitHead": "8ec61bdfaea7eb82c669da4b8aad48902c6a816e",
    "homepage": "https://github.com/qwales1/gulp-assetpaths",
    "keywords": [
        "gulpplugin",
        "cdn",
        "images",
        "domains",
        "assets",
        "urls",
        "paths"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "qwales1"
        }
    ],
    "name": "gulp-assetpaths",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/qwales1/gulp-assetpaths.git"
    },
    "scripts": {
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test": "istanbul test _mocha --report html -- test/*.js --reporter spec"
    },
    "version": "0.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
