# npmdoc-keytar

#### api documentation for  [keytar (v4.0.2)](http://atom.github.io/node-keytar)  [![npm package](https://img.shields.io/npm/v/npmdoc-keytar.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-keytar) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-keytar.svg)](https://travis-ci.org/npmdoc/node-npmdoc-keytar)

#### Bindings to native Mac/Linux/Windows password APIs

[![NPM](https://nodei.co/npm/keytar.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/keytar)

- [https://npmdoc.github.io/node-npmdoc-keytar/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-keytar/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-keytar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-keytar/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-keytar/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-keytar/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "main": "./lib/keytar.js",
    "name": "keytar",
    "description": "Bindings to native Mac/Linux/Windows password APIs",
    "version": "4.0.2",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/atom/node-keytar.git"
    },
    "bugs": {
        "url": "https://github.com/atom/node-keytar/issues"
    },
    "homepage": "http://atom.github.io/node-keytar",
    "keywords": [
        "keychain",
        "password",
        "passwords",
        "credential",
        "credentials",
        "vault",
        "credential vault"
    ],
    "scripts": {
        "lint": "npm run cpplint",
        "cpplint": "node-cpplint --filters legal-copyright,build-include,build-namespaces src/*.cc",
        "test": "npm run lint && npm build . && mocha --compilers js:babel-core/register spec/"
    },
    "devDependencies": {
        "babel-core": "^6.24.1",
        "babel-plugin-transform-async-to-generator": "^6.24.1",
        "chai": "^3.5.0",
        "mocha": "^3.2.0",
        "node-cpplint": "~0.1.5",
        "node-gyp": "^3.6.0"
    },
    "dependencies": {
        "nan": "2.5.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
