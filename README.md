# boot

> desc

> 构建系统基于 https://github.com/fast-flow/boot

- Online: https://fast-flow.github.io/boot/
- Other version: https://github.com/fast-flow/boot/releases

<div id="demo"></div>

- [example](./example/)
- [doc](./doc/)
- [test](./test/)

````js
require('boot/lib/index.css')
var React = require('react')
var ReactDOM = require('react-dom')
var Some = require('boot')
ReactDOM.render(<Some />, document.getElementById('demo'))
````

## Btn

<div id="demoBtn"></div>

````js
var React = require('react')
var ReactDOM = require('react-dom')
var Btn = require('boot/lib/btn')
ReactDOM.render(<Btn />, document.getElementById('demoBtn'))
````

## 参与开发 - development

```shell
npm i -g fis3 --registry=https://registry.npm.taobao.org
# 安装依赖
npm run dep
# 服务器
npm run s
# 开发
npm run dev


# 构建 gh-pages 版本 到 output/
npm run gh
# 将 output/** 发布到 gh-pages 分支
npm run gh-push
# 构建 npm 要发布的代码到 output/
npm run npm
```

> For npm owner: npm publish Need to be in ./output
