# object-translate

![Node](https://img.shields.io/node/v/object-translate.svg?style=flat-square)
[![NPM](https://img.shields.io/npm/v/object-translate.svg?style=flat-square)](https://www.npmjs.com/package/object-translate)
[![Travis](https://img.shields.io/travis/danielo515/object-translate/master.svg?style=flat-square)](https://travis-ci.org/danielo515/object-translate)
[![David](https://img.shields.io/david/danielo515/object-translate.svg?style=flat-square)](https://david-dm.org/danielo515/object-translate)
[![Coverage Status](https://img.shields.io/coveralls/danielo515/object-translate.svg?style=flat-square)](https://coveralls.io/github/danielo515/object-translate)

> Easily turn objects into other objects. Easy and composable

### Usage

```js
import objectTranslate from 'object-translate';

```

### Installation

Install via [yarn](https://github.com/yarnpkg/yarn)

	yarn add object-translate (--dev)

or npm

	npm install object-translate (--save-dev)


### configuration

You can pass in extra options as a configuration object (➕ required, ➖ optional, ✏️ default).

```js
import objectTranslate from 'object-translate';

```

➖ **property** ( type ) ` ✏️ default `
<br/> 📝 description
<br/> ❗️ warning
<br/> ℹ️ info
<br/> 💡 example

### methods

#### #name

```js
objectTranslate

```

### Examples

See [`example`](example/script.js) folder or the [runkit](https://runkit.com/danielo515/object-translate) example.

### Builds

If you don't use a package manager, you can [access `object-translate` via unpkg (CDN)](https://unpkg.com/object-translate/), download the source, or point your package manager to the url.

`object-translate` is compiled as a collection of [CommonJS](http://webpack.github.io/docs/commonjs.html) modules & [ES2015 modules](http://www.2ality.com/2014/0
  -9/es6-modules-final.html) for bundlers that support the `jsnext:main` or `module` field in package.json (Rollup, Webpack 2)

The `object-translate` package includes precompiled production and development [UMD](https://github.com/umdjs/umd) builds in the [`dist` folder](https://unpkg.com/object-translate/dist/). They can be used directly without a bundler and are thus compatible with many popular JavaScript module loaders and environments. You can drop a UMD build as a [`<script>` tag](https://unpkg.com/object-translate) on your page. The UMD builds make `object-translate` available as a `window.objectTranslate` global variable.

### License

The code is available under the [MIT](LICENSE) license.

### Contributing

We are open to contributions, see [CONTRIBUTING.md](CONTRIBUTING.md) for more info.

### Misc

This module was created using [generator-module-boilerplate](https://github.com/duivvv/generator-module-boilerplate).
