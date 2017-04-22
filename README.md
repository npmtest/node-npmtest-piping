# npmtest-piping

#### basic test coverage for  [piping (v1.0.0-rc.4)](https://github.com/mdlawson/piping#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-piping.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-piping) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-piping.svg)](https://travis-ci.org/npmtest/node-npmtest-piping)

#### Keep your code piping hot! Live code reloading without additional binaries

[![NPM](https://nodei.co/npm/piping.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/piping)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-piping/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-piping/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-piping/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-piping/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-piping/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-piping/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-piping/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-piping/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-piping/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-piping/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-piping/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-piping/build/test-report.html](https://npmtest.github.io/node-npmtest-piping/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-piping/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-piping/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-piping/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-piping/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-piping/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-piping/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-piping/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-piping/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Lawson"
    },
    "ava": {
        "serial": true
    },
    "babel": {
        "presets": [
            "es2015-loose"
        ]
    },
    "bugs": {
        "url": "https://github.com/mdlawson/piping/issues"
    },
    "dependencies": {
        "chokidar": "^1.5.0",
        "colors": "1.1.x",
        "lodash": "^4.12.0"
    },
    "description": "Keep your code piping hot! Live code reloading without additional binaries",
    "devDependencies": {
        "autochecker": "^0.9.2",
        "ava": "^0.14.0",
        "babel-cli": "^6.9.0",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-es2015-loose": "^7.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "775a14cf651aa42ee5b4aacab3548c5172d2857c",
        "tarball": "https://registry.npmjs.org/piping/-/piping-1.0.0-rc.4.tgz"
    },
    "gitHead": "83f75bca059976ba36d5d95dfa7e89dd9043b80c",
    "homepage": "https://github.com/mdlawson/piping#readme",
    "keywords": [
        "live",
        "code",
        "reload",
        "hot"
    ],
    "license": "MIT",
    "main": "lib/piping.js",
    "maintainers": [
        {
            "name": "mdlawson"
        },
        {
            "name": "steida"
        }
    ],
    "name": "piping",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mdlawson/piping.git"
    },
    "scripts": {
        "build": "babel src --out-dir lib",
        "dev": "npm run build -s -- --watch",
        "prepublish": "npm run build",
        "test": "ava test",
        "test-all": "autochecker 4 5 6"
    },
    "version": "1.0.0-rc.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
