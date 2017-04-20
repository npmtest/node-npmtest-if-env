# npmtest-if-env

#### basic test coverage for  [if-env (v1.0.0)](https://github.com/ericclemmons/if-env#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-if-env.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-if-env) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-if-env.svg)](https://travis-ci.org/npmtest/node-npmtest-if-env)

#### Simplify npm scripts with "if-env ... && npm run this || npm run that"

[![NPM](https://nodei.co/npm/if-env.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/if-env)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-if-env/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-if-env/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-if-env/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-if-env/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-if-env/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-if-env/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-if-env/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-if-env/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-if-env/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-if-env/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-if-env/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-if-env/build/test-report.html](https://npmtest.github.io/node-npmtest-if-env/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-if-env/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-if-env/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-if-env/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-if-env/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-if-env/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-if-env/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-if-env/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-if-env/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eric Clemmons"
    },
    "bin": {
        "if-env": "bin/if-env.js"
    },
    "bugs": {
        "url": "https://github.com/ericclemmons/if-env/issues"
    },
    "dependencies": {
        "npm-run-all": "1.4.0"
    },
    "description": "Simplify npm scripts with \"if-env ... && npm run this || npm run that\"",
    "devDependencies": {
        "expect": "1.13.4",
        "mocha": "2.3.4"
    },
    "directories": {},
    "dist": {
        "shasum": "6e09082cdd3f2ccfb75baf022a4a971565f6007c",
        "tarball": "https://registry.npmjs.org/if-env/-/if-env-1.0.0.tgz"
    },
    "gitHead": "98fdbf4e651f7cdc88cec9f05d50a47f9768ed03",
    "homepage": "https://github.com/ericclemmons/if-env#readme",
    "keywords": [
        "npm",
        "script",
        "env",
        "if",
        "run"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "ericclemmons"
        }
    ],
    "name": "if-env",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ericclemmons/if-env.git"
    },
    "scripts": {
        "changelog": "npm-run-all changelog:generate changelog:add",
        "changelog:add": "git add CHANGELOG.md",
        "changelog:generate": "github_changelog_generator --future-release $npm_package_version",
        "postversion": "npm-run-all version:amend publish",
        "publish": "npm-run-all publish:git publish:npm",
        "publish:git": "git push && git push --tags",
        "publish:npm": "npm publish",
        "test": "NODE_ENV=test mocha",
        "version": "npm run changelog",
        "version:ammend": "git commit --amend -m \"Release v${npm_package_version}\" && npm run release"
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
