# bee-checkbox
[![npm version](https://img.shields.io/npm/v/bee-checkbox.svg)](https://www.npmjs.com/package/bee-checkbox)
[![Build Status](https://img.shields.io/travis/tinper-bee/bee-checkbox/master.svg)](https://travis-ci.org/tinper-bee/bee-checkbox)
[![Coverage Status](https://coveralls.io/repos/github/tinper-bee/bee-checkbox/badge.svg?branch=master)](https://coveralls.io/github/tinper-bee/bee-checkbox?branch=master)

复选框

## 使用
使用单独的bee-checkbox包
#### 组件引入
先进行下载bee-checkbox包

```
npm install --save bee-checkbox
```
组件调用
```js
import Checkbox from 'bee-checkbox';

React.render(<div>
        <Checkbox colors="primary" />
</div>, document.getElementById('target'));

```
#### 样式引入
- 可以使用link引入dist目录下bee-checkbox.css
```
<link rel="stylesheet" href="./node_modules/build/bee-checkbox.css">
```
- 可以在js中import样式
```js
import "./node_modules/src/Checkbox.scss"
//或是
import "./node_modules/build/bee-checkbox.css"
```


## API
|参数|说明|类型|默认值|
|---|----|---|------|
|className|类名|string|-|
|color|one of: `primary` `success` `info` `error`  `warning` `dark`|string|''|
|disabled|是否可用|bool|false|
|onChange|监听改变|function|-|
|defaultChecked|默认是否选中|bool|false|
|checked|是否选中|bool|-|
|indeterminate|部分选中|bool|-|
|onDoubleClick|双击事件|function|function(checked, event){}|
|onClick|单击事件|function|function(event){}|

#### 开发调试

```sh
$ git clone https://github.com/tinper-bee/bee-checkbox
$ cd bee-checkbox
$ npm install
$ npm run dev
```
