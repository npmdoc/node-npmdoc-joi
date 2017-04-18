# npmdoc-joi

#### api documentation for  [joi (v10.4.1)](https://github.com/hapijs/joi)  [![npm package](https://img.shields.io/npm/v/npmdoc-joi.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-joi) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-joi.svg)](https://travis-ci.org/npmdoc/node-npmdoc-joi)

#### Object schema validation

[![NPM](https://nodei.co/npm/joi.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/joi)

- [https://npmdoc.github.io/node-npmdoc-joi/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-joi/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-joi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-joi/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-joi/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-joi/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/hapijs/joi/issues"
    },
    "dependencies": {
        "hoek": "4.x.x",
        "isemail": "2.x.x",
        "items": "2.x.x",
        "topo": "2.x.x"
    },
    "description": "Object schema validation",
    "devDependencies": {
        "code": "4.x.x",
        "hapitoc": "1.x.x",
        "lab": "13.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "a2fca1f0d603d1b843f2c1e086b52461f6be1f36",
        "tarball": "https://registry.npmjs.org/joi/-/joi-10.4.1.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "16b8c140fec6fc8e44caed9a9e533a76e49f5968",
    "homepage": "https://github.com/hapijs/joi",
    "keywords": [
        "hapi",
        "schema",
        "validation"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        },
        {
            "name": "marsup"
        },
        {
            "name": "nlf"
        },
        {
            "name": "wyatt"
        }
    ],
    "name": "joi",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/joi.git"
    },
    "scripts": {
        "test": "lab -t 100 -a code -L",
        "test-cov-html": "lab -r html -o coverage.html -a code",
        "test-debug": "lab -a code",
        "toc": "hapitoc",
        "version": "npm run toc && git add API.md README.md"
    },
    "version": "10.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
