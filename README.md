#### webpack知识点

##### javaScript模块化

> 命名空间

- 1: 库名.类别名.方法名

```js
  var NameSpace = {}
  NameSpace.type = NameSpace.type || {}
  NameSpace.type.method = function () {}
```

- 2: 使用`YUI` 命名规则

> `commonJS`

- 一个文件为一个模块
- 通过`module.exports`暴露模块接口
- 通过`require`引入模块 
- 同步执行

```js
// 引用模块
const EventEmitter = require('events').EventEmitter;
const mixin = require('./mixin');

// 暴露出一个方法
exports = module.exports = createApplication;

```

> `AMD` 、 `CMD` 、 `UMD`

> `ES6 module`

- 一个文件一个模块

- `export` 暴露出 、 `import` 引入

```js
// 引入
import {a, b} from './text.js'
// 暴露出
export let myVar = '';
export default function() {};  

```

##### css 模块化

- `CSS`设计模式
    - `OOCSS`
    - `SMACSS`
    - `Atomic CSS`
    - `MCSS`
    - `AMCSS`
    - `BEM`

- `CSS Modules`

