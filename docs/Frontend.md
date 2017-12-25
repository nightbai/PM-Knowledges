# 前端主要的框架语言

## javascript

JavaScript一种直译式脚本语言，是一种动态类型、弱类型、基于原型的语言，内置支持类型。它的解释器被称为JavaScript引擎，为浏览器的一部分，广泛用于客户端的脚本语言，最早是在HTML（标准通用标记语言下的一个应用）网页上使用，用来给HTML网页增加动态功能。

`基本特点`

JavaScript是一种属于网络的脚本语言,已经被广泛用于Web应用开发,常用来为网页添加各式各样的动态功能,为用户提供更流畅美观的浏览效果。通常JavaScript脚本是通过嵌入在HTML中来实现自身的功能的。

- 是一种解释性脚本语言（代码不进行预编译）。

- 主要用来向HTML（标准通用标记语言下的一个应用）页面添加交互行为。

- 可以直接嵌入HTML页面，但写成单独的js文件有利于结构和行为的分离。 

- 跨平台特性，在绝大多数浏览器的支持下，可以在多种平台下运行（如Windows、Linux、Mac、Android、iOS等）。

Javascript脚本语言同其他语言一样，有它自身的基本数据类型，表达式和算术运算符及程序的基本程序框架。Javascript提供了四种基本的数据类型和两种特殊数据类型用来处理数据和文字。而变量提供存放信息的地方，表达式则可以完成较复杂的信息处理。

`日常用途`

- 嵌入动态文本于HTML页面。

- 对浏览器事件做出响应。

- 读写HTML元素。 

- 在数据被提交到服务器之前验证数据。

- 检测访客的浏览器信息。

- 控制cookies，包括创建和修改等。 

- 基于Node.js技术进行服务器端编程。

`参考`

