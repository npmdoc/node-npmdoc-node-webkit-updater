# npmdoc-node-webkit-updater

#### api documentation for  [node-webkit-updater (v0.3.3)](https://github.com/edjafarov/node-webkit-updater)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-webkit-updater.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-webkit-updater) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-webkit-updater.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-webkit-updater)

#### node-webkit autoupdate library

[![NPM](https://nodei.co/npm/node-webkit-updater.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-webkit-updater)

- [https://npmdoc.github.io/node-npmdoc-node-webkit-updater/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-webkit-updater/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-webkit-updater/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-webkit-updater/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-webkit-updater/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-webkit-updater/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eldar Djafarov"
    },
    "bugs": {
        "url": "https://github.com/edjafarov/node-webkit-updater/issues"
    },
    "contributors": [
        {
            "name": "Eldar Djafarov"
        },
        {
            "name": "Adam Lynch"
        }
    ],
    "dependencies": {
        "del": "~0.1.2",
        "ncp": "2.0.0",
        "request": "~2.64.0",
        "semver": "^5.0.3",
        "tar.gz": "^0.1.1"
    },
    "description": "node-webkit autoupdate library",
    "devDependencies": {
        "chai": "^1.9.1",
        "express": "^4.3.1",
        "get-port": "^0.1.0",
        "grunt": "~0.4.5",
        "grunt-cli": "~0.1.13",
        "grunt-contrib-clean": "^0.5.0",
        "grunt-contrib-compress": "^0.9.1",
        "grunt-contrib-copy": "^0.5.0",
        "grunt-jsdoc-to-markdown": "~0.4.1",
        "grunt-mocha-test": "^0.10.2",
        "grunt-node-webkit-builder": "~0.2.2",
        "mocha": "^1.19.0"
    },
    "directories": {},
    "dist": {
        "shasum": "218579c225123b8289597b1e3468ab6e8a789888",
        "tarball": "https://registry.npmjs.org/node-webkit-updater/-/node-webkit-updater-0.3.3.tgz"
    },
    "gitHead": "9a99b8406f33f49f84c9c34855b49491be3c5e83",
    "homepage": "https://github.com/edjafarov/node-webkit-updater",
    "keywords": [
        "node-webkit",
        "update",
        "autoupdate"
    ],
    "main": "./app/updater.js",
    "maintainers": [
        {
            "name": "edjafarov"
        },
        {
            "name": "adam-lynch"
        }
    ],
    "name": "node-webkit-updater",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/edjafarov/node-webkit-updater.git"
    },
    "scripts": {
        "deps": "npm i && cd app && npm i && cd ..",
        "test": "node node_modules/grunt-cli/bin/grunt clean mochaTest"
    },
    "version": "0.3.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
