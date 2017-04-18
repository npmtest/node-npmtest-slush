# test coverage for  [slush (v1.1.1)](http://slushjs.github.io)  [![npm package](https://img.shields.io/npm/v/npmtest-slush.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-slush) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-slush.svg)](https://travis-ci.org/npmtest/node-npmtest-slush)
#### The streaming scaffolding system - Gulp as a replacement for Yeoman

[![NPM](https://nodei.co/npm/slush.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/slush)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-slush/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-slush/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-slush/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-slush/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-slush/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-slush/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-slush/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-slush/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-slush/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-slush/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-slush/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-slush/build/test-report.html](https://npmtest.github.io/node-npmtest-slush/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-slush/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-slush/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-slush/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-slush/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-slush/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-slush/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-slush/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-slush/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Joakim Bengtson"
    },
    "bin": {
        "slush": "./bin/slush.js"
    },
    "bugs": {
        "url": "https://github.com/slushjs/slush/issues"
    },
    "dependencies": {
        "archy": "^0.0.2",
        "chalk": "^0.4.0",
        "glob": "~4.0.0",
        "gulp-util": "^2.2.0",
        "liftoff": "~0.10.0",
        "minimist": "~0.1.0",
        "pretty-hrtime": "^0.2.0"
    },
    "description": "The streaming scaffolding system - Gulp as a replacement for Yeoman",
    "devDependencies": {
        "gulp": "~3.6.2",
        "gulp-jshint": "^1.4.0",
        "jshint": "^2.4.1",
        "mocha": "^1.17.0",
        "should": "^3.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "69d9d9981e425fef60a15535f07c55e8b84aa537",
        "tarball": "https://registry.npmjs.org/slush/-/slush-1.1.1.tgz"
    },
    "engineStrict": true,
    "engines": {
        "node": ">= 0.9"
    },
    "files": [
        "lib",
        "bin"
    ],
    "homepage": "http://slushjs.github.io",
    "keywords": [
        "scaffold",
        "stream",
        "project",
        "init",
        "tool",
        "yeoman",
        "gulp"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://raw.github.com/slushjs/slush/master/LICENSE"
        }
    ],
    "maintainers": [
        {
            "name": "joakimbeng"
        }
    ],
    "name": "slush",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/slushjs/slush.git"
    },
    "scripts": {
        "test": "node gulpfile.js && NODE_ENV=test mocha --reporter spec"
    },
    "version": "1.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