百度百科，[javascript](https://baike.baidu.com/item/javascript/321142?fr=aladdin&fromid=10687961&fromtitle=js)

W3school,[JavaScript 简介](http://www.w3school.com.cn/js/js_intro.asp)

## Vue.js

`定义`

Vue.js是一个构建数据驱动的web界面的渐进式框架。

`目标`

它的目标是通过尽可能简单的API实现响应的数据绑定和组合的视图组件。

`核心`

是一个响应的数据绑定系统。

`内容`

它不仅易于上手，还便于与第三方库或既有项目整合。另一方面，当与单文件组件和Vue生态系统支持的库结合使用时，Vue也完全能够为复杂的单页应用程序提供驱动。即在与相关工具和支持库一起使用时，Vue.js 也能完美地驱动复杂的单页应用。

与其他重量级框架不同的是，Vue采用自底向上增量开发的设计。Vue的核心库只关注视图层，并且非常容易学习，非常容易与其它库或已有项目整合。另一方面，Vue完全有能力驱动采用单文件组件和Vue生态系统支持的库开发的复杂单页应用。

`特点`

（1） 简洁 （2） 轻量 （3）快速 （4） 数据驱动 （5） 模块友好 （6） 组件化

`参考资料`

劳卜，[前端开发之走进Vue.js](http://www.cnblogs.com/luozhihao/p/6014098.html)

## React.js

`起源`

React起源于Facebook的内部项目，因为该公司对市场上所有JavaScript MVC框架，都不满意，就决定自己写一套，用来架设Instagram的网站。做出来以后，发现这套东西很好用，就在2013年5月开源了。由于React的设计思想极其独特，属于革命性创新，性能出众，代码逻辑却非常简单。所以，越来越多的人开始关注和使用，认为它可能是将来Web开发的主流工具。

`认识`

- React不是一个完整的MVC框架，不擅长于和动态数据打交道，因此它不同于，也替代不了常规的MVC框架，最多可以认为是MVC中的V（View），甚至React并不非常认可MVC开发模式；

- React的服务器端Render能力只能算是一个锦上添花的功能，并不是其核心出发点，事实上React官方站点几乎没有提及其在服务器端的应用；

- 有人拿React和Web Component相提并论，但两者并不是完全的竞争关系，你完全可以用React去开发一个真正的Web Component；

- React不是一个新的模板语言，JSX只是一个表象，没有JSX的React也能工作。

- React很擅长于处理组件化的页面，在页面上搭组件的形式有点像搭乐高一样，因此用上React的项目需求常规为界面组件化。另外React只支持到IE8+，就天朝的情况，是否使用React还是得稍微斟酌一番。

`特点`

- 虚拟DOM —— 在DOM树的状态需要发生变化时，虚拟DOM机制会将同一Event loop前后的DOM树进行对比（自然通过一系列高效的算法），如果俩个DOM树存在不一样的地方，那么React仅仅会针对这些不一样的区域（DOM diff）来进行响应的DOM修改，从而实现最高效的DOM操作和渲染。

- 组件可嵌套，而且，可以模版化嘛 —— 其实在React里提及的“组件”，常规是一些可封装起来、复用的UI模块，说的接地气了可以理解为“带有细粒度UI功能的部分DOM区域”。然后我们可以把这些组件层层嵌套起来使用（当然这样组件间会存在依赖关系）。

`参考`

VaJoy / 蓝邦珏， [ReactJS入门（一）—— 初步认识React](https://www.cnblogs.com/vajoy/p/4591274.html)

雲霏霏,[一看就懂的ReactJs入门教程-精华版](https://www.cnblogs.com/yunfeifei/p/4486125.html)

## Angularjs

`背景`

AngularJS诞生于2009年，由Misko Hevery等人创建，后为Google所收购。是一款优秀的前端JS框架，已经被用于Google的多款产品当中。

`特性`

AngularJS有着诸多特性，最为核心的是：MVC、模块化、自动化双向数据绑定、语义化标签、依赖注入等等。

`内容`

AngularJS是一个JavaScript框架。它是一个以JavaScript编写的库，它可通过<script>标签添加到HTML页面。

AngularJS通过指令扩展了HTML，且通过表达式绑定数据到HTML。

AngularJS是以一个JavaScript文件形式发布的，可通过script标签添加到网页中。

`理念`

Angular信奉的是，当组建视图(UI)同时又要写软件逻辑时，声明式的代码会比命令式的代码好得多，尽管命令式的代码非常适合用来表述业务逻辑。

`优点`

1. 模板功能强大丰富，并且是声明式的，自带了丰富的Angular指令；

2. 是一个比较完善的前端MVC框架，包含模板，数据双向绑定，路由，模块化，服务，过滤器，依赖注入等所有功能；

3. 自定义Directive，比jQuery插件还灵活，但是需要深入了解Directive的一些特性，简单的封装容易，复杂一点官方没有提供详细的介绍文档，我们可以通过阅读源代码来找到某些我们需要的东西，如：在directive使用 $parse；

4. ng模块化比较大胆的引入了Java的一些东西（依赖注入），能够很容易的写出可复用的代码，对于敏捷开发的团队来说非常有帮助，我们的项目从上线到目前，UI变化很大，在摸索中迭代产品，但是js的代码基本上很少改动。

5. 补充：Angular支持单元测试和e2e-testing。

`缺点`

1. 验证功能错误信息显示比较薄弱，需要写很多模板标签，没有jQuery Validate方便，所以我们自己封装了验证的错误信息提示，详细参考 why520crazy/w5c-validator-angular · GitHub ；

2. ngView只能有一个，不能嵌套多个视图，虽然有 angular-ui/ui-router · GitHub 解决，但是貌似ui-router 对于URL的控制不是很灵活，必须是嵌套式的（也许我没有深入了解或者新版本有改进）；

3. 对于特别复杂的应用场景，貌似性能有点问题，特别是在Windows下使用chrome浏览器，不知道是内存泄漏了还是什么其他问题，没有找到好的解决方案，奇怪的是在IE10下反而很快，对此还在观察中；

4. 这次从1.0.X升级到1.2.X，貌似有比较大的调整，没有完美兼容低版本，升级之后可能会导致一个兼容性的BUG，具体详细信息参考官方文档 AngularJS ，对应的中文版本：Angular 1.0到1.2 迁移指南

5. ng提倡在控制器里面不要有操作DOM的代码，对于一些jQuery 插件的使用，如果想不破坏代码的整洁性，需要写一些directive去封装插件，但是现在有很多插件的版本已经支持Angular了，如：jQuery File Upload Demo

6. Angular 太笨重了，没有让用户选择一个轻量级的版本，当然1.2.X后，Angular也在做一些更改，比如把route，animate等模块独立出去，让用户自己去选择。

`参考资料`

阿辉，[AngularJS------认识AngularJS](https://www.cnblogs.com/netxiaohui/p/5765463.html)

葡萄城控件技术团队，[带你走近AngularJS - 基本功能介绍](https://www.cnblogs.com/powertoolsteam/p/angularjs-introdection.html)

## Angular,react和Vue的比较

`参考资料`

[前端学习总结（二十三）——前端框架天下三分：Angular React 和 Vue的比较](http://blog.csdn.net/haoshidai/article/details/52346865)

[react.js,angular.js,vue.js学习哪个好？](https://www.zhihu.com/question/39943474)

[前端框架Vue、angular、React的优点和缺点](https://www.cnblogs.com/Zcqian/p/6843787.html)


