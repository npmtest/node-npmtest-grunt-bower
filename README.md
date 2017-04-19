# npmtest-grunt-bower

#### test coverage for  [grunt-bower (v0.21.4)](https://github.com/curist/grunt-bower)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-bower.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-bower) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-bower.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-bower)

#### Copy bower installed components to dist folder.

[![NPM](https://nodei.co/npm/grunt-bower.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-bower)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-bower/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-bower/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-bower/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-bower/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-bower/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-bower/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-bower/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-bower/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-bower/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-bower/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-bower/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-bower/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-bower/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-bower/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-bower/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-bower/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-bower/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-bower/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-bower/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-bower/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-bower/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "curist"
    },
    "bugs": {
        "url": "https://github.com/curist/grunt-bower/issues"
    },
    "dependencies": {
        "bower": "~1.7.9",
        "lodash": "^4.13.0"
    },
    "description": "Copy bower installed components to dist folder.",
    "devDependencies": {
        "grunt": "~0.4.0",
        "grunt-contrib-clean": "~0.3.1",
        "grunt-contrib-jshint": "~0.1.1",
        "grunt-contrib-nodeunit": "~0.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "e19fc62a1f698f20a97ae3f3587b0d556e8ec63c",
        "tarball": "https://registry.npmjs.org/grunt-bower/-/grunt-bower-0.21.4.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "fbd5b226978eebfa32571af83d4f4eee26ce89e3",
    "homepage": "https://github.com/curist/grunt-bower",
    "keywords": [
        "gruntplugin"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/curist/grunt-bower/blob/master/LICENSE-MIT"
        }
    ],
    "main": "grunt.js",
    "maintainers": [
        {
            "name": "curist"
        }
    ],
    "name": "grunt-bower",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/curist/grunt-bower.git"
    },
    "scripts": {
        "test": "cd ./test/boilerplate && npm install && rm -rf node_modules/grunt-bower && ln -nfs ../../.. node_modules/grunt-bower && node run_test.js"
    },
    "version": "0.21.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
