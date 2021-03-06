# npmdoc-ionic

#### api documentation for  [ionic (v2.2.3-201704220743-201704220744)](http://ionicframework.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-ionic.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ionic) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ionic.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ionic)

#### A tool for creating and developing Ionic Framework mobile apps.

[![NPM](https://nodei.co/npm/ionic.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ionic)

- [https://npmdoc.github.io/node-npmdoc-ionic/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ionic/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ionic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ionic/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ionic/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ionic/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ionic",
    "version": "2.2.3-201704220743-201704220744",
    "preferGlobal": true,
    "description": "A tool for creating and developing Ionic Framework mobile apps.",
    "homepage": "http://ionicframework.com/",
    "bin": {
        "ionic": "bin/ionic"
    },
    "scripts": {
        "changelog": "conventional-changelog -i CHANGELOG.md -s -p angular",
        "gh-release": "node scripts/release",
        "coveralls": "istanbul cover node_modules/jasmine-node/bin/jasmine-node --captureExceptions spec/ && cat coverage/lcov.info | node_modules/coveralls/bin/coveralls.js && rm -rf coverage",
        "e2e": "jasmine-node --captureExceptions ./e2e",
        "jasmine": "jasmine-node --captureExceptions  ./spec",
        "lint": "eslint .",
        "test": "istanbul cover node_modules/jasmine-node/bin/jasmine-node --captureExceptions spec/",
        "publish:nightly": "node ./scripts/publish-nightly.js"
    },
    "keywords": [
        "ionic",
        "ionic framework",
        "ionicframework",
        "mobile",
        "app",
        "hybrid",
        "cordova",
        "native",
        "phonegap"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/driftyco/ionic-cli.git"
    },
    "contributors": [
        {
            "name": "Max Lynch",
            "web": "https://twitter.com/maxlynch"
        },
        {
            "name": "Peter Collins",
            "web": "https://twitter.com/SomethingNew2_0"
        },
        {
            "name": "Adam Bradley",
            "web": "https://twitter.com/adamdbradley"
        },
        {
            "name": "Josh Bavari",
            "web": "https://twitter.com/jbavari"
        },
        {
            "name": "Tim Lancina",
            "web": "https://twitter.com/timlancina"
        },
        {
            "name": "Josh Thomas",
            "web": "https://twitter.com/jthoms1"
        }
    ],
    "license": "MIT",
    "dependencies": {
        "@ionic/app-generators": "0.0.3",
        "chalk": "^1.1.3",
        "cli-table": "0.3.1",
        "cross-spawn": "^5.0.1",
        "expand-tilde": "1.2.0",
        "form-data": "0.1.4",
        "gulp": "3.8.8",
        "gulp-util": "3.0.7",
        "inquirer": "0.11.2",
        "ionic-app-lib": "2.2.1",
        "moment": "2.11.1",
        "open": "0.0.5",
        "optimist": "0.6.0",
        "pretty-hrtime": "1.0.2",
        "progress": "1.1.7",
        "prompt": "0.2.12",
        "q": "1.0.1",
        "request": "2.74.0",
        "semver": "4.3.6",
        "serve-static": "1.7.1",
        "shelljs": "0.2.6",
        "underscore": "1.7.0",
        "unzip": "0.1.9"
    },
    "devDependencies": {
        "conventional-changelog-cli": "1.1.1",
        "coveralls": "^2.2.0",
        "eslint": "^3.8.1",
        "eslint-plugin-no-use-extend-native": "^0.3.11",
        "github": "0.2.4",
        "istanbul": "^0.4.4",
        "jasmine-node": "1.14.5",
        "mock-require": "1.3.0",
        "rewire": "2.5.1"
    },
    "bundledDependencies": [
        "cli-table",
        "chalk",
        "cross-spawn",
        "expand-tilde",
        "form-data",
        "gulp",
        "gulp-util",
        "inquirer",
        "ionic-app-lib",
        "moment",
        "open",
        "optimist",
        "pretty-hrtime",
        "progress",
        "prompt",
        "q",
        "request",
        "semver",
        "serve-static",
        "shelljs",
        "underscore",
        "unzip"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
