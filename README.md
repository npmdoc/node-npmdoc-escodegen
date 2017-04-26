# npmdoc-escodegen

#### basic api documentation for  [escodegen (v1.8.1)](http://github.com/estools/escodegen)  [![npm package](https://img.shields.io/npm/v/npmdoc-escodegen.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-escodegen) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-escodegen.svg)](https://travis-ci.org/npmdoc/node-npmdoc-escodegen)

#### ECMAScript code generator

[![NPM](https://nodei.co/npm/escodegen.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/escodegen)

- [https://npmdoc.github.io/node-npmdoc-escodegen/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-escodegen/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-escodegen/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-escodegen/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-escodegen/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-escodegen/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "esgenerate": "./bin/esgenerate.js",
        "escodegen": "./bin/escodegen.js"
    },
    "bugs": {
        "url": "https://github.com/estools/escodegen/issues"
    },
    "dependencies": {
        "esprima": "^2.7.1",
        "estraverse": "^1.9.1",
        "esutils": "^2.0.2",
        "optionator": "^0.8.1",
        "source-map": "~0.2.0"
    },
    "description": "ECMAScript code generator",
    "devDependencies": {
        "acorn": "^2.7.0",
        "bluebird": "^2.3.11",
        "bower-registry-client": "^0.2.1",
        "chai": "^1.10.0",
        "commonjs-everywhere": "^0.9.7",
        "gulp": "^3.8.10",
        "gulp-eslint": "^0.2.0",
        "gulp-mocha": "^2.0.0",
        "semver": "^5.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5a5b53af4693110bebb0867aa3430dd3b70a1018",
        "tarball": "https://registry.npmjs.org/escodegen/-/escodegen-1.8.1.tgz"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "files": [
        "LICENSE.BSD",
        "LICENSE.source-map",
        "README.md",
        "bin",
        "escodegen.js",
        "package.json"
    ],
    "gitHead": "ba4faabb224b2d5e0080c8e4f964702b699c7d1f",
    "homepage": "http://github.com/estools/escodegen",
    "license": "BSD-2-Clause",
    "main": "escodegen.js",
    "maintainers": [
        {
            "name": "constellation"
        },
        {
            "name": "michaelficarra"
        }
    ],
    "name": "escodegen",
    "optionalDependencies": {
        "source-map": "~0.2.0"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/estools/escodegen.git"
    },
    "scripts": {
        "build": "cjsify -a path: tools/entry-point.js > escodegen.browser.js",
        "build-min": "cjsify -ma path: tools/entry-point.js > escodegen.browser.min.js",
        "lint": "gulp lint",
        "release": "node tools/release.js",
        "test": "gulp travis",
        "unit-test": "gulp test"
    },
    "version": "1.8.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
