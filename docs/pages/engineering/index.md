# npm
npm是一个包管理工具,可以管理js的依赖库,jquery,vue这些库都可以通过npm安装,下面介绍一些常见的用法.
基本命令行
**package.json**
主要分几个重要的部分
 - script 自定义执行命令
 - devDependencies 开发阶段依赖
 - dependencies 项目直接依赖

基本使用
```shell
npm install 安装package.json里面的所有依赖
npm install <packageName> -g 安装在全局,就是说可以在全局执行此命令行
npm install <packageName> --save 安装在项目直接依赖
npm install <packageName> --save-dev 安装在开发阶段依赖
```
** 注意事项 ** 因为npm的服务器是外国的,所以经常不稳定,安装依赖要很久,推荐使用淘宝的cnpm
先安装cnpm
```shell
npm install -g cnpm --registry=https://registry.npm.taobao.org
```
以后使用的时候,把npm命令全部换成cnpm就行了

# webpack
webpack是一个前端打包工具,核心思想是一切都是资源,可以被加载进来,通过各种加载器和插件完成一系列的工作

[官网](http://webpack.github.io/)   
[官网-中文](https://webpack.vuefe.cn/index/)  
[资料汇总](https://gold.xitu.io/entry/580f63a20ce4630031964ec8)

# babel
转译工具,可以提前使用es6/7的语法
# postcss
转换css
# vue单文件
vue官方推荐写模块的方式,把模版,样式,脚本全部集中到一个文件,需要使用webpack的vue-loader插件

[文档](https://gold.xitu.io/entry/580f63a20ce4630031964ec8) 
