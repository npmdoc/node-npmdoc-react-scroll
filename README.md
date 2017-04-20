# npmdoc-react-scroll

#### api documentation for  [react-scroll (v1.5.2)](https://github.com/fisshy/react-scroll)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-scroll.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-scroll) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-scroll.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-scroll)

#### A scroll component for React.js

[![NPM](https://nodei.co/npm/react-scroll.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-scroll)

- [https://npmdoc.github.io/node-npmdoc-react-scroll/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-scroll/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-scroll/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-scroll/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-scroll/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-scroll/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-scroll",
    "version": "1.5.2",
    "description": "A scroll component for React.js",
    "main": "modules",
    "repository": {
        "type": "git",
        "url": "https://github.com/fisshy/react-scroll.git"
    },
    "scripts": {
        "examples": "webpack-dev-server --config examples/webpack.config.js --no-info --content-base examples",
        "build": "babel modules -d build/npm/modules --ignore '**/__tests__/**' && gulp",
        "clean": "rm -rf build/npm/modules",
        "test": "karma start"
    },
    "homepage": "https://github.com/fisshy/react-scroll",
    "bugs": "https://github.com/fisshy/react-scroll/issues",
    "authors": [
        "Joachim Karlsson"
    ],
    "license": "MIT",
    "tags": [
        "react",
        "scroll"
    ],
    "keywords": [
        "react",
        "react-component",
        "scroll",
        "scroller",
        "scrolls"
    ],
    "dependencies": {
        "object-assign": "^4.1.1",
        "prop-types": "^15.5.8"
    },
    "devDependencies": {
        "babel-cli": "^6.24.1",
        "babel-core": "^6.24.1",
        "babel-loader": "^6.4.1",
        "babel-preset-es2015": "^6.24.1",
        "babel-preset-react": "^6.24.1",
        "expect": "^1.20.2",
        "gulp": "^3.9.1",
        "gulp-concat": "^2.6.1",
        "karma": "^1.6.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-mocha": "^1.3.0",
        "karma-mocha-reporter": "^2.2.3",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^2.0.3",
        "mocha": "^3.2.0",
        "react": "^15.5.4",
        "react-addons-test-utils": "^15.5.1",
        "react-dom": "^15.5.4",
        "webpack": "^2.4.1",
        "webpack-dev-server": "^2.4.2"
    },
    "peerDependencies": {
        "react": "^15.5.4",
        "react-dom": "^15.5.4"
    },
    "babel": {
        "presets": [
            "es2015",
            "react"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
