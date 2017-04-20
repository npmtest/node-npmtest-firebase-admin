# npmtest-firebase-admin

#### basic test coverage for  [firebase-admin (v4.2.1)](https://firebase.google.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-firebase-admin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-firebase-admin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-firebase-admin.svg)](https://travis-ci.org/npmtest/node-npmtest-firebase-admin)

#### Firebase admin SDK for Node.js

[![NPM](https://nodei.co/npm/firebase-admin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/firebase-admin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-firebase-admin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-firebase-admin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-firebase-admin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-firebase-admin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-firebase-admin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-firebase-admin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-firebase-admin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-firebase-admin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-firebase-admin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-firebase-admin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-firebase-admin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-firebase-admin/build/test-report.html](https://npmtest.github.io/node-npmtest-firebase-admin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-firebase-admin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-firebase-admin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-firebase-admin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-firebase-admin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-firebase-admin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-firebase-admin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-firebase-admin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-firebase-admin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "firebase-admin",
    "version": "4.2.1",
    "description": "Firebase admin SDK for Node.js",
    "author": "Firebase (https://firebase.google.com/)",
    "license": "SEE LICENSE IN https://firebase.google.com/terms/",
    "homepage": "https://firebase.google.com/",
    "keywords": [
        "admin",
        "database",
        "Firebase",
        "realtime",
        "authentication"
    ],
    "main": "lib/index.js",
    "files": [
        "lib/",
        "README.md",
        "package.json",
        "npm-shrinkwrap.json"
    ],
    "types": "./lib/index.d.ts",
    "dependencies": {
        "@types/jsonwebtoken": "^7.1.33",
        "faye-websocket": "0.9.3",
        "jsonwebtoken": "7.1.9"
    },
    "devDependencies": {
        "@types/chai": "^3.4.34",
        "@types/chai-as-promised": "0.0.29",
        "@types/firebase-token-generator": "^2.0.28",
        "@types/lodash": "^4.14.38",
        "@types/mocha": "^2.2.32",
        "@types/nock": "^8.0.33",
        "@types/request": "0.0.32",
        "@types/request-promise": "^4.1.33",
        "@types/sinon": "^1.16.31",
        "@types/sinon-chai": "^2.7.27",
        "chai": "^3.5.0",
        "chai-as-promised": "^6.0.0",
        "chalk": "^1.1.3",
        "del": "^2.2.1",
        "firebase": "^3.6.9",
        "firebase-token-generator": "^2.0.0",
        "gulp": "^3.9.1",
        "gulp-exit": "0.0.2",
        "gulp-header": "^1.8.8",
        "gulp-istanbul": "^1.1.1",
        "gulp-mocha": "^3.0.1",
        "gulp-replace": "^0.5.4",
        "gulp-tslint": "^6.0.2",
        "gulp-typescript": "^3.1.2",
        "lodash": "^4.6.1",
        "merge2": "^1.0.2",
        "nock": "^8.0.0",
        "request": "^2.75.0",
        "request-promise": "^4.1.1",
        "run-sequence": "^1.1.5",
        "sinon": "^1.17.3",
        "sinon-chai": "^2.8.0",
        "tslint": "^3.5.0",
        "typescript": "^2.0.3",
        "typings": "^1.0.4"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
