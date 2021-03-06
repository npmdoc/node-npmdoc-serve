# npmdoc-serve

#### basic api documentation for  [serve (v5.1.4)](https://github.com/zeit/serve#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-serve.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-serve) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-serve.svg)](https://travis-ci.org/npmdoc/node-npmdoc-serve)

#### Static file serving and directory listing

[![NPM](https://nodei.co/npm/serve.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/serve)

- [https://npmdoc.github.io/node-npmdoc-serve/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-serve/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-serve/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-serve/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-serve/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-serve/build/screenCapture.npmPackageDependencyTree.svg)



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
        "args": "2.6.0",
        "basic-auth": "1.1.0",
        "bluebird": "3.5.0",
        "boxen": "1.0.0",
        "chalk": "1.1.3",
        "clipboardy": "1.1.0",
        "dargs": "5.1.0",
        "detect-port": "1.1.1",
        "filesize": "3.5.6",
        "fs-promise": "2.0.2",
        "handlebars": "4.0.6",
        "ip": "1.1.5",
        "micro": "7.3.2",
        "micro-compress": "1.0.0",
        "mime-types": "2.1.15",
        "node-version": "1.0.0",
        "path-type": "2.0.0",
        "send": "0.15.1",
        "update-notifier": "2.1.0"
    },
    "description": "Static file serving and directory listing",
    "devDependencies": {
        "eslint-config-prettier": "1.6.0",
        "husky": "0.13.3",
        "lint-staged": "3.4.0",
        "prettier": "0.22.0",
        "xo": "0.19.0"
    },
    "directories": {},
    "dist": {
        "shasum": "acbb5a96fbce87a1add9b911a9dc8cd5b172c600",
        "tarball": "https://registry.npmjs.org/serve/-/serve-5.1.4.tgz"
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
    "gitHead": "bba207e19393b69fbaa71a6bdc6c212acf2c47ee",
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
            "name": "leo"
        },
        {
            "name": "rauchg"
        }
    ],
    "name": "serve",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zeit/serve.git"
    },
    "scripts": {
        "precommit": "lint-staged",
        "test": "xo"
    },
    "version": "5.1.4",
    "xo": {
        "extends": "prettier"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
