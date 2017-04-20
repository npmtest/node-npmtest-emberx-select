# npmtest-emberx-select

#### basic test coverage for  [emberx-select (v3.0.1)](https://github.com/thefrontside/emberx-select#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-emberx-select.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-emberx-select) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-emberx-select.svg)](https://travis-ci.org/npmtest/node-npmtest-emberx-select)

#### A Select component based on html select.

[![NPM](https://nodei.co/npm/emberx-select.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/emberx-select)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-emberx-select/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-emberx-select/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-emberx-select/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-emberx-select/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-emberx-select/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-emberx-select/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-emberx-select/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-emberx-select/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-emberx-select/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-emberx-select/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-emberx-select/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-emberx-select/build/test-report.html](https://npmtest.github.io/node-npmtest-emberx-select/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-emberx-select/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-emberx-select/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-emberx-select/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-emberx-select/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-emberx-select/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-emberx-select/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-emberx-select/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-emberx-select/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "The Frontside"
    },
    "bugs": {
        "url": "https://github.com/thefrontside/emberx-select/issues"
    },
    "dependencies": {
        "ember-cli-babel": "^5.1.7",
        "ember-cli-htmlbars": "^1.1.1",
        "ember-cli-version-checker": "^1.2.0"
    },
    "description": "A Select component based on html select.",
    "devDependencies": {
        "broccoli-asset-rev": "^2.4.5",
        "ember-ajax": "^2.4.1",
        "ember-cli": "2.12.1",
        "ember-cli-chai": "^0.2.0",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-cli-deploy": "0.5.1",
        "ember-cli-document-title": "0.3.3",
        "ember-cli-eslint": "^3.0.0",
        "ember-cli-htmlbars-inline-precompile": "^0.3.6",
        "ember-cli-inject-live-reload": "^1.4.1",
        "ember-cli-mocha": "0.13.2",
        "ember-cli-release": "^1.0.0-beta.2",
        "ember-cli-shims": "^1.0.2",
        "ember-cli-uglify": "^1.2.0",
        "ember-data": "^2.12.1",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.6.0",
        "ember-resolver": "^2.0.3",
        "ember-sinon": "0.5.1",
        "ember-source": "~2.12.0",
        "eslint-plugin-prefer-let": "^0.1.0",
        "fs-branding": "0.1.3",
        "loader.js": "^4.2.3",
        "markdown-code-highlighting": "0.1.0"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "8daca28f7ab8352e60a30cc617afa45b3c30f388",
        "tarball": "https://registry.npmjs.org/emberx-select/-/emberx-select-3.0.1.tgz"
    },
    "ember-addon": {
        "demoURL": "http://emberx-select.pagefrontapp.com",
        "configPath": "tests/dummy/config",
        "versionCompatibility": {
            "ember": ">=1.13.4"
        }
    },
    "engines": {
        "node": ">= 4"
    },
    "gitHead": "d55b254dab94f0695cc6c5b2349c625feb593cc3",
    "homepage": "https://github.com/thefrontside/emberx-select#readme",
    "keywords": [
        "ember-addon",
        "select",
        "ember select",
        "emberx-select",
        "select box",
        "ember select component"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "cowboyd"
        },
        {
            "name": "robdel12"
        }
    ],
    "name": "emberx-select",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/thefrontside/emberx-select.git"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:each"
    },
    "version": "3.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
