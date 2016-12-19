# 简介

这里介绍的也将会是我们前端项目中所使用的,所以必须了解下面介绍的语言  

编程语言分为三部分
 - 脚本语言 javascript
 - 布局语言 html
 - 样式语言 css

基本上熟悉上面几门语言就已经足够搭建网页了,而且在很久一段时间他们互相配合,在互联网上运行良好,但是现代的浏览器发展飞快,网页承载的功能也越来越多,复杂性直线上升,所以社区出现了一些非常好的思路和工具来解决这些问题.下面我们来讨论一下

# javascript
javascript不是一门精心设计过的语言,所以在面对大型工程的时候,有它的一些限制,所以社区提供了更好的解决方案,提前能让我们使用上下一代精心设计过的javascript,这里就是ES6出场的时候了
# es6
es6是下一代的javascript,提供了更多好用的特征,当前文档不会详细说明,这里仅仅是提供参考资料  

最好的入门资料：ECMAScript 6入门 [点击阅读](http://es6.ruanyifeng.com/)  
![es6](./img/es6.jpg "ECMAScript 6入门")  

babel终端,可以在上面尝试es6的语法
[点击尝试](http://babeljs.io/repl/)

![babel-repl](./img/babel.jpg)  

基本上你看懂了上面那本书,顺便在终端里面实验一下就能大致了解es6了,值得注意的是,上面的书籍中,提供了[一节](http://es6.ruanyifeng.com/#docs/style),这是一份编程风格指南,也是一份很好的项目常用es6特征清单,希望能多看几遍

# html
html并没有什么好说的,这是前端工程师的基本功

# jade

> 已改名为pug

jade是一种以"精简"的思维写html的方式,以缩进的方式表示标签之间的嵌套方式,这样能让你少些一写代码,而且代码看起来也比较精炼简洁. 

[官网](https://pugjs.org/api/getting-started.html) 

你也可以试玩一下 

[点击访问](http://naltatis.github.io/jade-syntax-docs/#id-classes) 


# jsx  

当前文档不会详细说明,这里提供一些资料,jsx可能会涉及到react的东西,其实我们只要关注语法就行,因为我们是在vue.js中少量的使用jsx,所以有个大概的了解就可以了  

JSX语法 [点击阅读](https://zhuanlan.zhihu.com/p/21246327)

# css
css是控制页面样式的利器,这里也不会讨论太多css的东西,但是有一些在项目中用到的东西得熟悉一下,比如flexbox布局系统
这里提供参考资料  

 - Flex 布局教程：语法篇 [点击访问](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html?utm_source=tuicool)  
 - Flex 布局教程：实例篇 [点击访问](http://www.ruanyifeng.com/blog/2015/07/flex-examples.html)

# less
css不支持变量函数这些编程语言的特征,所以我们使用less来增强css,项目中我们大量使用less来解决css不足的地方,这里提供参考资料  
 - less中文网 [点击访问](http://lesscss.cn/)  
 - less即学即用(视频教程) [点击观看](less即学即用)  
 - 用less写个新浪微博(视频教程) [点击观看](http://www.imooc.com/learn/61)

# 其他
## yaml  
 我们使用yaml来取代json作为系统的配置文件,yaml是专门为了配置而创建的语言,提供更友好直观的配置方式,所以有必要了解一下,这里提供参考资料  
  - YAML 语言教程 [点击访问](http://www.ruanyifeng.com/blog/2016/07/yaml.html?f=tt)  
  - YAML 在线demo [点击尝试](http://nodeca.github.io/js-yaml/)  

当然你只要在用到的时候,来看一下即可,因为我们项目中没有使用太多特征,不需要花费太多时间去精通
