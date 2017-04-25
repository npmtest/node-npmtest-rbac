# npmtest-rbac

#### basic test coverage for  [rbac (v4.0.2)](https://github.com/CherryProjects/rbac#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-rbac.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rbac) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rbac.svg)](https://travis-ci.org/npmtest/node-npmtest-rbac)

#### Hierarchical Role Based Access Control

[![NPM](https://nodei.co/npm/rbac.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rbac)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rbac/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rbac/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rbac/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rbac/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rbac/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-rbac/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-rbac/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rbac/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rbac/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rbac/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rbac/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rbac/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rbac/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rbac/build/test-report.html](https://npmtest.github.io/node-npmtest-rbac/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rbac/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rbac/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rbac/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rbac/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rbac/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rbac/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rbac/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rbac/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Zlatko Fedor",
        "url": "http://www.cherrysro.com/"
    },
    "bugs": {
        "url": "https://github.com/seeden/rbac/issues"
    },
    "dependencies": {
        "async": "^2.3.0",
        "keymirror": "^0.1.1",
        "lodash": "^4.17.4",
        "web-error": "^4.0.1"
    },
    "description": "Hierarchical Role Based Access Control",
    "devDependencies": {
        "babel-cli": "^6.24.0",
        "babel-core": "^6.24.0",
        "babel-eslint": "^7.2.1",
        "babel-plugin-transform-class-properties": "^6.23.0",
        "babel-preset-es2015": "^6.24.0",
        "babel-preset-react": "^6.23.0",
        "babel-preset-stage-0": "^6.22.0",
        "babel-preset-stage-1": "^6.22.0",
        "eslint": "^3.19.0",
        "eslint-config-airbnb": "^14.1.0",
        "eslint-loader": "^1.7.1",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-react": "^6.10.3",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-jsdoc3": "^1.0.1",
        "gulp-util": "^3.0.8",
        "jaguarjs-jsdoc": "^1.0.2",
        "jest": "^19.0.2",
        "jest-cli": "^19.0.2",
        "jsdoc": "^3.4.3",
        "mongoose": "^4.9.3",
        "should": "^11.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "65651141a14bde609cca5801717231520914aeb9",
        "tarball": "https://registry.npmjs.org/rbac/-/rbac-4.0.2.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "2e39316be8200b43096a9682e9d237d50810cae2",
    "homepage": "https://github.com/CherryProjects/rbac#readme",
    "keywords": [
        "role",
        "permission",
        "access",
        "RBAC",
        "hierarchical",
        "privacy",
        "mongoose",
        "passport"
    ],
    "license": "MIT",
    "main": "./dist/index.js",
    "maintainers": [
        {
            "name": "zlatkofedor"
        }
    ],
    "name": "rbac",
    "optionalDependencies": {},
    "private": false,
    "repository": {
        "type": "git",
        "url": "git://github.com/CherryProjects/rbac.git"
    },
    "scripts": {
        "build": "babel-node ./node_modules/gulp/bin/gulp.js build",
        "coveralls": "babel-node ./node_modules/gulp/bin/gulp.js coveralls",
        "doc": "babel-node ./node_modules/gulp/bin/gulp.js doc",
        "eslint": "node ./node_modules/eslint/bin/eslint.js --ext .js,.jsx .",
        "prepublish": "npm run build",
        "test": "jest --coverage"
    },
    "version": "4.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
