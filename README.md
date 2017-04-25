# npmtest-execa

#### basic test coverage for  [execa (v0.6.3)](https://github.com/sindresorhus/execa#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-execa.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-execa) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-execa.svg)](https://travis-ci.org/npmtest/node-npmtest-execa)

#### A better `child_process`

[![NPM](https://nodei.co/npm/execa.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/execa)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-execa/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-execa/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-execa/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-execa/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-execa/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-execa/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-execa/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-execa/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-execa/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-execa/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-execa/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-execa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-execa/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-execa/build/test-report.html](https://npmtest.github.io/node-npmtest-execa/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-execa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-execa/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-execa/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-execa/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-execa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-execa/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-execa/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-execa/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "bugs": {
        "url": "https://github.com/sindresorhus/execa/issues"
    },
    "dependencies": {
        "cross-spawn": "^5.0.1",
        "get-stream": "^3.0.0",
        "is-stream": "^1.1.0",
        "npm-run-path": "^2.0.0",
        "p-finally": "^1.0.0",
        "signal-exit": "^3.0.0",
        "strip-eof": "^1.0.0"
    },
    "description": "A better 'child_process'",
    "devDependencies": {
        "ava": "*",
        "cat-names": "^1.0.2",
        "coveralls": "^2.11.9",
        "delay": "^1.3.1",
        "is-running": "^2.0.0",
        "nyc": "^10.0.0",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "57b69a594f081759c69e5370f0d17b9cb11658fe",
        "tarball": "https://registry.npmjs.org/execa/-/execa-0.6.3.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "2892941f582608f2e1f79b584761392906553feb",
    "homepage": "https://github.com/sindresorhus/execa#readme",
    "keywords": [
        "exec",
        "child",
        "process",
        "execute",
        "fork",
        "execfile",
        "spawn",
        "file",
        "shell",
        "bin",
        "binary",
        "binaries",
        "npm",
        "path",
        "local"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "sindresorhus"
        }
    ],
    "name": "execa",
    "nyc": {
        "reporter": [
            "text",
            "lcov"
        ],
        "exclude": [
            "**/fixtures/**",
            "**/test.js",
            "**/test/**"
        ]
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/execa.git"
    },
    "scripts": {
        "test": "xo && nyc ava"
    },
    "version": "0.6.3",
    "xo": {
        "esnext": true
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
