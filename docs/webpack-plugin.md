# webpack 常用插件

## 构建时功能插件

### DefinePlugin

写入环境变量，用于区分开发和生产环境。

[用法](https://webpack.js.org/plugins/define-plugin/)

### HTML Webpack Plugin
![Downloads](https://img.shields.io/npm/dm/html-webpack-plugin.svg)

创建页面使用的 html 文件，自动添加依赖。

安装：`npm i -D html-webpack-plugin`

[用法](https://github.com/jantimon/html-webpack-plugin#basic-usage)

[Github 地址](https://github.com/jantimon/html-webpack-plugin)

### copy-webpack-plugin
![Downloads](https://img.shields.io/npm/dm/copy-webpack-plugin.svg)

用于复制文件到输出文件中。

安装：`npm i -D copy-webpack-plugin`

[用法](https://github.com/webpack-contrib/copy-webpack-plugin#usage)

[Github 地址](https://github.com/webpack-contrib/copy-webpack-plugin)

### extract-text-webpack-plugin
![Downloads](https://img.shields.io/npm/dm/extract-text-webpack-plugin.svg)

从包中提取 CSS 文本到文件中。

安装：`npm i -D extract-text-webpack-plugin`

[用法](https://github.com/webpack-contrib/extract-text-webpack-plugin#usage)

[Github 地址](https://github.com/webpack-contrib/extract-text-webpack-plugin)

### compression-webpack-plugin
![Downloads](https://img.shields.io/npm/dm/compression-webpack-plugin.svg)

创建资源的压缩版本。

安装：`npm i -D compression-webpack-plugin`

[用法](https://github.com/webpack-contrib/compression-webpack-plugin#usage)

[Github 地址](https://github.com/webpack-contrib/compression-webpack-plugin)

---

## 输出优化插件

### commons-chunk-plugin

从输出文件中抽离每个入口公用的模块，放在额外的 js 文件中。

[用法](https://webpack.js.org/plugins/commons-chunk-plugin/)

### uglifyjs-webpack-plugin
![Downloads](https://img.shields.io/npm/dm/uglifyjs-webpack-plugin.svg)

压缩 JS 文件。

安装：`npm i -D uglifyjs-webpack-plugin`

[用法](https://github.com/webpack-contrib/uglifyjs-webpack-plugin#usage)

[Github 地址](https://github.com/webpack-contrib/uglifyjs-webpack-plugin)

### optimize-css-assets-webpack-plugin
![Downloads](https://img.shields.io/npm/dm/optimize-css-assets-webpack-plugin.svg)

优化，最小化 css 资源文件，使用 cssnano。使用 extract-text 插件只是将 css 文本提取到 css 文件中，它并没有做更多的优化。

安装：`npm i -D optimize-css-assets-webpack-plugin`

[用法](https://github.com/NMFR/optimize-css-assets-webpack-plugin#configuration)

[Github 地址](https://github.com/NMFR/optimize-css-assets-webpack-plugin)

### prerender-spa-plugin
![Downloads](https://img.shields.io/npm/dm/prerender-spa-plugin.svg)

可以在编译时渲染单页应用。

安装：`npm i -D prerender-spa-plugin`

[用法](https://github.com/webpack-contrib/prerender-spa-plugin#usage)

[Github 地址](https://github.com/chrisvfritz/prerender-spa-plugin)

## OccurrenceOrderPlugin（默认启用）

按照模块和块发生的次数来赋给它们 id，可以得到更短的 id，来减小整个文件的大小。

[介绍](https://github.com/webpack/docs/wiki/list-of-plugins#occurrenceorderplugin)
[默认加载](https://www.webpackjs.com/guides/migrating/#-occurrenceorderplugin)

## DedupePlugin（移除）

去除重复的文件。

[介绍](https://github.com/webpack/docs/wiki/list-of-plugins#optimize)
[去除](https://www.webpackjs.com/guides/migrating/#-dedupeplugin)

---

## 构建时优化插件

### DllPlugin 和 DllReferencePlugin

用于加快构建速度。

[用法](https://webpack.js.org/plugins/dll-plugin/#dllplugin)

---

## 开发用插件

### HotModuleReplacementPlugin

在开发服务器中开启模块热替换。

[介绍](https://github.com/webpack/docs/wiki/list-of-plugins#hotmodulereplacementplugin)
[热替换](https://webpack.js.org/guides/hot-module-replacement/)
[API](https://github.com/webpack/docs/wiki/hot-module-replacement)

### NoEmitOnErrorsPlugin

如果使用了这个插件，当编译时发生错误，webpack 会直接跳过 emit 阶段。

[介绍](https://webpack.js.org/plugins/no-emit-on-errors-plugin/)

### FriendlyErrorsPlugin
![Downloads](https://img.shields.io/npm/dm/friendly-errors-webpack-plugin.svg)

使错误的输出更友好，提供更好的开发体验。

安装：`npm i -D friendly-errors-webpack-plugin`

[用法](https://github.com/geowarin/friendly-errors-webpack-plugin#basic-usage)

[Github 地址](https://github.com/geowarin/friendly-errors-webpack-plugin)

---

## 统计插件

### webpack-bundle-analyzer
![Downloads](https://img.shields.io/npm/dm/webpack-bundle-analyzer.svg)

用于查看在输出的包中，每个依赖占用的大小。

安装：`npm install --save-dev webpack-bundle-analyzer`

[用法](https://github.com/webpack-contrib/webpack-bundle-analyzer#usage-as-a-plugin)

[Github 地址](https://github.com/webpack-contrib/webpack-bundle-analyzer)

### stats-webpack-plugin
![Downloads](https://img.shields.io/npm/dm/stats-webpack-plugin.svg)

用于将构建时的统计信息写入文件。

安装：`npm install --save-dev stats-webpack-plugin`

[用法](https://github.com/unindented/stats-webpack-plugin/#usage)

[Github 地址](https://github.com/unindented/stats-webpack-plugin/)
