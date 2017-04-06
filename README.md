# api documentation for  [babylon (v6.16.1)](https://babeljs.io/)  [![npm package](https://img.shields.io/npm/v/npmdoc-babylon.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-babylon) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-babylon.svg)](https://travis-ci.org/npmdoc/node-npmdoc-babylon)
#### A JavaScript parser

[![NPM](https://nodei.co/npm/babylon.png?downloads=true)](https://www.npmjs.com/package/babylon)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babylon/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-babylon_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babylon/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-babylon/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-babylon/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sebastian McKenzie",
        "email": "sebmck@gmail.com"
    },
    "ava": {
        "files": [
            "test/*.js"
        ],
        "source": [
            "src/**/*.js",
            "bin/**/*.js"
        ]
    },
    "bin": {
        "babylon": "./bin/babylon.js"
    },
    "bugs": {
        "url": "https://github.com/babel/babylon/issues"
    },
    "contributors": [
        {
            "name": "List of Acorn contributors. Updated before every release."
        },
        {
            "name": "Adrian Rakovsky"
        },
        {
            "name": "Alistair Braidwood"
        },
        {
            "name": "Andres Suarez"
        },
        {
            "name": "Aparajita Fishman"
        },
        {
            "name": "Arian Stolwijk"
        },
        {
            "name": "Artem Govorov"
        },
        {
            "name": "Brandon Mills"
        },
        {
            "name": "Charles Hughes"
        },
        {
            "name": "Conrad Irwin"
        },
        {
            "name": "David Bonnet"
        },
        {
            "name": "Forbes Lindesay"
        },
        {
            "name": "Gilad Peleg"
        },
        {
            "name": "impinball"
        },
        {
            "name": "Ingvar Stepanyan"
        },
        {
            "name": "Jesse McCarthy"
        },
        {
            "name": "Jiaxing Wang"
        },
        {
            "name": "Joel Kemp"
        },
        {
            "name": "Johannes Herr"
        },
        {
            "name": "Jürg Lehni"
        },
        {
            "name": "keeyipchan"
        },
        {
            "name": "Kevin Kwok"
        },
        {
            "name": "krator"
        },
        {
            "name": "Marijn Haverbeke"
        },
        {
            "name": "Martin Carlberg"
        },
        {
            "name": "Mathias Bynens"
        },
        {
            "name": "Mathieu 'p01' Henri"
        },
        {
            "name": "Max Schaefer"
        },
        {
            "name": "Max Zerzouri"
        },
        {
            "name": "Mihai Bazon"
        },
        {
            "name": "Mike Rennie"
        },
        {
            "name": "Nick Fitzgerald"
        },
        {
            "name": "Oskar Schöldström"
        },
        {
            "name": "Paul Harper"
        },
        {
            "name": "Peter Rust"
        },
        {
            "name": "PlNG"
        },
        {
            "name": "r-e-d"
        },
        {
            "name": "Rich Harris"
        },
        {
            "name": "Sebastian McKenzie"
        },
        {
            "name": "zsjforcn"
        }
    ],
    "dependencies": {},
    "description": "A JavaScript parser",
    "devDependencies": {
        "ava": "^0.17.0",
        "babel-cli": "^6.14.0",
        "babel-eslint": "^7.0.0",
        "babel-helper-fixtures": "^6.9.0",
        "babel-plugin-external-helpers": "^6.18.0",
        "babel-plugin-istanbul": "^3.0.0",
        "babel-plugin-transform-flow-strip-types": "^6.14.0",
        "babel-preset-es2015": "^6.14.0",
        "babel-preset-stage-0": "^6.5.0",
        "chalk": "^1.1.3",
        "codecov": "^1.0.1",
        "cross-env": "^2.0.0",
        "eslint": "^3.7.1",
        "eslint-config-babel": "^6.0.0",
        "eslint-plugin-flowtype": "^2.20.0",
        "flow-bin": "^0.38.0",
        "nyc": "^10.0.0",
        "rimraf": "^2.5.4",
        "rollup": "^0.41.0",
        "rollup-plugin-babel": "^2.6.1",
        "rollup-plugin-node-resolve": "^2.0.0",
        "unicode-9.0.0": "~0.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "30c5a22f481978a9e7f8cdfdf496b11d94b404d3",
        "tarball": "https://registry.npmjs.org/babylon/-/babylon-6.16.1.tgz"
    },
    "files": [
        "bin",
        "lib"
    ],
    "gitHead": "539d345d9b23ae1331a4beb13e2de91b0a9020e6",
    "greenkeeper": {
        "ignore": [
            "cross-env"
        ]
    },
    "homepage": "https://babeljs.io/",
    "keywords": [
        "babel",
        "javascript",
        "parser",
        "babylon"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "amasad",
            "email": "amjad.masad@gmail.com"
        },
        {
            "name": "danez",
            "email": "daniel@tschinder.de"
        },
        {
            "name": "gabelevi",
            "email": "gabelevi@gmail.com"
        },
        {
            "name": "hzoo",
            "email": "hi@henryzoo.com"
        },
        {
            "name": "jmm",
            "email": "npm-public@jessemccarthy.net"
        },
        {
            "name": "loganfsmyth",
            "email": "loganfsmyth@gmail.com"
        },
        {
            "name": "sebmck",
            "email": "sebmck@gmail.com"
        },
        {
            "name": "thejameskyle",
            "email": "me@thejameskyle.com"
        }
    ],
    "name": "babylon",
    "nyc": {
        "include": [
            "src/**/*.js",
            "bin/**/*.js"
        ],
        "sourceMap": false,
        "instrument": false
    },
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/babel/babylon.git"
    },
    "scripts": {
        "build": "npm run clean && rollup -c",
        "changelog": "git log 'git describe --tags --abbrev=0'..HEAD --pretty=format:' * %s (%an)' | grep -v 'Merge pull request'",
        "clean": "rimraf lib",
        "coverage": "nyc report --reporter=json && codecov -f coverage/coverage-final.json",
        "flow": "flow",
        "lint": "eslint src bin",
        "prepublish": "cross-env BABEL_ENV=production npm run build",
        "preversion": "npm run test && npm run changelog",
        "test": "npm run lint && npm run flow && npm run build -- -m && npm run test-only",
        "test-ci": "nyc npm run test-only",
        "test-only": "ava",
        "watch": "npm run clean && cross-env BABEL_ENV=watch babel src --out-dir lib --watch"
    },
    "version": "6.16.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module babylon](#apidoc.module.babylon)
