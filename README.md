# npmtest-angular2-datatable

#### basic test coverage for  [angular2-datatable (v0.6.0)](https://github.com/mariuszfoltak/angular2-datatable#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-angular2-datatable.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-angular2-datatable) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-angular2-datatable.svg)](https://travis-ci.org/npmtest/node-npmtest-angular2-datatable)

#### DataTable component for Angular2 framework

[![NPM](https://nodei.co/npm/angular2-datatable.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/angular2-datatable)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-angular2-datatable/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular2-datatable/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-angular2-datatable/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-angular2-datatable/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-angular2-datatable/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-angular2-datatable/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-angular2-datatable/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-angular2-datatable/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-angular2-datatable/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-angular2-datatable/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-angular2-datatable/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular2-datatable/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-angular2-datatable/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-angular2-datatable/build/test-report.html](https://npmtest.github.io/node-npmtest-angular2-datatable/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-angular2-datatable/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-angular2-datatable/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-angular2-datatable/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-angular2-datatable/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-angular2-datatable/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-angular2-datatable/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-angular2-datatable/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-angular2-datatable/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "mariuszfoltak@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/mariuszfoltak/angular2-datatable/issues"
    },
    "dependencies": {
        "lodash": "^4.0.0"
    },
    "description": "DataTable component for Angular2 framework",
    "devDependencies": {
        "@angular/common": "^2.1.0",
        "@angular/compiler": "^2.1.0",
        "@angular/compiler-cli": "^2.1.0",
        "@angular/core": "^2.1.0",
        "@angular/platform-browser": "^2.1.0",
        "@angular/platform-browser-dynamic": "^2.1.0",
        "@types/jasmine": "^2.5.35",
        "@types/lodash": "ts2.0",
        "core-js": "^2.4.1",
        "http-server": "^0.9.0",
        "jasmine-core": "^2.4.1",
        "karma": "^1.3.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-coverage": "^1.1.1",
        "karma-jasmine": "^1.0.2",
        "karma-phantomjs-launcher": "^1.0.2",
        "lodash": "^4.0.0",
        "phantomjs-prebuilt": "^2.1.7",
        "remap-istanbul": "^0.7.0",
        "rimraf": "^2.5.4",
        "rxjs": "5.0.0-beta.12",
        "systemjs": "^0.19.39",
        "typescript": "~2.1.0",
        "zone.js": "^0.6.25"
    },
    "directories": {},
    "dist": {
        "shasum": "ca008f74087f0cb87da5709ed2f2d1d061772632",
        "tarball": "https://registry.npmjs.org/angular2-datatable/-/angular2-datatable-0.6.0.tgz"
    },
    "gitHead": "9d3c4e626e9e5fc74c429bdbf903ccba1d28c413",
    "homepage": "https://github.com/mariuszfoltak/angular2-datatable#readme",
    "keywords": [
        "angular",
        "angularjs",
        "angular2",
        "ng",
        "ng2",
        "table",
        "pagination",
        "sort",
        "sorting"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mariuszfoltak"
        }
    ],
    "name": "angular2-datatable",
    "optionalDependencies": {},
    "peerDependencies": {
        "@angular/core": "^2.0.0",
        "@angular/common": "^2.0.0",
        "@angular/platform-browser": "^2.0.0",
        "rxjs": "^5.0.0-beta.12"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mariuszfoltak/angular2-datatable.git"
    },
    "scripts": {
        "build": "ngc -p src",
        "coverage": "http-server -c-1 -o -p 9875 ./coverage",
        "coverage-remap": "remap-istanbul -i coverage/coverage-final.json -o coverage/coverage-remapped.lcov -t lcovonly",
        "posttest": "remap-istanbul -i coverage/coverage-final.json -o coverage -t html",
        "prebuild": "rimraf lib",
        "pretest": "npm run build",
        "start": "http-server -c-1 -o -p 8875 .",
        "test": "karma start karma.conf.js"
    },
    "version": "0.6.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
