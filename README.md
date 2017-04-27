# npmtest-juice

#### basic test coverage for  [juice (v4.0.2)](https://github.com/Automattic/juice#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-juice.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-juice) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-juice.svg)](https://travis-ci.org/npmtest/node-npmtest-juice)

#### Inlines css into html source

[![NPM](https://nodei.co/npm/juice.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/juice)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-juice/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-juice/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-juice/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-juice/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-juice/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-juice/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-juice/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-juice/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-juice/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-juice/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-juice/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-juice/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-juice/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-juice/build/test-report.html](https://npmtest.github.io/node-npmtest-juice/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-juice/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-juice/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-juice/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-juice/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-juice/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-juice/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-juice/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-juice/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "juice": "bin/juice"
    },
    "browser": "client.js",
    "bugs": {
        "url": "https://github.com/Automattic/juice/issues"
    },
    "contributors": [
        {
            "name": "Guillermo Rauch"
        },
        {
            "name": "Arian Stolwijk"
        },
        {
            "name": "Paweł Marzec"
        },
        {
            "name": "Andrew Kelley"
        },
        {
            "name": "Francois-Guillaume Ribreau"
        }
    ],
    "dependencies": {
        "cheerio": "^0.22.0",
        "commander": "2.9.0",
        "cross-spawn": "^5.0.1",
        "deep-extend": "^0.4.0",
        "mensch": "^0.3.3",
        "slick": "1.12.2",
        "web-resource-inliner": "^4.0.0"
    },
    "description": "Inlines css into html source",
    "devDependencies": {
        "batch": "0.5.3",
        "mocha": "^3.1.2",
        "should": "^11.1.1",
        "typescript": "^2.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "0797481c9a8ee3b780fe6dadc95e21119a8a9674",
        "tarball": "https://registry.npmjs.org/juice/-/juice-4.0.2.tgz"
    },
    "engines": {
        "node": ">=4.2.0"
    },
    "gitHead": "de6a32044109d7cca4ade4db797585a5407f63ba",
    "homepage": "https://github.com/Automattic/juice#readme",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "rauchg"
        },
        {
            "name": "superjoe"
        },
        {
            "name": "jrit"
        }
    ],
    "name": "juice",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Automattic/juice.git"
    },
    "scripts": {
        "test": "mocha --reporter spec && npm run test-typescript",
        "test-typescript": "tsc ./test/typescript/juice-tests.ts && rm ./test/typescript/juice-tests.js",
        "testcover": "istanbul cover node_modules/mocha/bin/_mocha -- -R spec"
    },
    "types": "juice.d.ts",
    "version": "4.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
