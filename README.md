# npmdoc-nativescript-cardview

#### basic api documentation for  [nativescript-cardview (v1.3.2)](https://github.com/bradmartin/nativescript-cardview)  [![npm package](https://img.shields.io/npm/v/npmdoc-nativescript-cardview.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nativescript-cardview) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nativescript-cardview.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nativescript-cardview)

#### A NativeScript plugin for Material Design CardView component.

[![NPM](https://nodei.co/npm/nativescript-cardview.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nativescript-cardview)

- [https://npmdoc.github.io/node-npmdoc-nativescript-cardview/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nativescript-cardview/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nativescript-cardview/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nativescript-cardview/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nativescript-cardview/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nativescript-cardview/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brad Martin",
        "url": "https://github.com/bradmartin"
    },
    "bugs": {
        "url": "https://github.com/bradmartin/nativescript-cardview/issues"
    },
    "contributors": [
        {
            "name": "Nathanael Anderson",
            "url": "https://github.com/nathanaela"
        },
        {
            "name": "Nathanael Walker",
            "url": "https://github.com/NathanWalker"
        },
        {
            "name": "Ned",
            "url": "https://github.com/manijak"
        },
        {
            "name": "Vladimir Nani",
            "url": "https://github.com/vladimirnani"
        },
        {
            "name": "Stanimira Vlaeva",
            "url": "https://github.com/sis0k0"
        },
        {
            "name": "Eddy Verbruggen",
            "url": "https://github.com/EddyVerbruggen"
        }
    ],
    "dependencies": {},
    "description": "A NativeScript plugin for Material Design CardView component.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "8fa9f5aeb8611ca5bb8d6125f45c7a4beb702011",
        "tarball": "https://registry.npmjs.org/nativescript-cardview/-/nativescript-cardview-1.3.2.tgz"
    },
    "gitHead": "4051f65b65920cba73942af0d38ed06b6013a83c",
    "homepage": "https://github.com/bradmartin/nativescript-cardview",
    "keywords": [
        "NativeScript",
        "native",
        "script",
        "TypeScript",
        "javascript",
        "Card",
        "android",
        "ios",
        "CardView",
        "Material Design",
        "bradmartin",
        "Thorum"
    ],
    "license": "Apache-2.0",
    "main": "cardview",
    "maintainers": [
        {
            "name": "bradmartin"
        },
        {
            "name": "nathanaela"
        },
        {
            "name": "walkerrunpdx"
        }
    ],
    "name": "nativescript-cardview",
    "nativescript": {
        "platforms": {
            "android": "2.3.0",
            "ios": "2.3.0"
        }
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bradmartin/nativescript-cardview.git"
    },
    "scripts": {
        "build": "tsc",
        "demo.android": "npm run preparedemo; cd demo; tns emulate android",
        "demo.ios": "npm run preparedemo; cd demo; tns emulate ios",
        "preparedemo": "npm run build; cd demo; tns plugin remove nativescript-cardview; tns plugin add ..; tns install",
        "setup": "cd demo; npm install; cd ..; npm run build; cd demo; tns plugin add ..; cd .."
    },
    "typings": "index.d.ts",
    "version": "1.3.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
