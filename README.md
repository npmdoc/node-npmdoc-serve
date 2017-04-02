# api documentation for  [serve (v5.1.2)](https://github.com/zeit/serve#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-serve.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-serve) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-serve.svg)](https://travis-ci.org/npmdoc/node-npmdoc-serve)
#### Static file serving and directory listing

[![NPM](https://nodei.co/npm/serve.png?downloads=true)](https://www.npmjs.com/package/serve)

[![apidoc](https://npmdoc.github.io/node-npmdoc-serve/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-serve_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-serve/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-serve/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "leo"
    },
    "bin": {
        "serve": "./bin/serve.js"
    },
    "bugs": {
        "url": "https://github.com/zeit/serve/issues"
    },
    "dependencies": {
        "args": "2.4.1",
        "basic-auth": "1.1.0",
        "bluebird": "3.5.0",
        "boxen": "1.0.0",
        "chalk": "1.1.3",
        "clipboardy": "1.0.2",
        "dargs": "5.1.0",
        "detect-port": "1.1.1",
        "filesize": "3.5.6",
        "fs-promise": "2.0.2",
        "handlebars": "4.0.6",
        "ip": "1.1.5",
        "micro": "7.3.0",
        "micro-compress": "1.0.0",
        "mime-types": "2.1.15",
        "node-version": "1.0.0",
        "path-type": "2.0.0",
        "send": "0.15.1",
        "update-notifier": "2.1.0"
    },
    "description": "Static file serving and directory listing",
    "devDependencies": {
        "eslint-config-prettier": "1.5.0",
        "husky": "0.13.3",
        "lint-staged": "3.4.0",
        "prettier": "0.22.0",
        "xo": "0.19.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d8ed66f54e037184dd413a5b99761674860d7e08",
        "tarball": "https://registry.npmjs.org/serve/-/serve-5.1.2.tgz"
    },
    "engines": {
        "node": ">=6.9.0"
    },
    "files": [
        "bin",
        "lib",
        "assets",
        "views"
    ],
    "gitHead": "f000282878377041cbc46e9ff7b9acc21f61b2b0",
    "homepage": "https://github.com/zeit/serve#readme",
    "keywords": [
        "now",
        "serve",
        "micro",
        "http-server"
    ],
    "license": "MIT",
    "lint-staged": {
        "*.js": [
            "npm run test",
            "prettier --single-quote --write",
            "git add"
        ]
    },
    "main": "./lib/api.js",
    "maintainers": [
        {
            "name": "leo",
            "email": "leo@zeit.co"
        },
        {
            "name": "rauchg",
            "email": "rauchg@gmail.com"
        }
    ],
    "name": "serve",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zeit/serve.git"
    },
    "scripts": {
        "precommit": "lint-staged",
        "test": "xo"
    },
    "version": "5.1.2",
    "xo": {
        "extends": "prettier"
    }
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module serve](#apidoc.module.serve)



# <a name="apidoc.module.serve"></a>[module serve](#apidoc.module.serve)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
