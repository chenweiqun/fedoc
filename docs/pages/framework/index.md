# 简介
技术框架有利于加快我们项目开发速度,我们前端技术框架都是基于vue.js中的,所以主要讨论vue.js,并且会围绕vue.js
周边的配套工具就行.
# Vue全家桶
## vue.js
![vue](./img/vue.jpg "vue.js")  


我们并不讨论vue.js是什么,能做什么等这些官网已经说得很清楚的问题,这些是需要自己去讨论,我们只讨论vue哪些概念是
一定要理解并消化的.因为你会在项目中不断的实践并会一直出现在你的代码中,反复使用.

 - 响应式数据(数据绑定,计算属性)
 - 组件系统(生命周期,slot,prop,异步组件,事件通讯)
 - 列表渲染  

参考链接:  
官网:[点击访问](http://cn.vuejs.org/)  
指南:[点击访问](http://cn.vuejs.org/v2/guide/)  
API:[点击访问](http://cn.vuejs.org/v2/api/)  

## vue-router
vue-router是vue官方提供的路由框架,因为我们项目遵守前后端分离的原则,所以整个项目都是一个单页,而根据url路由来
组织页面就成了一种必要,所以我们直接使用vue-router来作为我们的路由库

参考链接:
参考文档:[点击访问](https://router.vuejs.org/zh-cn/index.html)  


## vue-resource
> 注意：官方已经不再投入精力维护

# vuex

一个组件之间的状态管理工具,解决跨组件数据通讯的问题,顺便提供了时间旅行的功能.

参考文档 [点击访问](http://localhost:35729/livereload.js)  
扩展知识 flux架构

# 第三方库
 - [element-ui](http://element.eleme.io/#/zh-CN/component/installation) (饿了么出品的UI库,适用于后台开发)
 - [jquery](http://jquery.cuishifeng.cn/) (不解释了)
 - [lodash](http://www.css88.com/doc/lodash/) (javascript辅助函数库)
 - [moment](http://momentjs.cn/) (操作时间的库)
 - [store](https://github.com/marcuswestin/store.js) (操作本地数据的库,对localStrong和cookie的封装)
 - [axios](https://github.com/mzabriskie/axios) (vue作者推荐取代vue-resource的网络请求库)
 - [weui](https://github.com/weui/weui/wiki) (微信官方出品的css库)
