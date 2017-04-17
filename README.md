# test coverage for  [cassandra-driver (v3.2.0)](https://github.com/datastax/nodejs-driver#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cassandra-driver.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cassandra-driver) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cassandra-driver.svg)](https://travis-ci.org/npmtest/node-npmtest-cassandra-driver)
#### DataStax Node.js Driver for Apache Cassandra

[![NPM](https://nodei.co/npm/cassandra-driver.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cassandra-driver)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cassandra-driver/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cassandra-driver/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cassandra-driver/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cassandra-driver/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cassandra-driver/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cassandra-driver/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cassandra-driver/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cassandra-driver/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cassandra-driver/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cassandra-driver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cassandra-driver/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cassandra-driver/build/test-report.html](https://npmtest.github.io/node-npmtest-cassandra-driver/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cassandra-driver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cassandra-driver/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cassandra-driver/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cassandra-driver/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cassandra-driver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cassandra-driver/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cassandra-driver/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cassandra-driver/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "DataStax"
    },
    "bugs": {
        "url": "https://groups.google.com/a/lists.datastax.com/forum/#!forum/nodejs-driver-user"
    },
    "dependencies": {
        "long": "^2.2.0"
    },
    "description": "DataStax Node.js Driver for Apache Cassandra",
    "devDependencies": {
        "mocha": ">= 1.14.0",
        "mocha-appveyor-reporter": ">= 0.2.1",
        "mocha-jenkins-reporter": ">= 0.1.9",
        "mocha-multi": ">= 0.8.0",
        "rewire": ">= 2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3da538829a8b47b63d6fcc16aaa93ce32ca2cb2d",
        "tarball": "https://registry.npmjs.org/cassandra-driver/-/cassandra-driver-3.2.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "385c453fae2eb06c02e5015c4fbb688c016e19cd",
    "homepage": "https://github.com/datastax/nodejs-driver#readme",
    "keywords": [
        "cassandra",
        "cql",
        "cql3",
        "connection",
        "pool",
        "datastax",
        "nosql",
        "driver",
        "database"
    ],
    "license": "Apache-2.0",
    "maintainers": [
        {
            "name": "jorgebay"
        }
    ],
    "name": "cassandra-driver",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/datastax/nodejs-driver.git"
    },
    "scripts": {
        "ci": "mocha test/unit test/integration/short -R mocha-multi",
        "ci_unit": "mocha test/unit -R mocha-multi",
        "eslint": "eslint lib test --ignore-pattern '/lib/types/integer.js'",
        "test": "mocha test/unit -R spec -t 5000"
    },
    "version": "3.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
