# npmtest-aws-sdk

#### basic test coverage for  [aws-sdk (v2.45.0)](https://github.com/aws/aws-sdk-js)  [![npm package](https://img.shields.io/npm/v/npmtest-aws-sdk.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-aws-sdk) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-aws-sdk.svg)](https://travis-ci.org/npmtest/node-npmtest-aws-sdk)

#### AWS SDK for JavaScript

[![NPM](https://nodei.co/npm/aws-sdk.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/aws-sdk)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-aws-sdk/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-aws-sdk/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-aws-sdk/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-aws-sdk/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-aws-sdk/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-aws-sdk/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-aws-sdk/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-aws-sdk/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-aws-sdk/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-aws-sdk/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-aws-sdk/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-aws-sdk/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-aws-sdk/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-aws-sdk/build/test-report.html](https://npmtest.github.io/node-npmtest-aws-sdk/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-aws-sdk/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-aws-sdk/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-aws-sdk/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-aws-sdk/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-aws-sdk/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-aws-sdk/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-aws-sdk/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-aws-sdk/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Amazon Web Services",
        "url": "http://aws.amazon.com/"
    },
    "browser": {
        "lib/aws.js": "./lib/browser.js",
        "fs": false,
        "./global.js": "./browser.js",
        "./lib/node_loader.js": "./lib/browser_loader.js"
    },
    "browserify": {
        "transform": "./dist-tools/transform.js"
    },
    "bugs": {
        "url": "http://github.com/aws/aws-sdk-js/issues"
    },
    "contributors": [
        {
            "name": "Loren Segal"
        },
        {
            "name": "Trevor Rowe"
        }
    ],
    "dependencies": {
        "buffer": "4.9.1",
        "crypto-browserify": "1.0.9",
        "jmespath": "0.15.0",
        "querystring": "0.2.0",
        "sax": "1.2.1",
        "url": "0.10.3",
        "uuid": "3.0.1",
        "xml2js": "0.4.17",
        "xmlbuilder": "4.2.1"
    },
    "description": "AWS SDK for JavaScript",
    "devDependencies": {
        "@types/node": "^6.0.46",
        "browserify": "13.1.0",
        "chai": "*",
        "codecov": "^1.0.1",
        "coffee-script": "1.6.3",
        "coffeeify": "*",
        "cucumber": "0.5.x",
        "eslint": "1.x",
        "insert-module-globals": "^7.0.0",
        "istanbul": "*",
        "jasmine": "^2.5.3",
        "jasmine-core": "^2.5.2",
        "karma": "^1.4.1",
        "karma-jasmine": "^1.1.0",
        "karma-phantomjs-launcher": "^1.0.2",
        "mocha": "*",
        "repl.history": "*",
        "semver": "*",
        "typescript": "2.0.8",
        "uglify-js": "2.x"
    },
    "directories": {
        "lib": "lib"
    },
    "dist": {
        "shasum": "045dbd323630170968306dc849d793dbb1e4444d",
        "tarball": "https://registry.npmjs.org/aws-sdk/-/aws-sdk-2.45.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "8bc99767740a3142b8e2b4c519588260bb69d79f",
    "homepage": "https://github.com/aws/aws-sdk-js",
    "keywords": [
        "api",
        "amazon",
        "aws",
        "ec2",
        "simpledb",
        "s3",
        "sqs",
        "ses",
        "sns",
        "route53",
        "rds",
        "elasticache",
        "cloudfront",
        "fps",
        "cloudformation",
        "cloudwatch",
        "dynamodb",
        "iam",
        "swf",
        "autoscaling",
        "cloudsearch",
        "elb",
        "loadbalancing",
        "emr",
        "mapreduce",
        "importexport",
        "storagegateway",
        "workflow",
        "ebs",
        "vpc",
        "beanstalk",
        "glacier",
        "kinesis",
        "cloudtrail",
        "waf"
    ],
    "license": "Apache-2.0",
    "main": "lib/aws.js",
    "maintainers": [
        {
            "name": "aws"
        }
    ],
    "name": "aws-sdk",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/aws/aws-sdk-js.git"
    },
    "scripts": {
        "add-change": "node ./scripts/changelog/add-change.js",
        "browsertest": "rake browser:test && karma start",
        "buildertest": "mocha --compilers coffee:coffee-script -s 1000 -t 10000 dist-tools/test",
        "console": "./scripts/console",
        "coverage": "istanbul cover ./node_modules/mocha/bin/_mocha --reporter=lcovonly -- test test/json test/model test/protocol test/query test/services test/signers test/xml test/s3 test/cloudfront test/dynamodb test/polly",
        "integration": "cucumber.js",
        "lint": "eslint lib dist-tools/*.js",
        "test": "npm -s run-script lint && npm -s run-script unit && npm -s run-script buildertest && npm -s run-script browsertest && ([ -f configuration ] && npm -s run-script integration || true)",
        "testfiles": "istanbul '[ $COVERAGE ] && echo 'cover _mocha' || echo 'test mocha''",
        "tstest": "tsc -p ./ts",
        "unit": "mocha -- test test/json test/model test/protocol test/query test/services test/signers test/xml test/s3 test/cloudfront test/dynamodb test/polly"
    },
    "types": "index.d.ts",
    "typings": "index.d.ts",
    "version": "2.45.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
