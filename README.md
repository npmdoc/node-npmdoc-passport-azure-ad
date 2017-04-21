# npmdoc-passport-azure-ad

#### api documentation for  passport-azure-ad (v3.0.6)  [![npm package](https://img.shields.io/npm/v/npmdoc-passport-azure-ad.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-passport-azure-ad) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-passport-azure-ad.svg)](https://travis-ci.org/npmdoc/node-npmdoc-passport-azure-ad)

#### OIDC and Bearer Passport strategies for Azure Active Directory

[![NPM](https://nodei.co/npm/passport-azure-ad.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/passport-azure-ad)

- [https://npmdoc.github.io/node-npmdoc-passport-azure-ad/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-passport-azure-ad/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-passport-azure-ad/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-passport-azure-ad/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-passport-azure-ad/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-passport-azure-ad/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "passport-azure-ad",
    "version": "3.0.6",
    "license": "MIT",
    "keywords": [
        "azure active directory",
        "aad",
        "adfs",
        "sso",
        "oidc",
        "bearer",
        "shibboleth"
    ],
    "description": "OIDC and Bearer Passport strategies for Azure Active Directory",
    "author": {
        "name": "azuread",
        "url": "http://microsoft.com/"
    },
    "repository": {
        "type": "git",
        "url": "git@github.com:AzureAD/passport-azure-ad.git"
    },
    "main": "./lib",
    "devDependencies": {
        "adal-node": "^0.1.22",
        "azure-keyvault": "^0.11.0",
        "chai": "2.x.x",
        "chai-passport-strategy": "1.x.x",
        "chromedriver": "^2.24.1",
        "eslint": "^2.9.0",
        "eslint-config-oniyi": "^3.0.0",
        "grunt": "^1.0.1",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-nodeunit": "^1.0.0",
        "grunt-contrib-uglify": "^1.0.1",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-eslint": "^18.1.0",
        "grunt-mocha-test": "^0.12.7",
        "mocha": "^3.0.2",
        "nodeunit": "^0.9.1",
        "selenium-webdriver": "^3.0.0",
        "server-graceful-shutdown": "^0.1.2"
    },
    "dependencies": {
        "async": "^1.5.2",
        "base64url": "^2.0.0",
        "bunyan": "^1.8.0",
        "cache-manager": "^2.0.0",
        "jws": "^3.1.3",
        "jwk-to-pem": "^1.2.6",
        "lodash": "^4.11.2",
        "oauth": "0.9.14",
        "passport": "^0.3.2",
        "pkginfo": "^0.4.0",
        "request": "^2.72.0",
        "valid-url": "^1.0.6"
    },
    "scripts": {
        "test": "grunt run_tests"
    },
    "engines": {
        "node": ">= 4.0.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
