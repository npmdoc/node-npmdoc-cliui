# npmdoc-cliui

#### api documentation for  [cliui (v3.2.0)](https://github.com/yargs/cliui#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-cliui.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cliui) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cliui.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cliui)

#### easily create complex multi-column command-line-interfaces

[![NPM](https://nodei.co/npm/cliui.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cliui)

- [https://npmdoc.github.io/node-npmdoc-cliui/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cliui/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cliui/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cliui/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cliui/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cliui/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Coe"
    },
    "bugs": {
        "url": "https://github.com/yargs/cliui/issues"
    },
    "config": {
        "blanket": {
            "pattern": [
                "index.js"
            ],
            "data-cover-never": [
                "node_modules",
                "test"
            ],
            "output-reporter": "spec"
        }
    },
    "dependencies": {
        "string-width": "^1.0.1",
        "strip-ansi": "^3.0.1",
        "wrap-ansi": "^2.0.0"
    },
    "description": "easily create complex multi-column command-line-interfaces",
    "devDependencies": {
        "chai": "^3.5.0",
        "chalk": "^1.1.2",
        "coveralls": "^2.11.8",
        "mocha": "^2.4.5",
        "nyc": "^6.4.0",
        "standard": "^6.0.8",
        "standard-version": "^2.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "120601537a916d29940f934da3b48d585a39213d",
        "tarball": "https://registry.npmjs.org/cliui/-/cliui-3.2.0.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "75d62e9dfa77a0e0a9c3ac3b96b02baa294142ce",
    "homepage": "https://github.com/yargs/cliui#readme",
    "keywords": [
        "cli",
        "command-line",
        "layout",
        "design",
        "console",
        "wrap",
        "table"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bcoe"
        }
    ],
    "name": "cliui",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/yargs/cliui.git"
    },
    "scripts": {
        "coverage": "nyc --reporter=text-lcov mocha | coveralls",
        "pretest": "standard",
        "test": "nyc mocha",
        "version": "standard-version"
    },
    "standard": {
        "ignore": [
            "**/example/**"
        ],
        "globals": [
            "it"
        ]
    },
    "version": "3.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