1.  [function <span class="apidocSignatureSpan">babylon.</span>parse (input, options)](#apidoc.element.babylon.parse)
1.  [function <span class="apidocSignatureSpan">babylon.</span>parseExpression (input, options)](#apidoc.element.babylon.parseExpression)
1.  object <span class="apidocSignatureSpan">babylon.</span>tokTypes



# <a name="apidoc.module.babylon"></a>[module babylon](#apidoc.module.babylon)

#### <a name="apidoc.element.babylon.parse"></a>[function <span class="apidocSignatureSpan">babylon.</span>parse (input, options)](#apidoc.element.babylon.parse)
- description and source-code
```javascript
function parse(input, options) {
  return new Parser(options, input).parse();
}
```
- example usage
```shell
...
Heavily based on [acorn](https://github.com/marijnh/acorn) and [acorn-jsx](https://github.com/RReverser/acorn-jsx),
thanks to the awesome work of [@RReverser](https://github.com/RReverser) and [@marijnh](https://github.com/marijnh).

Significant diversions are expected to occur in the future such as streaming, EBNF definitions, sweet.js integration, interspatial
 parsing and more.

## API

### 'babylon.parse(code, [options])'

### 'babylon.parseExpression(code, [options])'

'parse()' parses the provided 'code' as an entire ECMAScript program, while
'parseExpression()' tries to parse a single Expression with performance in
mind. When in doubt, use '.parse()'.
...
```

#### <a name="apidoc.element.babylon.parseExpression"></a>[function <span class="apidocSignatureSpan">babylon.</span>parseExpression (input, options)](#apidoc.element.babylon.parseExpression)
- description and source-code
```javascript
function parseExpression(input, options) {
  var parser = new Parser(options, input);
  if (parser.options.strictMode) {
    parser.state.strict = true;
  }
  return parser.getExpression();
}
```
- example usage
```shell
...

Significant diversions are expected to occur in the future such as streaming, EBNF definitions, sweet.js integration, interspatial
 parsing and more.

## API

### 'babylon.parse(code, [options])'

### 'babylon.parseExpression(code, [options])'

'parse()' parses the provided 'code' as an entire ECMAScript program, while
'parseExpression()' tries to parse a single Expression with performance in
mind. When in doubt, use '.parse()'.

### Options
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
