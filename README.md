# npmtest-treeize

#### basic test coverage for  [treeize (v2.0.2)](https://github.com/kwhitley/treeize#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-treeize.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-treeize) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-treeize.svg)](https://travis-ci.org/npmtest/node-npmtest-treeize)

#### Converts tabular row data (as from SQL joins, flat JSON, etc) to deep object graphs based on simple column naming conventions - without the use of an ORM or models.

[![NPM](https://nodei.co/npm/treeize.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/treeize)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-treeize/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-treeize/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-treeize/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-treeize/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-treeize/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-treeize/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-treeize/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-treeize/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-treeize/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-treeize/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-treeize/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-treeize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-treeize/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-treeize/build/test-report.html](https://npmtest.github.io/node-npmtest-treeize/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-treeize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-treeize/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-treeize/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-treeize/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-treeize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-treeize/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-treeize/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-treeize/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "K. R. Whitley",
        "url": "http://krwhitley.com/"
    },
    "bugs": {
        "url": "https://github.com/kwhitley/treeize/issues"
    },
    "dependencies": {
        "inflection": "~1.2.6",
        "lodash": "~1.3.1",
        "object-merge": "~2.5.1"
    },
    "description": "Converts tabular row data (as from SQL joins, flat JSON, etc) to deep object graphs based on simple column naming conventions - without the use of an ORM or models.",
    "devDependencies": {
        "grunt": "latest",
        "grunt-cli": "latest",
        "grunt-contrib-jshint": "latest",
        "grunt-contrib-nodeunit": "latest",
        "grunt-contrib-watch": "latest",
        "grunt-mocha-test": "~0.12.0",
        "mocha": "latest",
        "should": "latest"
    },
    "directories": {},
    "dist": {
        "shasum": "e8f5a0a8275d7c7273770a4ef5d1b13e256f988b",
        "tarball": "https://registry.npmjs.org/treeize/-/treeize-2.0.2.tgz"
    },
    "gitHead": "0d8f89bc0032b7d33805cd4b1581e61c20f53e9a",
    "homepage": "https://github.com/kwhitley/treeize#readme",
    "keywords": [
        "JSON",
        "SQL",
        "CSV",
        "excel",
        "tree",
        "object",
        "graph",
        "hydration",
        "incongrous",
        "multi-source",
        "model",
        "deep",
        "convert",
        "expand",
        "flat",
        "array",
        "ORM"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://en.wikipedia.org/wiki/MIT_License"
        }
    ],
    "main": "./lib/treeize.js",
    "maintainers": [
        {
            "name": "kwhitley"
        }
    ],
    "name": "treeize",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kwhitley/treeize.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "2.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
