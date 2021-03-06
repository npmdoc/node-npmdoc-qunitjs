# npmdoc-qunitjs

#### api documentation for  [qunitjs (v2.3.2)](https://qunitjs.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-qunitjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-qunitjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-qunitjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-qunitjs)

#### An easy-to-use JavaScript Unit Testing framework.

[![NPM](https://nodei.co/npm/qunitjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/qunitjs)

- [https://npmdoc.github.io/node-npmdoc-qunitjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-qunitjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-qunitjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-qunitjs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-qunitjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-qunitjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "qunitjs",
    "title": "QUnit",
    "description": "An easy-to-use JavaScript Unit Testing framework.",
    "version": "2.3.2",
    "homepage": "https://qunitjs.com",
    "author": {
        "name": "jQuery Foundation and other contributors",
        "url": "https://github.com/qunitjs/qunit/blob/2.3.2/AUTHORS.txt"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/qunitjs/qunit.git"
    },
    "keywords": [
        "testing",
        "unit",
        "jquery"
    ],
    "bugs": {
        "url": "https://github.com/qunitjs/qunit/issues"
    },
    "license": "MIT",
    "bin": {
        "qunit": "bin/qunit"
    },
    "files": [
        "bin/",
        "qunit/qunit.js",
        "qunit/qunit.css",
        "LICENSE.txt"
    ],
    "dependencies": {
        "chokidar": "1.6.1",
        "commander": "2.9.0",
        "exists-stat": "1.0.0",
        "findup-sync": "^0.4.3",
        "js-reporters": "1.2.0",
        "walk-sync": "0.3.1"
    },
    "devDependencies": {
        "async": "2.1.4",
        "babel-plugin-external-helpers": "6.18.0",
        "babel-preset-es2015": "6.18.0",
        "browserstack-runner": "0.4.4",
        "co": "4.6.0",
        "commitplease": "2.7.6",
        "eslint-config-jquery": "1.0.0",
        "eslint-plugin-html": "1.7.0",
        "eslint-plugin-qunit": "2.3.0",
        "execa": "0.6.1",
        "fixturify": "0.3.3",
        "fs-extra": "1.0.0",
        "grunt": "1.0.1",
        "grunt-cli": "1.2.0",
        "grunt-concurrent": "2.3.1",
        "grunt-contrib-connect": "1.0.2",
        "grunt-contrib-copy": "1.0.0",
        "grunt-contrib-qunit": "1.3.0",
        "grunt-contrib-watch": "1.0.0",
        "grunt-coveralls": "1.0.1",
        "grunt-eslint": "19.0.0",
        "grunt-git-authors": "3.2.0",
        "grunt-istanbul": "0.7.2",
        "grunt-rollup": "1.0.1",
        "grunt-search": "0.1.8",
        "load-grunt-tasks": "3.5.2",
        "npm-reporter": "file:./test/cli/fixtures/npm-reporter",
        "requirejs": "2.3.2",
        "rollup-plugin-babel": "2.6.1"
    },
    "scripts": {
        "browserstack": "grunt build && sh build/run-browserstack.sh",
        "build": "grunt build",
        "test": "grunt",
        "coverage": "grunt coverage",
        "test:cli": "grunt build && npm link && qunit test/cli/*.js"
    },
    "commitplease": {
        "components": [
            "All",
            "Assert",
            "Build",
            "CLI",
            "CSS",
            "Core",
            "Docs",
            "Dump",
            "HTML Reporter",
            "Readme",
            "Test",
            "Tests"
        ]
    },
    "main": "qunit/qunit.js",
    "engines": {
        "node": "4.* || 6.* || 7.*"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
