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

### prerender-spa-plugin
![Downloads](https://img.shields.io/npm/dm/prerender-spa-plugin.svg)

可以在编译时渲染单页应用。

安装：`npm i -D prerender-spa-plugin`

[用法](https://github.com/webpack-contrib/prerender-spa-plugin#usage)

[Github 地址](https://github.com/chrisvfritz/prerender-spa-plugin)


---

## 统计插件

### webpack-bundle-analyzer
![Coverage Status]()
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
