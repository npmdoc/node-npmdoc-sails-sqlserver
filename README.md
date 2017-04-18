# npmdoc-sails-sqlserver

#### api documentation for  [sails-sqlserver (v0.10.8)](https://github.com/cnect/sails-sqlserver)  [![npm package](https://img.shields.io/npm/v/npmdoc-sails-sqlserver.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sails-sqlserver) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sails-sqlserver.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sails-sqlserver)

#### Official SQL Server Adapter for Sails / Waterline

[![NPM](https://nodei.co/npm/sails-sqlserver.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sails-sqlserver)

- [https://npmdoc.github.io/node-npmdoc-sails-sqlserver/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sails-sqlserver/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails-sqlserver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails-sqlserver/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sails-sqlserver/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sails-sqlserver/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Travis Webb"
    },
    "bugs": {
        "url": "https://github.com/cnect/sails-sqlserver/issues"
    },
    "bundleDependencies": [
        "lodash",
        "mssql",
        "underscore.string",
        "waterline-cursor"
    ],
    "contributors": [
        {
            "name": "balderdashy"
        },
        {
            "name": "Stuart Welham"
        },
        {
            "name": "wxactly"
        },
        {
            "name": "Seich"
        },
        {
            "name": "tjwebb"
        },
        {
            "name": "jaredfromsubway"
        }
    ],
    "dependencies": {
        "captains-log": "^0.11.11",
        "lodash": "^3.8.0",
        "mssql": "^2.1.3",
        "underscore.string": "^3.0.0",
        "waterline-cursor": "0.0.5"
    },
    "description": "Official SQL Server Adapter for Sails / Waterline",
    "devDependencies": {
        "mocha": "*",
        "waterline-adapter-tests": "git://github.com/tjwebb/waterline-adapter-tests.git"
    },
    "directories": {},
    "dist": {
        "shasum": "8e2af717b50bd18a99e6b7645ca37f8e60e5f6fd",
        "tarball": "https://registry.npmjs.org/sails-sqlserver/-/sails-sqlserver-0.10.8.tgz"
    },
    "gitHead": "6ae53197a84e3ab6d0b5ee3baba7224aada07a78",
    "homepage": "https://github.com/cnect/sails-sqlserver",
    "keywords": [
        "cnect",
        "sails",
        "sails-mssql",
        "sails-sqlserver",
        "sql server",
        "sqlserver",
        "microsoft",
        "azure",
        "adapter",
        "waterline",
        "sails.js",
        "mssql",
        "sqlserver"
    ],
    "license": "MIT",
    "main": "lib/adapter.js",
    "maintainers": [
        {
            "name": "tjwebb"
        }
    ],
    "name": "sails-sqlserver",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/cnect/sails-sqlserver.git"
    },
    "scripts": {
        "test": "node test/integration/runner -R spec -b"
    },
    "version": "0.10.8",
    "waterlineAdapter": {
        "type": "sails-sqlserver",
        "interfaces": [
            "semantic",
            "queryable",
            "associations"
        ],
        "waterlineVersion": "~0.10.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
