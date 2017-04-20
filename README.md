# npmtest-commander-completion

#### basic test coverage for  [commander-completion (v1.0.0)](https://github.com/twolfson/commander-completion)  [![npm package](https://img.shields.io/npm/v/npmtest-commander-completion.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-commander-completion) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-commander-completion.svg)](https://travis-ci.org/npmtest/node-npmtest-commander-completion)

#### Shell completion for commander.js

[![NPM](https://nodei.co/npm/commander-completion.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/commander-completion)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-commander-completion/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-commander-completion/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-commander-completion/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-commander-completion/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-commander-completion/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-commander-completion/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-commander-completion/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-commander-completion/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-commander-completion/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-commander-completion/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-commander-completion/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-commander-completion/build/test-report.html](https://npmtest.github.io/node-npmtest-commander-completion/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-commander-completion/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-commander-completion/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-commander-completion/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-commander-completion/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-commander-completion/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-commander-completion/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-commander-completion/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-commander-completion/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "commander-completion",
    "description": "Shell completion for commander.js",
    "version": "1.0.0",
    "homepage": "https://github.com/twolfson/commander-completion",
    "author": {
        "name": "Todd Wolfson",
        "url": "http://twolfson.com/"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/twolfson/commander-completion.git"
    },
    "bugs": {
        "url": "https://github.com/twolfson/commander-completion/issues"
    },
    "license": "Unlicense",
    "main": "lib/commander-completion",
    "engines": {
        "node": ">= 4.0.0"
    },
    "scripts": {
        "lint": "twolfson-style lint lib/ test/",
        "test": "mocha && npm run lint"
    },
    "dependencies": {
        "completion": "~1.0.1"
    },
    "devDependencies": {
        "commander": "~2.9.0",
        "foundry": "~4.3.3",
        "foundry-release-git": "~2.0.2",
        "foundry-release-npm": "~2.0.2",
        "jscs": "~3.0.7",
        "jshint": "~2.9.4",
        "mocha": "~3.2.0",
        "twolfson-style": "~1.6.1"
    },
    "keywords": [
        "complete",
        "completion",
        "shell",
        "tab",
        "commander"
    ],
    "foundry": {
        "releaseCommands": [
            "foundry-release-npm",
            "foundry-release-git"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
