# Summary

* [丰富的选项合并策略](src/丰富的选项合并策略.md)
  * [1.1 Vue的引入](src/丰富的选项合并策略.md#11-vue的引入)
    * [1.1.1 基础使用](src/丰富的选项合并策略.md#111-基础使用)
    * [1.1.2 Vue构造器](src/丰富的选项合并策略.md#112-vue构造器)
    * [1.1.3 定义原型属性方法](src/丰富的选项合并策略.md#113-定义原型属性方法)
    * [1.1.4 定义静态属性方法](src/丰富的选项合并策略.md#114-定义静态属性方法)
  * [1.2 构造器的默认选项](src/丰富的选项合并策略.md#12-构造器的默认选项)
  * [1.3 选项检验](src/丰富的选项合并策略.md#13-选项检验)
    * [1.3.1 components规范检验](src/丰富的选项合并策略.md#131-components规范检验)
    * [1.3.2 props规范检验](src/丰富的选项合并策略.md#132-props规范检验)
    * [1.3.3 inject的规范校验](src/丰富的选项合并策略.md#133-inject的规范校验)
    * [1.3.4 directive的规范校验](src/丰富的选项合并策略.md#134-directive的规范校验)
    * [1.3.5 函数缓存](src/丰富的选项合并策略.md#135-函数缓存)
  * [1.4 子类构造器](src/丰富的选项合并策略.md#14-子类构造器)
  * [1.5 合并策略](src/丰富的选项合并策略.md#15-合并策略)
    * [1.5.1 默认策略](src/丰富的选项合并策略.md#151-默认策略)
  * [1.6 常规选项的合并](src/丰富的选项合并策略.md#16-常规选项的合并)
    * [1.6.1 el的合并](src/丰富的选项合并策略.md#161-el的合并)
    * [1.6.2 data合并](src/丰富的选项合并策略.md#162-data合并)
  * [1.7 自带资源选项合并](src/丰富的选项合并策略.md#17-自带资源选项合并)
  * [1.8 生命周期钩子函数的合并](src/丰富的选项合并策略.md#18-生命周期钩子函数的合并)
  * [1.9 watch选项合并](src/丰富的选项合并策略.md#19-watch选项合并)
  * [1.10 props methods inject computed合并](src/丰富的选项合并策略.md#110-props-methods-inject-computed合并)
  * [1.11 小结](src/丰富的选项合并策略.md#111-小结)
* [基础的数据代理检测](src/基础的数据代理检测.md)
  * [2.1 数据代理的含义](src/基础的数据代理检测.md#21-数据代理的含义)
    * [2.1.1 Object.defineProperty](src/基础的数据代理检测.md#211-objectdefineproperty)
    * [2.1.2 Proxy](src/基础的数据代理检测.md#212-proxy)
  * [2.2 initProxy](src/基础的数据代理检测.md#22-initproxy)
    * [2.2.1 触发代理](src/基础的数据代理检测.md#221-触发代理)
    * [2.2.2 数据过滤](src/基础的数据代理检测.md#222-数据过滤)
  * [2.3 小结](src/基础的数据代理检测.md#23-小结)
* [实例挂载流程和模板编译](src/实例挂载流程和模板编译.md)
  * [3.1 Runtime Only VS Runtime + Compiler](src/实例挂载流程和模板编译.md#31-runtime-only-vs-runtime--compiler)
    * [3.1.1 Runtime + Compiler](src/实例挂载流程和模板编译.md#311-runtime--compiler)
    * [3.1.2 Runtime Only](src/实例挂载流程和模板编译.md#312-runtime-only)
  * [3.2 实例挂载的基本思路](src/实例挂载流程和模板编译.md#32-实例挂载的基本思路)
    * [3.2.1 流程图](src/实例挂载流程和模板编译.md#321-流程图)
    * [3.2.2 代码分析](src/实例挂载流程和模板编译.md#322-代码分析)
  * [3.3 模板编译](src/实例挂载流程和模板编译.md#33-模板编译)
    * [3.3.1 template的三种写法](src/实例挂载流程和模板编译.md#331-template的三种写法)
    * [3.3.2 编译流程图解](src/实例挂载流程和模板编译.md#332-编译流程图解)
    * [3.3.3 逻辑解析](src/实例挂载流程和模板编译.md#333-逻辑解析)
  * [3.4 小结](src/实例挂载流程和模板编译.md#34-小结)
* [完整渲染流程](src/完整渲染流程.md)
  * [4.1 Virtual DOM](src/完整渲染流程.md#41-virtual-dom)
    * [4.1.1 浏览器的渲染流程](src/完整渲染流程.md#411-浏览器的渲染流程)
    * [4.1.2 缓冲层-虚拟DOM](src/完整渲染流程.md#412-缓冲层-虚拟dom)
  * [4.2 Vnode](src/完整渲染流程.md#42-vnode)
    * [4.2.1 Vnode构造函数](src/完整渲染流程.md#421-vnode构造函数)
    * [4.2.2 创建Vnode注释节点](src/完整渲染流程.md#422-创建vnode注释节点)
    * [4.2.3 创建Vnode文本节点](src/完整渲染流程.md#423-创建vnode文本节点)
    * [4.2.4 克隆vnode](src/完整渲染流程.md#424-克隆vnode)
  * [4.3 Virtual DOM的创建](src/完整渲染流程.md#43-virtual-dom的创建)
    * [4.3.1 数据规范检测](src/完整渲染流程.md#431-数据规范检测)
    * [4.3.2 子节点children规范化](src/完整渲染流程.md#432-子节点children规范化)
    * [4.3.4 实际场景](src/完整渲染流程.md#434-实际场景)
  * [4.4 虚拟Vnode映射成真实DOM](src/完整渲染流程.md#44-虚拟vnode映射成真实dom)
  * [4.5 小结](src/完整渲染流程.md#45-小结)
* [组件基础剖析](src/组件基础剖析.md)
  * [5.1 组件两种注册方式](src/组件基础剖析.md#51-组件两种注册方式)
    * [5.1.1 全局注册](src/组件基础剖析.md#511-全局注册)
    * [5.1.2 局部注册](src/组件基础剖析.md#512-局部注册)
    * [5.1.3 注册过程](src/组件基础剖析.md#513-注册过程)
  * [5.2 组件Vnode创建](src/组件基础剖析.md#52-组件vnode创建)
    * [5.2.1 Vnode创建流程图](src/组件基础剖析.md#521-vnode创建流程图)
    * [5.2.2 具体流程分析](src/组件基础剖析.md#522-具体流程分析)
    * [5.2.3 局部注册和全局注册的区别](src/组件基础剖析.md#523-局部注册和全局注册的区别)
  * [5.3 组件Vnode渲染真实DOM](src/组件基础剖析.md#53-组件vnode渲染真实dom)
    * [5.3.1 真实节点渲染流程图](src/组件基础剖析.md#531-真实节点渲染流程图)
    * [5.3.2 具体流程分析](src/组件基础剖析.md#532-具体流程分析)
  * [5.4 建立组件联系](src/组件基础剖析.md#54-建立组件联系)
  * [5.5 小结](src/组件基础剖析.md#55-小结)
* [组件高级用法](src/组件高级用法.md)
  * [6.1 异步组件](src/组件高级用法.md#61-异步组件)
    * [6.1.1 使用场景](src/组件高级用法.md#611-使用场景)
    * [6.1.2 工厂函数](src/组件高级用法.md#612-工厂函数)
    * [6.1.3 流程分析](src/组件高级用法.md#613-流程分析)
    * [6.1.4 Promise异步组件](src/组件高级用法.md#614-promise异步组件)
    * [6.1.5 高级异步组件](src/组件高级用法.md#615-高级异步组件)
    * [6.1.6 wepack异步组件用法](src/组件高级用法.md#616-wepack异步组件用法)
  * [6.2 函数式组件](src/组件高级用法.md#62-函数式组件)
    * [6.2.1 使用场景](src/组件高级用法.md#621-使用场景)
    * [6.2.2 源码分析](src/组件高级用法.md#622-源码分析)
  * [6.3 小结](src/组件高级用法.md#63-小结)
* [深入响应式系统构建-上](src/深入响应式系统构建-上.md)
  * [7.1 数据初始化](src/深入响应式系统构建-上.md#71-数据初始化)
  * [7.2 initProps](src/深入响应式系统构建-上.md#72-initprops)
    * [7.2.1 props的命名规范](src/深入响应式系统构建-上.md#721-props的命名规范)
    * [7.2.2 响应式数据props](src/深入响应式系统构建-上.md#722-响应式数据props)
  * [7.3 initMethods](src/深入响应式系统构建-上.md#73-initmethods)
  * [7.4 initData](src/深入响应式系统构建-上.md#74-initdata)
  * [7.5 initComputed](src/深入响应式系统构建-上.md#75-initcomputed)
  * [7.6 极简风的响应式系统](src/深入响应式系统构建-上.md#76-极简风的响应式系统)
    * [7.6.1 框架搭建](src/深入响应式系统构建-上.md#761-框架搭建)
    * [7.6.2 设置响应式对象 - Observer](src/深入响应式系统构建-上.md#762-设置响应式对象---observer)
    * [7.6.3 依赖本身 - Watcher](src/深入响应式系统构建-上.md#763-依赖本身---watcher)
    * [7.6.4 依赖管理 - Dep](src/深入响应式系统构建-上.md#764-依赖管理---dep)
    * [7.6.5 依赖管理过程 - defineReactive](src/深入响应式系统构建-上.md#765-依赖管理过程---definereactive)
    * [7.6.6 结果](src/深入响应式系统构建-上.md#766-结果)
  * [7.7 小结](src/深入响应式系统构建-上.md#77-小结)
* [深入响应式系统构建-中](src/深入响应式系统构建-中.md)
  * [7.8 相关概念](src/深入响应式系统构建-中.md#78-相关概念)
  * [7.9 data](src/深入响应式系统构建-中.md#79-data)
    * [7.9.1 问题思考](src/深入响应式系统构建-中.md#791-问题思考)
    * [7.9.2 依赖收集](src/深入响应式系统构建-中.md#792-依赖收集)
    * [7.9.3 派发更新](src/深入响应式系统构建-中.md#793-派发更新)
  * [7.10 computed](src/深入响应式系统构建-中.md#710-computed)
    * [7.10.1 依赖收集](src/深入响应式系统构建-中.md#7101-依赖收集)
    * [7.10.2 派发更新](src/深入响应式系统构建-中.md#7102-派发更新)
  * [7.11 小结](src/深入响应式系统构建-中.md#711-小结)
* [深入响应式系统构建-下](src/深入响应式系统构建-下.md)
  * [7.12 数组检测](src/深入响应式系统构建-下.md#712-数组检测)
    * [7.12.1 数组方法的重写](src/深入响应式系统构建-下.md#7121-数组方法的重写)
    * [7.12.2 依赖收集](src/深入响应式系统构建-下.md#7122-依赖收集)
    * [7.12.3 派发更新](src/深入响应式系统构建-下.md#7123-派发更新)
  * [7.13 对象检测异常](src/深入响应式系统构建-下.md#713-对象检测异常)
  * [7.14 nextTick](src/深入响应式系统构建-下.md#714-nexttick)
    * [7.14.1 事件循环机制](src/深入响应式系统构建-下.md#7141-事件循环机制)
    * [7.14.2 基本实现](src/深入响应式系统构建-下.md#7142-基本实现)
    * [7.14.3 使用场景](src/深入响应式系统构建-下.md#7143-使用场景)
  * [7.15 watch](src/深入响应式系统构建-下.md#715-watch)
    * [7.15.1 依赖收集](src/深入响应式系统构建-下.md#7151-依赖收集)
    * [7.15.2 派发更新](src/深入响应式系统构建-下.md#7152-派发更新)
  * [7.16 小结](src/深入响应式系统构建-下.md#716-小结)
* [来，跟我一起实现diff算法](src/来，跟我一起实现diff算法.md)
  * [8.1 创建基础类](src/来，跟我一起实现diff算法.md#81-创建基础类)
  * [8.2 创建Vnode](src/来，跟我一起实现diff算法.md#82-创建vnode)
  * [8.3 模拟渲染过程](src/来，跟我一起实现diff算法.md#83-模拟渲染过程)
    * [8.3.1 createVnode](src/来，跟我一起实现diff算法.md#831-createvnode)
    * [8.3.2 createElement](src/来，跟我一起实现diff算法.md#832-createelement)
    * [8.3.3 setAttr](src/来，跟我一起实现diff算法.md#833-setattr)
  * [8.4 diff算法实现](src/来，跟我一起实现diff算法.md#84-diff算法实现)
    * [8.4.1 diffVnode](src/来，跟我一起实现diff算法.md#841-diffvnode)
    * [8.4.2 _sameVnode](src/来，跟我一起实现diff算法.md#842-samevnode)
    * [8.4.3 generateElm](src/来，跟我一起实现diff算法.md#843-generateelm)
    * [8.4.4 patchVnode](src/来，跟我一起实现diff算法.md#844-patchvnode)
    * [8.4.5 updateChildren](src/来，跟我一起实现diff算法.md#845-updatechildren)
  * [8.5 diff算法优化](src/来，跟我一起实现diff算法.md#85-diff算法优化)
  * [8.6 问题思考](src/来，跟我一起实现diff算法.md#86-问题思考)
* [揭秘Vue的事件机制](src/揭秘Vue的事件机制.md)
  * [9.1 模板编译](src/揭秘Vue的事件机制.md#91-模板编译)
  * [9.2 代码生成](src/揭秘Vue的事件机制.md#92-代码生成)
  * [9.3 事件绑定](src/揭秘Vue的事件机制.md#93-事件绑定)
  * [9.4 自定义事件](src/揭秘Vue的事件机制.md#94-自定义事件)
    * [9.4.1 模板编译](src/揭秘Vue的事件机制.md#941-模板编译)
    * [9.4.2 代码生成](src/揭秘Vue的事件机制.md#942-代码生成)
    * [9.4.3 子组件实例](src/揭秘Vue的事件机制.md#943-子组件实例)
    * [9.4.4 事件api](src/揭秘Vue的事件机制.md#944-事件api)
* [vue插槽，你想了解的都在这里](src/vue插槽，你想了解的都在这里.md)
  * [10.1 普通插槽](src/vue插槽，你想了解的都在这里.md#101-普通插槽)
    * [10.1.1 基础用法](src/vue插槽，你想了解的都在这里.md#1011-基础用法)
    * [10.1.2 组件挂载原理](src/vue插槽，你想了解的都在这里.md#1012-组件挂载原理)
    * [10.1.3 父组件处理](src/vue插槽，你想了解的都在这里.md#1013-父组件处理)
    * [10.1.4 子组件流程](src/vue插槽，你想了解的都在这里.md#1014-子组件流程)
  * [10.2 具有后备内容的插槽](src/vue插槽，你想了解的都在这里.md#102-具有后备内容的插槽)
  * [10.3 具名插槽](src/vue插槽，你想了解的都在这里.md#103-具名插槽)
    * [10.3.1 模板编译的差别](src/vue插槽，你想了解的都在这里.md#1031-模板编译的差别)
    * [10.3.2 父组件vnode生成阶段](src/vue插槽，你想了解的都在这里.md#1032-父组件vnode生成阶段)
    * [10.3.3 子组件渲染Vnode过程](src/vue插槽，你想了解的都在这里.md#1033-子组件渲染vnode过程)
    * [10.3.4 子组件渲染真实dom](src/vue插槽，你想了解的都在这里.md#1034-子组件渲染真实dom)
  * [10.4 作用域插槽](src/vue插槽，你想了解的都在这里.md#104-作用域插槽)
    * [10.4.1 父组件编译阶段](src/vue插槽，你想了解的都在这里.md#1041-父组件编译阶段)
    * [10.4.2 子组件渲染](src/vue插槽，你想了解的都在这里.md#1042-子组件渲染)
    * [10.4.3 思考](src/vue插槽，你想了解的都在这里.md#1043-思考)
* [你真的了解v-model的语法糖了吗](src/你真的了解v-model的语法糖了吗.md)
  * [11.1 表单绑定](src/你真的了解v-model的语法糖了吗.md#111-表单绑定)
    * [11.1.1 基础使用](src/你真的了解v-model的语法糖了吗.md#1111-基础使用)
    * [11.1.2 AST树的解析](src/你真的了解v-model的语法糖了吗.md#1112-ast树的解析)
    * [11.1.3 render函数生成](src/你真的了解v-model的语法糖了吗.md#1113-render函数生成)
    * [11.1.4 patch真实节点](src/你真的了解v-model的语法糖了吗.md#1114-patch真实节点)
    * [11.1.5 语法糖的背后](src/你真的了解v-model的语法糖了吗.md#1115-语法糖的背后)
  * [11.2 组件使用v-model](src/你真的了解v-model的语法糖了吗.md#112-组件使用v-model)
* [动态组件的深入分析](src/动态组件的深入分析.md)
  * [12.1 动态组件](src/动态组件的深入分析.md#121-动态组件)
    * [12.1.1 基本用法](src/动态组件的深入分析.md#1211-基本用法)
    * [12.1.2 AST解析](src/动态组件的深入分析.md#1212-ast解析)
    * [12.1.3 render函数](src/动态组件的深入分析.md#1213-render函数)
    * [12.1.4 普通组件和动态组件的对比](src/动态组件的深入分析.md#1214-普通组件和动态组件的对比)
    * [12.1.5 疑惑](src/动态组件的深入分析.md#1215-疑惑)
  * [12.2 内联模板](src/动态组件的深入分析.md#122-内联模板)
  * [12.3 内置组件](src/动态组件的深入分析.md#123-内置组件)
    * [12.3.1 构造器定义组件](src/动态组件的深入分析.md#1231-构造器定义组件)
    * [12.3.2 注册内置组件](src/动态组件的深入分析.md#1232-注册内置组件)
* [彻底搞懂Vue中keep-alive的魔法-上](src/彻底搞懂Vue中keep-alive的魔法-上.md)
  * [13.1 基本用法](src/彻底搞懂Vue中keep-alive的魔法-上.md#131-基本用法)
  * [13.2 从模板编译到生成vnode](src/彻底搞懂Vue中keep-alive的魔法-上.md#132-从模板编译到生成vnode)
  * [13.3 初次渲染](src/彻底搞懂Vue中keep-alive的魔法-上.md#133-初次渲染)
    * [13.3.1 流程图](src/彻底搞懂Vue中keep-alive的魔法-上.md#1331-流程图)
    * [13.3.2 内置组件选项](src/彻底搞懂Vue中keep-alive的魔法-上.md#1332-内置组件选项)
    * [13.3.3 缓存vnode](src/彻底搞懂Vue中keep-alive的魔法-上.md#1333-缓存vnode)
    * [13.3.4 真实节点的保存](src/彻底搞懂Vue中keep-alive的魔法-上.md#1334-真实节点的保存)
  * [13.4 抽象组件](src/彻底搞懂Vue中keep-alive的魔法-上.md#134-抽象组件)
* [彻底搞懂Vue中keep-alive的魔法-下](src/彻底搞懂Vue中keep-alive的魔法-下.md)
  * [13.5 准备工作](src/彻底搞懂Vue中keep-alive的魔法-下.md#135-准备工作)
    * [13.5.1 基础使用](src/彻底搞懂Vue中keep-alive的魔法-下.md#1351-基础使用)
    * [13.5.2 流程图](src/彻底搞懂Vue中keep-alive的魔法-下.md#1352-流程图)
  * [13.6 流程分析](src/彻底搞懂Vue中keep-alive的魔法-下.md#136-流程分析)
    * [13.6.1 重新渲染组件](src/彻底搞懂Vue中keep-alive的魔法-下.md#1361-重新渲染组件)
    * [13.6.2 重用缓存组件](src/彻底搞懂Vue中keep-alive的魔法-下.md#1362-重用缓存组件)
    * [13.6.3 真实节点的替换](src/彻底搞懂Vue中keep-alive的魔法-下.md#1363-真实节点的替换)
  * [13.7 生命周期](src/彻底搞懂Vue中keep-alive的魔法-下.md#137-生命周期)
    * [13.7.1 deactivated](src/彻底搞懂Vue中keep-alive的魔法-下.md#1371-deactivated)
    * [13.7.2 activated](src/彻底搞懂Vue中keep-alive的魔法-下.md#1372-activated)
  * [13.8 缓存优化 - LRU](src/彻底搞懂Vue中keep-alive的魔法-下.md#138-缓存优化---lru)


