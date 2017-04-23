# npmdoc-tumblr.js

#### api documentation for  [tumblr.js (v1.1.1)](https://github.com/tumblr/tumblr.js)  [![npm package](https://img.shields.io/npm/v/npmdoc-tumblr.js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-tumblr.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-tumblr.js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-tumblr.js)

#### Official JavaScript client for the Tumblr API

[![NPM](https://nodei.co/npm/tumblr.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tumblr.js)

- [https://npmdoc.github.io/node-npmdoc-tumblr.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tumblr.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tumblr.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tumblr.js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-tumblr.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-tumblr.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tumblr"
    },
    "bugs": {
        "url": "https://github.com/tumblr/tumblr.js/issues"
    },
    "contributors": [
        {
            "name": "Keith McKnight"
        },
        {
            "name": "Bryan Irace"
        },
        {
            "name": "John Crepezzi"
        }
    ],
    "dependencies": {
        "lodash": "^4.14.0",
        "query-string": "^4.2.2",
        "request": "^2.74.0"
    },
    "description": "Official JavaScript client for the Tumblr API",
    "devDependencies": {
        "chai": "^3.5.0",
        "gulp": "^3.9.1",
        "gulp-eslint": "^3.0.1",
        "gulp-istanbul": "^1.0.0",
        "gulp-mocha": "^2.2.0",
        "hotdoc": "^0.7.1",
        "jsdoc": "^3.4.0",
        "json5": "^0.5.0",
        "nock": "^8.0.0",
        "semver": "^5.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a72423e7a08781952d2a45fe4fa35ed15f225c6d",
        "tarball": "https://registry.npmjs.org/tumblr.js/-/tumblr.js-1.1.1.tgz"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "files": [
        "/lib",
        "/LICENSE"
    ],
    "gitHead": "47679a7ab5b17b21bc12d5440d4f5375f0c4d43b",
    "homepage": "https://github.com/tumblr/tumblr.js",
    "keywords": [
        "tumblr",
        "api"
    ],
    "license": "Apache-2.0",
    "main": "./lib/tumblr",
    "maintainers": [
        {
            "name": "seejohnrun"
        },
        {
            "name": "kmck"
        },
        {
            "name": "tumblr"
        },
        {
            "name": "johnnybenson"
        }
    ],
    "name": "tumblr.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tumblr/tumblr.js.git"
    },
    "scripts": {
        "generate-docs": "rm -rf gh-pages && node_modules/.bin/jsdoc -c jsdoc.json",
        "gh-pages": "git subtree push --prefix=gh-pages origin gh-pages",
        "test": "gulp"
    },
    "version": "1.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
