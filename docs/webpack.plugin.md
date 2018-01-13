# webpack 常用插件

## 内置插件

### DefinePlugin

写入环境变量，用于区分开发和生产环境。

[用法](https://webpack.js.org/plugins/define-plugin/)

### DefinePlugin

从输出文件中抽离每个入口公用的模块，放在额外的 js 文件中。

[用法](https://webpack.js.org/plugins/commons-chunk-plugin/)

---

## 其他插件

### webpack-bundle-analyzer
![Coverage Status]()
![Downloads](https://img.shields.io/npm/dm/webpack-bundle-analyzer.svg)

用于查看在输出的包中，每个依赖占用的大小。

安装：`npm install --save-dev webpack-bundle-analyzer`

[用法](https://github.com/webpack-contrib/webpack-bundle-analyzer#usage-as-a-plugin)

[Github 地址](https://github.com/webpack-contrib/webpack-bundle-analyzer)

### HTML Webpack Plugin
![Coverage Status]()
![Downloads](https://img.shields.io/npm/dm/html-webpack-plugin.svg)

创建页面使用的 html 文件，自动添加依赖。

安装：`npm install html-webpack-plugin --save-dev`

[用法](https://github.com/jantimon/html-webpack-plugin#basic-usage)

[Github 地址](https://github.com/jantimon/html-webpack-plugin)

### copy-webpack-plugin
![Coverage Status]()
![Downloads](https://img.shields.io/npm/dm/copy-webpack-plugin.svg)

用于复制文件到输出文件中。

安装：`npm install copy-webpack-plugin --save-dev`

[用法](https://github.com/webpack-contrib/copy-webpack-plugin#usage)

[Github 地址](https://github.com/webpack-contrib/copy-webpack-plugin)
