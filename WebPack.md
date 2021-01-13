#### `webpack`进化史

> `WebPack` **V1**

- 编译、打包
- `HMR`（模块热更新）
    - 不刷新页面就可以看到页面进行修改
- 代码分割
- 文件处理

> `WebPack` **V2**

- `Tree Shaking`
    - 打包以后代码更小，引入包中没有使用的模块不进行打包
- `ES module`
    - **V1**中需要使用`babel`才可以使用`export / import` 
- 动态`Import`
- 新的文档

> `WebPack` **V3**

- `Scope Hoisting（作用域提升）`

- `Magic Comments（配合动态import使用）`
    - 可以自定义打包以后的文件名

> `Tree Shaking`

**包含 js 与 css**

- 优化代码

- 使用`Webpack.optimize.uglifyJS`进行优化
- 使用`babel`（可选）

- 使用`Purify css`

#### 提升`webpack`打包速度

- 1: 跟上技术的迭代（Node、Npm、Yarn）
- 2: 在尽可能少的模块上引用`Loader`
- 3：`resolve`参数合理配置
- 4：`Plugin`尽可能精简并确保可靠
- 5：使用`DIIPlugin`提升打包速度
- 6：控制包文件大小
- 7：`thread-loader` 、 `parallel-webpack`、`happypack`多进程打包
- 8：合理使用`sourceMap`
- 9: 结合`stats`分析打包结果
- 10：开发环境内存编译
- 11： 


