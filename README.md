# hello vue2.0!
如何使用VUE，vue的插件，vue的组件化开发

## 主流框架分析
 ![主流框架](http://upload-images.jianshu.io/upload_images/1058258-31ed9b6eb0f19aee.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240/format/jpg)
 
* 纯模板引擎：最少的就是纯模板引擎，只管状态到界面的映射。

* React和Vue：其实这两者都是非常专注的只做状态到界面映射，以及组件。

* Backbone：它会给你多一些架构上指导，比如它会让你分层  MVC。

* Angular：它做的事情就更多，它有自己的路由，这些都会包含在里面。

* Ember：相比Angular，Ember做得就更加彻底，Ember信奉的是约定优于配置，它会将一切都帮你设计好打包好，你就开箱用就可以了。

* Meteor：Meteor只是一个极端，它是从前到后全都包含，从前端到数据层到数据库，全都帮你打包好。
<hr/>
<hr/>

## vue 特点！
* 易用
* 灵活
* 高效
* 文档易读

## *渐进式开发框架* 
![渐进式开发框架](http://upload-images.jianshu.io/upload_images/1058258-fa85b93e56d6c1c6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240/format/jpg)

*  避免手动直接的操控DOM DOM随着状态变化而变化 
 
*  组件系统 
 
*  客户端路由 大型的单页面
 
*  大规模应用，多个组件之间共享统一状态，
 
*  构建工具 提升前端开发效率

## VUE的渲染 虚拟DOM
* 模版语法
>> 贴近HTML 结构观察， css书写
* jsx语法
>> 拥有javascript特性 有利于逻辑判断
* vue本身的响应式系统，追踪数据变化
>> ![追踪响应](http://upload-images.jianshu.io/upload_images/1058258-7e643d8fd694ed18.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240/format/jpg);
## 生命周期
 ![vue生命周期](https://cn.vuejs.org/images/lifecycle.png)
## 组件系统 
>> 把UI的结构映射到组件数

>> props用于父子组件之间的通信,数据单向传递，子组件数据相对独立

>> <a target="_blank"  href="https://cn.vuejs.org/v2/guide/single-file-components.html">单文件组件</a> 基于构建工具
## 客户端路由
## 路由管理<a target="_blank" href="http://router.vuejs.org/zh-cn/"> vue-router </a>
## vue的状态管理工具 <a target="_blank" href="https://vuex.vuejs.org/zh-cn/">vuex</a>
## 构建工具 vue cli
## 服务端渲染
## <a href="https://github.com/vuejs/vue-hackernews-2.0">官方例子</a>
