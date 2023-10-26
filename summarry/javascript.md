# JavaScript题目汇总
##
- [写一个 mySetInterVal(fn, a, b),每次间隔 a,a+b,a+2b,...,a+nb 的时间，然后写一个 myClear，停止上面的 mySetInterVal](#写一个-mysetintervalfn-a-b每次间隔-aaba2b-的时间然后写一个-myclear停止上面的-mysetinterval) ✅
- [介绍防抖节流原理、区别以及应用，并用JavaScript进行实现](#介绍防抖节流原理区别以及应用并用javascript进行实现) ✅
- [对闭包的看法，为什么要用闭包？说一下闭包原理以及应用场景](#对闭包的看法为什么要用闭包说一下闭包原理以及应用场景) ✅
- [实现 lodash 的_.get](#实现-lodash-的_get) ✅
- [实现 add(1)(2)(3)](#实现-add123) ✅
- [实现链式调用](#实现链式调用) ✅
- [类数组和数组的区别，dom 的类数组如何转换成数组](#类数组和数组的区别dom-的类数组如何转换成数组) ✅
- [介绍下 promise 的特性、优缺点，内部是如何实现的，动手实现 Promise](#介绍下-promise-的特性优缺点内部是如何实现的动手实现-promise) ✅
- [实现 Promise.all](#实现-promiseall) ✅
- [手写发布订阅](#手写发布订阅) ✅
- [手写数组转树](#手写数组转树) ✅
- [手写用 ES6proxy 如何实现 arr[-1] 的访问](#手写用-es6proxy-如何实现-arr-1-的访问) ✅
- [手写实现 Array.flat()](#手写实现-arrayflat) ✅
- [大数计算如何实现](#大数计算如何实现) ✅
- [什么是深拷贝，和浅拷贝有什么区别，动手实现一个深拷贝](#什么是深拷贝和浅拷贝有什么区别动手实现一个深拷贝) ✅
- [实现一个方法判断 html 中的标签是否闭合](#实现一个方法判断-html-中的标签是否闭合) ✅
- [箭头函数和普通函数的区别](#箭头函数和普通函数的区别) ✅
- [es5 实现 isInteger](#es5-实现-isinteger) ✅
- [写出输出结果](#写出输出结果) ✅
- [手写 dom 操作，翻转 li 标签，如何处理更优](#手写-dom-操作翻转-li-标签如何处理更优) ✅
- [怎样判断一个对象是否是数组，如何处理类数组对象](#怎样判断一个对象是否是数组如何处理类数组对象) ✅
- [是否了解 glob，glob 是如何处理文件的，业界是否还有其它解决方案](#是否了解-globglob-是如何处理文件的业界是否还有其它解决方案) ✅
- [随便打开一个网页，用 JavaScript 打印所有以 s 和 h 开头的标签，并计算出标签的种类](#随便打开一个网页用-javascript-打印所有以-s-和-h-开头的标签并计算出标签的种类) ✅
- [1000*1000 的画布，上面有飞机、子弹，如何划分区域能够更有效的做碰撞检测，类似划分区域大小与碰撞检测效率的算法，说一下大致的思路](#10001000-的画布上面有飞机子弹如何划分区域能够更有效的做碰撞检测类似划分区域大小与碰撞检测效率的算法说一下大致的思路) ✅
- [移动设备安卓与 iOS 的软键盘弹出的处理方式有什么不同](#移动设备安卓与-ios-的软键盘弹出的处理方式有什么不同) ✅
- [iPhone 里面 Safari 上如果一个输入框 fixed 绝对定位在底部，当软键盘弹出的时候会有什么问题，如何解决](#iphone-里面-safari-上如果一个输入框-fixed-绝对定位在底部当软键盘弹出的时候会有什么问题如何解决) ✅
- [给定一个数组，按找到每个元素右侧第一个比它大的数字，没有的话返回-1 规则返回一个数组](#给定一个数组按找到每个元素右侧第一个比它大的数字没有的话返回-1-规则返回一个数组) ✅
- [说一说 promise，有几个状态，通过 catch 捕获到 reject 之后，在 catch 后面还能继续执行 then 方法嘛，如果能执行执行的是第几个回调函数](#说一说-promise有几个状态通过-catch-捕获到-reject-之后在-catch-后面还能继续执行-then-方法嘛如果能执行执行的是第几个回调函数) ✅
- [var、let、const 的区别](#varletconst-的区别) ✅
- [说一下 GC](#说一下-gc) ✅
- [如何实现按需加载](#如何实现按需加载) ✅
- [讲一下 import 的原理，与 require 有什么不同](#讲一下-import-的原理与-require-有什么不同) ✅
- [请实现如下的函数](#请实现如下的函数) ✅
- [是否用过 restful 接口，和其他风格的有什么区别](#是否用过-restful-接口和其他风格的有什么区别) ✅
- [说一下 get、post、put 的区别](#说一下-getpostput-的区别) ✅
- [说一下对面向对象的理解，面向对象有什么好处](#说一下对面向对象的理解面向对象有什么好处) ✅
- [类设计：使用面相对象设计一个停车场管理系](#类设计使用面相对象设计一个停车场管理系) ✅
- [实现输出一个十六进制的随机颜色(#af0128a)](#实现输出一个十六进制的随机颜色af0128a) ✅
- [手写代码实现kuai-shou-front-end=&gt;KuaiShouFrontEnd](#手写代码实现kuai-shou-front-endkuaishoufrontend) ✅
- [设计一个 Student 组件，实现输入姓名性别成绩（这三个必填），还有几个不是必填的属性，要设置默认值，点击弹出成绩](#设计一个-student-组件实现输入姓名性别成绩这三个必填还有几个不是必填的属性要设置默认值点击弹出成绩) ✅
- [设计一个函数，奇数次执行的时候打印 1，偶数次执行的时候打印 2](#设计一个函数奇数次执行的时候打印-1偶数次执行的时候打印-2) ✅
- [实现 Promise.then](#实现-promisethen) ✅
- [平时在项目开发中都做过哪些前端性能优化](#平时在项目开发中都做过哪些前端性能优化) ✅
- [给定起止日期，返回中间的所有月份](#给定起止日期返回中间的所有月份) ✅
- [输入两个字符串，输出他们中间的月份](#输入两个字符串输出他们中间的月份) ✅
- [用尽量短的代码实现一个 arrary 的链式操作，将数组中的大于 10 的值进行一个累加](#用尽量短的代码实现一个-arrary-的链式操作将数组中的大于-10-的值进行一个累加) ✅
- [简单封装一个异步 fecth，使用 async await 的方式来使用](#简单封装一个异步-fecth使用-async-await-的方式来使用) ✅
- [请写一个函数，输出出多级嵌套结构的 Object 的所有 key 值](#请写一个函数输出出多级嵌套结构的-object-的所有-key-值) ✅
- [写出打印结果，并解释为什么](#写出打印结果并解释为什么) ✅
- [动手实现一个 repeat 方法](#动手实现一个-repeat-方法) ✅
- [setTimeout 有什么缺点，和 requestAnimationFrame 有什么区别](#settimeout-有什么缺点和-requestanimationframe-有什么区别) ✅
- [versions 是一个项目的版本号列表，因多人维护，不规则，动手实现一个版本号处理函数](#versions-是一个项目的版本号列表因多人维护不规则动手实现一个版本号处理函数) ✅
- [实现一个多并发的请求](#实现一个多并发的请求) ✅
- [写出代码执行结果](#写出代码执行结果) ✅
- [按要求实现一个 sum 函数](#按要求实现一个-sum-函数) ✅
- [说一下 base64 的编码方式](#说一下-base64-的编码方式) ✅
- [改变 this 指向的方式都有哪些？](#改变-this-指向的方式都有哪些) ✅
- [说一下module.exports和exports的区别，export和export default的区别](#说一下moduleexports和exports的区别export和export-default的区别) ✅
- [number 为什么会出现精度损失，怎样避免](#number-为什么会出现精度损失怎样避免) ✅
- [实现一个函数将中文数字转成数字](#实现一个函数将中文数字转成数字) ✅
- [节流](#节流) ✅
- [如何实现 5 秒自动刷新一次页面(具体都有什么方法 reload 之类的)](#如何实现-5-秒自动刷新一次页面具体都有什么方法-reload-之类的) ✅
- [都了解哪些 ES6、ES7 的新特性，箭头函数可以被 new 吗](#都了解哪些-es6es7-的新特性箭头函数可以被-new-吗) ✅
- [说一下 JavaScript 继承都有哪些方法](#说一下-javascript-继承都有哪些方法) ✅
- [已知函数 A，要求构造⼀个函数 B 继承 A](#已知函数-a要求构造个函数-b-继承-a) ✅
- [数组和对象转换为字符串结果](#数组和对象转换为字符串结果) ✅
- [请写出以下代码的打印结果](#请写出以下代码的打印结果) ✅
- [请写出以下代码的打印结果](#请写出以下代码的打印结果-1) ✅
- [要求⽤不同⽅式对 A 进⾏改造实现 A.name 发⽣变化时⽴即执⾏ A.getName](#要求不同式对-a-进改造实现-aname-发变化时即执-agetname) ✅
- [修改以下代码，使得最后⼀⾏代码能够输出数字 0-9（最好能给多种答案）](#修改以下代码使得最后代码能够输出数字-0-9最好能给多种答案) ✅
- [请给出识别 Email 的正则表达式](#请给出识别-email-的正则表达式) ✅
- [设计 AutoComplete 组件(又叫搜索组件、自动补全组件等)时，需要考虑什么问题？](#设计-autocomplete-组件又叫搜索组件自动补全组件等时需要考虑什么问题) ✅
- [实现函数接受任意二叉树，求二叉树所有根到叶子路径组成的数字之和](#实现函数接受任意二叉树求二叉树所有根到叶子路径组成的数字之和) ✅
- [请写出一下代码的打印结果](#请写出一下代码的打印结果) ✅
- [Promise 链式调用如何实现](#promise-链式调用如何实现) ✅
- [说一下对BigInt的理解，在什么场景下会使用](#说一下对bigint的理解在什么场景下会使用) ✅
- [null 是不是一个对象，如果是，如何判断一个对象是 null，不使用 JavaScript 提供的 api 如何进行判断](#null-是不是一个对象如果是如何判断一个对象是-null不使用-javascript-提供的-api-如何进行判断) ✅
- [说一下对于堆栈的理解](#说一下对于堆栈的理解) ✅
- [[] == ![]为什么](#--为什么) ✅
- [如何把真实 dom 转变为虚拟 dom，代码实现一下](#如何把真实-dom-转变为虚拟-dom代码实现一下) ✅
- [说一下错误监控的实现，错误监控的正确使用方式，日志如何分等级](#说一下错误监控的实现错误监控的正确使用方式日志如何分等级) ✅
- [请写出以下代码执行结果](#请写出以下代码执行结果) ✅
- [请写出以下代码执行结果](#请写出以下代码执行结果-1) ✅
- [请写出以下代码执行结果](#请写出以下代码执行结果-2) ✅
- [请写出以下代码执行结果](#请写出以下代码执行结果-3) ✅
- [请写出以下代码执行结果](#请写出以下代码执行结果-4) ✅
- [请写出以下代码执行结果](#请写出以下代码执行结果-5) ✅
- [请写出以下代码执行结果](#请写出以下代码执行结果-6) ✅
- [说一下什么是死锁](#说一下什么是死锁) ✅
- [实现以下代码](#实现以下代码) ✅
- [请实现一个 cacheRequest 方法，保证发出多次同一个 ajax 请求时都能拿到数据，而实际上只发出一次请求](#请实现一个-cacherequest-方法保证发出多次同一个-ajax-请求时都能拿到数据而实际上只发出一次请求) ✅
- [实现一个函数柯里化](#实现一个函数柯里化) ✅
- [说一下对原型链的理解，画一个经典的原型链图示](#说一下对原型链的理解画一个经典的原型链图示) ✅
- [说一下 ajax/axios/fetch 的区别](#说一下-ajaxaxiosfetch-的区别) ✅
- [用 Promise 封装一个 ajax](#用-promise-封装一个-ajax) ✅
- [描述 DOM 事件捕获的具体流程](#描述-dom-事件捕获的具体流程) ✅
- [请实现$on,$emit](#请实现onemit) ✅
- [实现 bind 方法，不能使用 call、apply、bind](#实现-bind-方法不能使用-callapplybind) ✅
- [手写实现 sleep 函数](#手写实现-sleep-函数) ✅
- [请写出原生 js 如何设置元素高度](#请写出原生-js-如何设置元素高度) ✅
- [用原生 js 实现自定义事件](#用原生-js-实现自定义事件) ✅
- [如何识别出字符串中的回车并进行换行？](#如何识别出字符串中的回车并进行换行？) ✅
- [输入一个日期 返回几秒前、几小时前、几天前、几月前](#输入一个日期-返回几秒前几小时前几天前几月前) ✅
- [将 153812.7 转化为 153,812.7](#将-1538127-转化为-1538127) ✅
- [数组有哪些方法 讲讲区别跟使用场景](#数组有哪些方法-讲讲区别跟使用场景) ✅
- [讲一下函数式编程](#讲一下函数式编程) ✅
- [promise 跟 async await 的区别，使用场景](#promise-跟-async-await-的区别使用场景) ✅
- [async、await 如何进行错误捕获](#asyncawait-如何进行错误捕获) ✅
- [weak-Set、weak-Map 和 Set、Map 区别](#weak-setweak-map-和-setmap-区别) ✅
- [valueOf 与 toString 的区别](#valueof-与-tostring-的区别) ✅
- [怎么判断是一个空对象](#怎么判断是一个空对象) ✅
- [请写出下面代码的执行结果](#请写出下面代码的执行结果) ✅
- [请写出下面代码的执行结果](#请写出下面代码的执行结果-1) ✅
- [请只用数组方法和 Math.random()在一条语句的情况下，实现生成给定位数的随机数组，例如生成 10 位随机数组[1.1,102.1,2,3,8,4,90,123,11,123],数组内数字随机生成。](#请只用数组方法和-mathrandom在一条语句的情况下实现生成给定位数的随机数组例如生成-10-位随机数组11102123849012311123数组内数字随机生成) ✅
- [实现一个 setter 方法](#实现一个-setter-方法) ✅
- [setTimeout 与 setInterval 区别](#settimeout-与-setinterval-区别) ✅
- [项目中如何应用数据结构](#项目中如何应用数据结构) ✅
- [闭包的核心是什么](#闭包的核心是什么) ✅
- [写出代码输出结果](#写出代码输出结果) ✅
- [实现一个功能，发送请求 5s 时间后，如果没有数据返回，中断请求,提示错误](#实现一个功能发送请求-5s-时间后如果没有数据返回中断请求提示错误) ✅
- [什么是作用域链](#什么是作用域链) ✅
- [介绍事件冒泡、事件代理、事件捕获，以及它们的关系](#介绍事件冒泡事件代理事件捕获以及它们的关系) ✅
- [for..of 和 for...in 是否可以直接遍历对象，为什么](#forof-和-forin-是否可以直接遍历对象为什么) ✅
- [在 map 中和 for 中调用异步函数的区别](#在-map-中和-for-中调用异步函数的区别) ✅
- [gennerator yield 的作用](#gennerator-yield-的作用) ✅
- [promise 的状态有哪些](#promise-的状态有哪些) ✅
- [在 ES6 中有哪些解决异步的方法](#在-es6-中有哪些解决异步的方法) ✅
- [es6 类继承中 super 的作用](#es6-类继承中-super-的作用) ✅
- [cros 的简单请求和复杂请求的区别](#cros-的简单请求和复杂请求的区别) ✅
- [addEventListener 的第三个参数的作用](#addeventlistener-的第三个参数的作用) ✅
- [获取 id 为 netease 节点下所有的 checkbox 子元素(不用框架，注意兼容)](#获取-id-为-netease-节点下所有的-checkbox-子元素不用框架注意兼容) ✅
- [使用原型链如何实现继承](#使用原型链如何实现继承) ✅
- [如何获取一个对象的深度](#如何获取一个对象的深度) ✅
- [reduce 函数的功能，如何实现的，动手实现一下](#reduce-函数的功能如何实现的动手实现一下) ✅
- [说一下 splice 和 slice 的功能用法](#说一下-splice-和-slice-的功能用法) ✅
- [面向对象的三要素是啥？都是啥意思？](#面向对象的三要素是啥都是啥意思) ✅
- [函数中的 this 有几种](#函数中的-this-有几种) ✅
- [如何同时获取 html 中的 h1,h2,h3,h4,h5,h6 中的内容](#如何同时获取-html-中的-h1h2h3h4h5h6-中的内容) ✅
- [JavaScript 的执行流程](#javascript-的执行流程) ✅
- [Promise.resolve(obj)，obj 有几种可能](#promiseresolveobjobj-有几种可能) ✅
- [写出代码执行结果](#写出代码执行结果) ✅
- [nextTick 是在本次循环执行，还是在下次，setTimeout(() =&gt; {}, 0)呢？](#nexttick-是在本次循环执行还是在下次settimeout---0呢) ✅
- [使用正则去掉 Dom 中的内联样式](#使用正则去掉-dom-中的内联样式) ✅
- [写一个匹配 ip 地址的正则](#写一个匹配-ip-地址的正则) ✅
- [写一个匹配 Html 标签的正则](#写一个匹配-html-标签的正则) ✅
- [IOC 是啥，应用场景是啥？](#ioc-是啥应用场景是啥) ✅
- [写出代码执行的打印结果](#写出代码执行的打印结果) ✅
- [实现函数](#实现函数) ✅
- [怎么实现 this 对象的深拷贝](#怎么实现-this-对象的深拷贝) ✅
- [使用 canvas 绘图时如何组织成通用组件](#使用-canvas-绘图时如何组织成通用组件) ✅
- [表单可以跨域吗](#表单可以跨域吗) ✅
- [搜索请求如何处理？搜索请求中文如何请求？](#搜索请求如何处理搜索请求中文如何请求) ✅
- [介绍观察者模式](#介绍观察者模式) ✅
- [介绍中介者模式](#介绍中介者模式) ✅
- [观察者和订阅-发布的区别，各自用在哪里](#观察者和订阅-发布的区别各自用在哪里) ✅
- [通过什么做到并发请求](#通过什么做到并发请求) ✅
- [介绍 service worker](#介绍-service-worker) ✅
- [介绍事件代理以及优缺点，主要解决什么问题](#介绍事件代理以及优缺点主要解决什么问题) ✅
- [介绍下 this 的各种情况](#介绍下-this-的各种情况) ✅
- [前端如何控制管理路由](#前端如何控制管理路由) ✅
- [使用路由时出现问题如何解决](#使用路由时出现问题如何解决) ✅
- [JavaScript 异步解决方案的发展历程以及优缺点](#javascript-异步解决方案的发展历程以及优缺点) ✅
- [介绍 AST（Abstract Syntax Tree）抽象语法树](#介绍-astabstract-syntax-tree抽象语法树) ✅
- [对 async、await 的理解，内部原理是怎样的？](#对-asyncawait-的理解内部原理是怎样的) ✅
- [== 和 ===的区别，什么情况下用相等==](#-和-的区别什么情况下用相等) ✅
- [bind、call、apply 的区别](#bindcallapply-的区别) ✅
- [介绍下原型链](#介绍下原型链) ✅
- [介绍暂时性死区](#介绍暂时性死区) ✅
- [ES6 中的 map 和原生的对象有什么区别](#es6-中的-map-和原生的对象有什么区别) ✅
- [对纯函数的理解](#对纯函数的理解) ✅
- [介绍 JSX](#介绍-jsx) ✅
- [如何设计一个 localStorage，保证数据的时效性](#如何设计一个-localstorage保证数据的时效性) ✅
- [实现 sum 方法，使 sum(x)(y),sum(x,y)返回的结果相同](#实现-sum-方法使-sumxysumxy返回的结果相同) ✅
- [两个对象如何比较](#两个对象如何比较) ✅
- [说一下变量的作用域链](#说一下变量的作用域链) ✅
- [介绍 dom 树对比](#介绍-dom-树对比) ✅
- [如何设计状态树](#如何设计状态树) ✅
- [Ajax 发生跨域要设置什么（前端）](#ajax-发生跨域要设置什么前端) ✅
- [加上 CORS 之后从发起到请求正式成功的过程](#加上-cors-之后从发起到请求正式成功的过程) ✅
- [Async 里面有多个 await 请求，可以怎么优化](#async-里面有多个-await-请求可以怎么优化) ✅
- [JavaScript 变量类型分为几种，区别是什么](#javascript-变量类型分为几种区别是什么) ✅
- [JavaScript 里垃圾回收机制是什么，常用的是哪种，怎么处理的](#javascript-里垃圾回收机制是什么常用的是哪种怎么处理的) ✅
- [ES5 和 ES6 有什么区别](#es5-和-es6-有什么区别) ✅
- [取数组的最大值（ES5、ES6）](#取数组的最大值es5es6)
- [some、every、find、filter、map、forEach 有什么区别](#someeveryfindfiltermapforeach-有什么区别)
- [页面上生成一万个 button，并且绑定事件，如何做（JS 原生操作 DOM）？循环绑定时的 index 是多少，为什么，怎么解决？](#页面上生成一万个-button并且绑定事件如何做js-原生操作-dom循环绑定时的-index-是多少为什么怎么解决)
- [页面上有一个 input，还有一个 p 标签，改变 input 后 p 标签就跟着变化，如何处理？监听 input 的哪个事件，在什么时候触发？](#页面上有一个-input还有一个-p-标签改变-input-后-p-标签就跟着变化如何处理监听-input-的哪个事件在什么时候触发)
- [Promise 和 async/await，和 Callback 有什么区别](#promise-和-asyncawait和-callback-有什么区别)
- [项目中对于用户体验做过什么优化](#项目中对于用户体验做过什么优化)
- [前后端通信使用什么方案](#前后端通信使用什么方案)
- [RESTful 常用的 Method](#restful-常用的-method)
- [prototype 和proto区别](#prototype-和proto区别)
- [new 的实现原理，动手实现一个 new](#new-的实现原理动手实现一个-new)
- [如何实现 H5 手机端的适配](#如何实现-h5-手机端的适配)
- [如何去除 url 中的#号](#如何去除-url-中的号)
- [base64 为什么能提升性能，缺点](#base64-为什么能提升性能缺点)
- [介绍 webp 这个图片文件格式](#介绍-webp-这个图片文件格式)
- [异步请求，低版本 fetch 如何低版本适配](#异步请求低版本-fetch-如何低版本适配)
- [ajax 如何处理跨域？CORSr 如何设置？](#ajax-如何处理跨域corsr-如何设置)
- [jsonp 为什么不支持 post 方法](#jsonp-为什么不支持-post-方法)
- [介绍 Immuable](#介绍-immuable)
- [介绍 JS 全部数据类型，基本数据类型和引用数据类型的区别](#介绍-js-全部数据类型基本数据类型和引用数据类型的区别)
- [Array 是 Object 类型吗](#array-是-object-类型吗)
- [说一下栈和堆的区别，垃圾回收时栈和堆的区别](#说一下栈和堆的区别垃圾回收时栈和堆的区别)
- [数组里面有 10 万个数据，取第一个元素和第 10 万个元素的时间相差多少](#数组里面有-10-万个数据取第一个元素和第-10-万个元素的时间相差多少)
- [Async/Await 怎么实现](#asyncawait-怎么实现)
- [JavaScript 为什么要区分微任务和宏任务](#javascript-为什么要区分微任务和宏任务)
- [Promise 构造函数是同步还是异步执行，then 呢](#promise-构造函数是同步还是异步执行then-呢)
- [JavaScript 执行过程分为哪些阶段](#javascript-执行过程分为哪些阶段)
- [词法作用域和 this 的区别](#词法作用域和-this-的区别)
- [loadsh 深拷贝实现原理](#loadsh-深拷贝实现原理)
- [ES6 中 let 块作用域是怎么实现的](#es6-中-let-块作用域是怎么实现的)
- [formData 和原生的 ajax 有什么区别](#formdata-和原生的-ajax-有什么区别)
- [介绍下表单提交，和 formData 有什么关系](#介绍下表单提交和-formdata-有什么关系)
- [promise 如何实现 then 处理，动手实现 then](#promise-如何实现-then-处理动手实现-then)
- [如何处理异常捕获](#如何处理异常捕获)
- [项目如何管理模块](#项目如何管理模块)
- [尽可能多的写出判断数组的方法](#尽可能多的写出判断数组的方法)
- [介绍 localstorage 的 api](#介绍-localstorage-的-api)
- [使用原型最大的好处](#使用原型最大的好处)
- [单例、工厂、观察者项目中实际场景](#单例工厂观察者项目中实际场景)
- [添加原生事件不移除为什么会内存泄露，还有哪些地方会存在内存泄漏](#添加原生事件不移除为什么会内存泄露还有哪些地方会存在内存泄漏)
- [setInterval 需要注意的点](#setinterval-需要注意的点)
- [定时器为什么是不精确的](#定时器为什么是不精确的)
- [setTimeout(1)和 setTimeout(2)之间的区别](#settimeout1和-settimeout2之间的区别)
- [介绍宏任务和微任务](#介绍宏任务和微任务)
- [promise 里面和 then 里面执行有什么区别](#promise-里面和-then-里面执行有什么区别)
- [介绍 class 和 ES5 的类以及区别](#介绍-class-和-es5-的类以及区别)
- [介绍 defineProperty 方法，什么时候需要用到](#介绍-defineproperty-方法什么时候需要用到)
- [for..in 和 object.keys 的区别](#forin-和-objectkeys-的区别)
- [使用闭包特权函数的使用场景](#使用闭包特权函数的使用场景)
- [JavaScript 是什么范式语言](#javascript-是什么范式语言)
- [Promise 有没有解决异步的问题](#promise-有没有解决异步的问题)
- [Promise 和 setTimeout 的区别](#promise-和-settimeout-的区别)
- [按照调用实例，实现下面的 Person 方法](#按照调用实例实现下面的-person-方法)
- [请写出正确的执行结果](#请写出正确的执行结果)
- [请写出正确的执行结果](#请写出正确的执行结果-1)
- [请写出正确的执行结果](#请写出正确的执行结果-2)
- [请写出正确的执行结果](#请写出正确的执行结果-3)
- [请写出正确的执行结果](#请写出正确的执行结果-4)
- [请写出正确的执行结果](#请写出正确的执行结果-5)
- [请写出代码正确执行结果，并解释原因](#请写出代码正确执行结果并解释原因)
- [请写出正确的执行结果](#请写出正确的执行结果-6)
- [请写出正确的执行结果](#请写出正确的执行结果-7)
- [按要求完成代码](#按要求完成代码)
- [请写出正确的执行结果](#请写出正确的执行结果-8)
- [请写出正确的执行结果](#请写出正确的执行结果-9)
- [请修改代码能跳出死循环](#请修改代码能跳出死循环)
- [修改代码不造成死循环](#修改代码不造成死循环)
- [请写出代码正确执行结果](#请写出代码正确执行结果)
- [请写出代码正确执行结果](#请写出代码正确执行结果-1)
- [计算以上字节每位 <g-emoji class="g-emoji" alias="airplane" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2708.png">✈️</g-emoji> 的起码点，并描述这些字节的起码点代表什么](#计算以上字节每位-️-的起码点并描述这些字节的起码点代表什么)
- [请写出代码正确执行结果，并解释原因](#请写出代码正确执行结果并解释原因-1)
- [请写出代码正确执行结果](#请写出代码正确执行结果-2)
- [请写出代码正确执行结果，并解释原因](#请写出代码正确执行结果并解释原因-2)
- [请写出代码正确执行结果](#请写出代码正确执行结果-3)
- [请写出代码正确执行结果，并解释原因](#请写出代码正确执行结果并解释原因-3)
- [请问当前 textarea 文本框展示的内容是什么？](#请问当前-textarea-文本框展示的内容是什么)
- [请写出代码正确执行结果](#请写出代码正确执行结果-4)
- [请写出代码正确执行结果](#请写出代码正确执行结果-5)
- [请写出代码正确执行结果，并解释为什么](#请写出代码正确执行结果并解释为什么)
- [请手写实现一个拖拽](#请手写实现一个拖拽)
- [请手动实现一个浅拷贝](#请手动实现一个浅拷贝)
- [介绍 instanceof 原理，并手动实现](#介绍-instanceof-原理并手动实现)
- [请实现一个 JSON.stringfy](#请实现一个-jsonstringfy)
- [请实现一个 JSON.parse](#请实现一个-jsonparse)
- [请写出代码的正确执行结果，并解释原因？](#请写出代码的正确执行结果并解释原因)
- [请写出代码的正确执行结果，并解释原因？](#请写出代码的正确执行结果并解释原因-1)
- [请写出代码的正确执行结果，并解释原因？](#请写出代码的正确执行结果并解释原因-2)
- [请写出代码的正确执行结果，并解释原因？](#请写出代码的正确执行结果并解释原因-3)
- [请写出代码的正确执行结果，并解释原因？](#请写出代码的正确执行结果并解释原因-4)
- [请写出代码正确执行结果，并解释原因？](#请写出代码正确执行结果并解释原因-4)
- [JavaScript 中如何模拟实现方法的重载](#javascript-中如何模拟实现方法的重载)
- [请解释 JSONP 的工作原理](#请解释-jsonp-的工作原理)
- [用 html、css、js 模拟实现一个下拉框，使得下拉框在各个浏览器下的样式和行为完全一致，说出你的设计方案，并且重点说明功能设计时要考虑的因素。](#用-htmlcssjs-模拟实现一个下拉框使得下拉框在各个浏览器下的样式和行为完全一致说出你的设计方案并且重点说明功能设计时要考虑的因素)
- [实现一个打点计时器](#实现一个打点计时器)
- [JavaScript 写一个单例模式，可以具体到某一个场景](#javascript-写一个单例模式可以具体到某一个场景)
- [JavaScript 基本数据类型都有哪些？用 typeOf 判断分别显示什么？](#javascript-基本数据类型都有哪些用-typeof-判断分别显示什么)
- [怎么判断引用类型数据，兼容判断原始类型数据呢？](#怎么判断引用类型数据兼容判断原始类型数据呢)
- [概述异步编程模型](#概述异步编程模型)
- [在一个 ul 里有 10 个 li,实现点击对应的 li,输出对应的下标](#在一个-ul-里有-10-个-li实现点击对应的-li输出对应的下标)
- [分别对以下数组进行去重，1:[1,'1',2,'2',3]，2:[1,[1,2,3['1','2','3'],4],5,6]](#分别对以下数组进行去重11122321123123456)
- [简述 JavaScript 中的函数的几种调用方式](#简述-javascript-中的函数的几种调用方式)
- [编写一个 Person 类，并创建两个不同的 Person 对象](#编写一个-person-类并创建两个不同的-person-对象)
- [手写实现 call](#手写实现-call)
- [手写实现 apply](#手写实现-apply)
- [一个 dom 必须要操作几百次，该如何解决，如何优化？](#一个-dom-必须要操作几百次该如何解决如何优化)
- [页面埋点怎么实现](#页面埋点怎么实现)
- [除了 jsonp、postmessage 后端控制，怎么实现跨页面通讯](#除了-jsonppostmessage-后端控制怎么实现跨页面通讯)
- [说一下 let、const 的实现，动手实现一下](#说一下-letconst-的实现动手实现一下)
- [addEventListener 再 removeListener 会不会造成内存泄漏](#addeventlistener-再-removelistener-会不会造成内存泄漏)
- [scrollview 如何进行性能优化(例如 page=100 时，往上滚动)](#scrollview-如何进行又能优化例如-page100-时往上滚动)
- [原生 JavaScript 获取 ul 中的第二个 li 里边的 p 标签的内容](#原生-javascript-获取-ul-中的第二个-li-里边的-p-标签的内容)
- [说下 offsetWith 和 clientWidth、offsetHeight 和 clientHeight 的区别，说说 offsetTop，offsetLeft，scrollWidth、scrollHeight 属性都是干啥的](#说下-offsetwith-和-clientwidthoffsetheight-和-clientheight-的区别说说-offsettopoffsetleftscrollwidthscrollheight-属性都是干啥的)
- [写一个函数打乱一个数组，传入一个数组，返回一个打乱的新数组](#写一个函数打乱一个数组传入一个数组返回一个打乱的新数组)
- [数组截取插入 splice，push 返回值，数组的栈方法、队列方法、排序方法、操作方法、迭代方法说一下](#数组截取插入-splicepush-返回值数组的栈方法队列方法排序方法操作方法迭代方法说一下)
- [判断一个变量的类型，写个方法用 Object.prototype.toString 判断传入数据的类型](#判断一个变量的类型写个方法用-objectprototypetostring-判断传入数据的类型)
- [判断一个变量的类型，写个方法用 Object.prototype.toString 判断传入数据的类型？Object.prototype.toString.call(Symbol) 返回什么？](#判断一个变量的类型写个方法用-objectprototypetostring-判断传入数据的类型objectprototypetostringcallsymbol-返回什么)
- [对作用域和闭包的理解，解释下 let 和 const 的块级作用域](#对作用域和闭包的理解解释下-let-和-const-的块级作用域)
- [以下代码输出什么？](#以下代码输出什么)
- [switch case，case 具体是怎么比较的，哪些情况下会走到 default](#switch-casecase-具体是怎么比较的哪些情况下会走到-default)
- [说下 typeof()各种类型的返回值？instanceof 呢？](#说下-typeof各种类型的返回值instanceof-呢)
- [if([] == 0), [1,2] == "1,2", if([]), [] == 0 具体是怎么对比的](#if--0-12--12-if---0-具体是怎么对比的)
- [如何加快页面渲染速度，都有哪些方式](#如何加快页面渲染速度都有哪些方式)
- [generator 的实现原理](#genertor-的实现原理)
- [判断是否是数组的方法](#判断是否是数组的方法)
- [手写 EventEmitter 实现](#手写-eventemitter-实现)
- [给出的两行代码为什么这么输出](#给出的两行代码为什么这么输出)
- [动画性能如何检测](#动画性能如何检测)
- [平时都用到了哪些设计模式](#平时都用到了哪些设计模式)
- [对 service worker 的理解](#对-service-worker-的理解)
- [单点登录实现原理](#单点登录实现原理)
- [尾递归实现](#尾递归实现)
- [有 1000 个 dom，需要更新其中的 100 个，如何操作才能减少 dom 的操作？](#有-1000-个-dom需要更新其中的-100-个如何操作才能减少-dom-的操作)
- [商城的列表页跳转到商品的详情页，详情页数据接口很慢，前端可以怎么优化用户体验？](#商城的列表页跳转到商品的详情页详情页数据接口很慢前端可以怎么优化用户体验)
- [多个 tab 只对应一个内容框，点击每个 tab 都会请求接口并渲染到内容框，怎么确保频繁点击 tab 但能够确保数据正常显示？](#多个-tab-只对应一个内容框点击每个-tab-都会请求接口并渲染到内容框怎么确保频繁点击-tab-但能够确保数据正常显示)
- [请实现鼠标点击页面中的任意标签，alert 该标签的名称(注意兼容性)](#请实现鼠标点击页面中的任意标签alert-该标签的名称注意兼容性)
- [完成一个表达式，验证用户输入是否是电子邮箱](#完成一个表达式验证用户输入是否是电子邮箱)
- [原生实现 ES5 的 Object.create()方法](#原生实现-es5-的-objectcreate方法)
- [如何记录前端在用户浏览器上发生的错误并汇报给服务器？](#如何记录前端在用户浏览器上发生的错误并汇报给服务器)
- [有哪几种方式可以解决跨域问题？(描述对应的原理)](#有哪几种方式可以解决跨域问题描述对应的原理)
- [按要求完成题目](#按要求完成题目)
- [你是如何组织 JavaScript 代码的？（可以从模块、组件、模式、编程思想等方面回答）](#你是如何组织-javascript-代码的可以从模块组件模式编程思想等方面回答)
- [填充代码实现 template 方法](#填充代码实现-template-方法)
- [请描述下为什么页面需要做优化？并写出常用的页面优化实现方案？](#请描述下为什么页面需要做优化并写出常用的页面优化实现方案)
- [请列出至少 5 个 JavaScript 常用的内置对象，说明用途](#请列出至少-5-个-javascript-常用的内置对象说明用途)
- [请描述下 JavaScript 中 Scope、Closure、Prototype 概念，并说明 JavaScript 封装、继承实现原理。](#请描述下-javascript-中-scopeclosureprototype-概念并说明-javascript-封装继承实现原理)
- [请列出目前主流的 JavaScript 模块化实现的技术有哪些？说出它们的区别？](#请列出目前主流的-javascript-模块化实现的技术有哪些说出它们的区别)
- [请用 JavaScript 代码实现事件代理](#请用-javascript-代码实现事件代理)
- [实现格式化输出，比如输入 999999999，输出 999,999,999](#实现格式化输出比如输入-999999999输出-999999999)
- [使用 JavaScript 实现 cookie 的设置、读取、删除](#使用-javascript-实现-cookie-的设置读取删除)
- [请编写一个 JavaScript 函数 parseQueryString,它的用途是把 URL 参数解析为一个对象，url="<a href="http://iauto360.cn/index.php?key0=0&amp;key1=1&amp;key2=2" rel="nofollow">http://iauto360.cn/index.php?key0=0&amp;key1=1&amp;key2=2</a>"](#请编写一个-javascript-函数-parsequerystring它的用途是把-url-参数解析为一个对象urlhttpiauto360cnindexphpkey00key11key22)
- [如何实现 a,b 两个变量的交换](#如何实现-ab-两个变量的交换)
- [给 JavaScript 的 String 原生对象添加一个名为 trim 的原型方法，用于截取字符串前后的空白字符](#给-javascript-的-string-原生对象添加一个名为-trim-的原型方法用于截取字符串前后的空白字符)
- [微任务和宏任务的区别](#微任务和宏任务的区别)
- [原生 JavaScript 实现图片懒加载的思路](#原生-javascript-实现图片懒加载的思路)
- [回调函数和任务队列的区别](#回调函数和任务队列的区别)
- [写出下面代码的输出结果](#写出下面代码的输出结果)
- [有这样一个函数 A,要求在不改变原有函数 A 功能以及调用方式的情况下，使得每次调用该函数都能在控制台打印出“HelloWorld”](#有这样一个函数-a要求在不改变原有函数-a-功能以及调用方式的情况下使得每次调用该函数都能在控制台打印出helloworld)
- [在浏览器执行以下代码，写出打印结果](#在浏览器执行以下代码写出打印结果)
- [请写出弹出值，并解释为什么？](#请写出弹出值并解释为什么)
- [写出输出值，并解释为什么](#写出输出值并解释为什么)
- [请写出代码执⾏结果，并解释为什么](#请写出代码执结果并解释为什么)
- [请写出代码执⾏结果，并解释为什么](#请写出代码执结果并解释为什么-1)
- [给定⼀个⼤⼩为 n 的数组，找到其中的众数。众数是指在数组中出现次数⼤于 n/2 的元素](#给定个为-n-的数组找到其中的众数众数是指在数组中出现次数于--n2--的元素)
- [原生实现addClass,用多种方法](#原生实现addclass用多种方法)
- [实现一个倒计时,setInterval实现的话，如何消除时间误差](#实现一个倒计时setinterval实现的话如何消除时间误差)
- [函数中的arguments是数组吗？若不是，如何将它转化为真正的数组？](#函数中的arguments是数组吗若不是如何将它转化为真正的数组)
- [请写出以下代码的打印结果](#请写出以下代码的打印结果-2)
- [以最小的改动解决以下代码的错误(可以使用ES6)](#以最小的改动解决以下代码的错误可以使用es6)
- [实现Function 原型的bind方法，使得以下程序最后能输出“success”](#实现function-原型的bind方法使得以下程序最后能输出success)
- [文件上传如何做断点续传](#文件上传如何做断点续传)
- [列举 3 种强制类型转换和 2 种隐式类型转换](#列举-3-种强制类型转换和-2-种隐式类型转换)

### 写一个 mySetInterVal(fn, a, b),每次间隔 a,a+b,a+2b,...,a+nb 的时间，然后写一个 myClear，停止上面的 mySetInterVal

公司：头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/7)
创建一个 `mySetInterval` 函数来实现这个功能，并使用 `myClear` 函数来停止间隔执行。下面是具体的实现：

```javascript
let intervalID = null; // 用于存储定时器ID

function mySetInterval(fn, a, b) {
  let n = 0; // 用于记录已经执行的次数

  function run() {
    fn(); // 执行传入的函数
    n++;
    // 计算下一次的间隔时间
    const nextInterval = a + n * b;
    intervalID = setTimeout(run, nextInterval);
  }

  // 启动第一次执行
  run();
}

function myClearInterval() {
  if (intervalID !== null) {
    clearInterval(intervalID);
    intervalID = null;
  }
}
```

这里的 `mySetInterval` 函数接受三个参数：要执行的函数 `fn`，初始间隔时间 `a`，和增加的间隔时间 `b`。它使用递归来定时执行函数 `fn`，并在每次执行后计算下一次的间隔时间。

你可以使用它的方式如下：

```javascript
function myFunction() {
  console.log("Hello, world!");
}

// 启动间隔执行
mySetInterval(myFunction, 1000, 500); // 每1秒，1.5秒，2秒...执行一次

// 停止间隔执行
myClearInterval(); // 停止间隔执行
```

通过调用 `myClearInterval` 函数，你可以停止之前启动的间隔执行，这样定时器就不再触发。这个自定义的 `mySetInterval` 和 `myClearInterval` 类似于原生的 `setInterval` 和 `clearInterval`，但允许你更精细地控制间隔时间。

<br/>

### 介绍防抖节流原理、区别以及应用，并用JavaScript进行实现

公司：滴滴、虎扑、挖财、58、头条

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/15)
防抖和节流是常用的优化技术，用于控制函数的执行频率，提高性能和用户体验。

**防抖（Debounce）** 的原理是在事件触发后，等待一段时间（例如200毫秒），如果在这段时间内没有再次触发事件，才执行函数。如果在等待时间内又触发了事件，则重新计时。这样可以避免频繁触发事件导致函数多次执行，只有在事件停止触发后才执行一次函数。

**防抖的应用场景**：
- 输入框搜索建议：当用户输入时，等待一段时间后再发送请求获取搜索建议，避免每次输入都发送请求。
- 窗口大小调整：当窗口大小调整时，等待一段时间后再执行布局调整的函数，避免频繁触发布局调整。

**节流（Throttle）** 的原理是在一定时间间隔内只执行一次函数。例如，设置间隔时间为200毫秒，如果在这段时间内触发了多次事件，只有第一次触发会执行函数，后续的触发会被忽略。然后在间隔时间过去后，才能再次触发执行函数。

**节流的应用场景**：
- 滚动加载：当用户滚动页面时，每隔一段时间加载更多的内容，避免滚动过快导致频繁加载。
- 频繁点击按钮：当用户频繁点击按钮时，每隔一段时间才执行一次点击事件，避免误操作或重复提交。

下面是使用 JavaScript 实现防抖和节流的示例代码：

**防抖的实现**：
```javascript
function debounce(func, delay) {
  let timerId;

  return function (...args) {
    clearTimeout(timerId);
    timerId = setTimeout(() => {
      func.apply(this, args);
    }, delay);
  };
}

// 使用防抖函数
const debouncedFn = debounce(() => {
  console.log("Debounced function executed");
}, 200);

// 触发事件
debouncedFn(); // 在200毫秒后执行函数
```

**节流的实现**：
```javascript
function throttle(func, delay) {
  let timerId;
  let lastExecTime = 0;

  return function (...args) {
    const currentTime = Date.now();
    const elapsedTime = currentTime - lastExecTime;

    if (elapsedTime >= delay) {
      func.apply(this, args);
      lastExecTime = currentTime;
    } else {
      clearTimeout(timerId);
      timerId = setTimeout(() => {
        func.apply(this, args);
        lastExecTime = Date.now();
      }, delay - elapsedTime);
    }
  };
}

// 使用节流函数
const throttledFn = throttle(() => {
  console.log("Throttled function executed");
}, 200);

// 触发事件
throttledFn(); // 立即执行函数
throttledFn(); // 在200毫秒后执行函数
throttledFn(); // 在400毫秒后执行函数
```

通过使用防抖和节流，可以有效地控制函数的执行频率，避免过多的计算和请求，提高性能和用户体验。根据具体的需求，选择合适的优化方式来应用在相应的场景中。

<br/>

### 对闭包的看法，为什么要用闭包？说一下闭包原理以及应用场景

公司：滴滴、携程、喜马拉雅、微医、蘑菇街、酷家乐、腾讯应用宝、安居客

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/17)
闭包是一种强大的特性，它可以让函数访问并操作其外部作用域中的变量，即使在函数执行完毕后，这些变量仍然可以被访问和使用。闭包在JavaScript中被广泛应用，它提供了一种在函数内部创建私有变量和实现数据封装的方式。

**闭包的原理**：
当一个函数内部定义了另一个函数，并且内部函数引用了外部函数的变量时，就形成了闭包。内部函数可以访问外部函数的变量，因为在创建内部函数时，会创建一个闭包环境，将外部函数的变量保存在闭包环境中。即使外部函数执行完毕，闭包环境仍然存在，内部函数仍然可以访问和使用这些变量。

**闭包的应用场景**：
1. **私有变量和函数**：闭包可以创建私有变量和函数，这些变量和函数对外部是不可见的，只能通过内部函数访问和操作。这样可以避免全局命名冲突和数据被外部修改，实现数据的封装和隐藏。
2. **模块化开发**：闭包可以用于实现模块化开发，将一组相关的变量和函数封装在闭包中，对外暴露必要的接口。这样可以避免全局命名污染，提高代码的可维护性和可复用性。
3. **函数柯里化**：闭包可以用于实现函数柯里化（Currying），即将一个接受多个参数的函数转化为接受单个参数的函数序列。通过闭包保存部分参数，返回一个新的函数，可以实现参数的复用和延迟执行。
4. **事件处理**：闭包可以用于处理事件回调函数，将事件处理函数作为闭包保存，可以在事件触发时访问和操作外部的变量。这样可以避免全局变量的使用和事件处理函数的重复定义。

下面是一个闭包的示例代码：

```javascript
function outerFunction() {
  let outerVariable = "I'm outer";

  function innerFunction() {
    console.log(outerVariable);
  }

  return innerFunction;
}

const closure = outerFunction();
closure(); // 输出 "I'm outer"
```

在上面的代码中，`innerFunction` 是一个闭包，它可以访问和使用外部函数 `outerFunction` 中的 `outerVariable` 变量。即使 `outerFunction` 执行完毕，`closure` 仍然可以访问和使用 `outerVariable` 变量。这样就实现了变量的私有化和封装。

闭包是JavaScript中强大且灵活的特性，合理地应用闭包可以提高代码的可维护性和可复用性，同时避免全局命名冲突和数据被外部修改的问题。

<br/>

### 实现 lodash 的_.get

公司：滴滴

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/20)
当想要实现类似 Lodash 的 `_.get` 函数时，可以创建一个 JavaScript 函数，该函数接受一个对象和一个表示嵌套属性路径的字符串，然后返回该路径对应的值。以下是一个简单的实现示例：

```javascript
function getObjectValue(obj, path, defaultValue) {
  const keys = path.split('.');
  let result = obj;
  
  for (let key of keys) {
    if (result !== null && result !== undefined && key in result) {
      result = result[key];
    } else {
      return defaultValue;
    }
  }
  
  return result;
}

// 示例用法
const user = {
  id: 1,
  name: {
    first: 'John',
    last: 'Doe'
  },
  address: {
    city: 'New York'
  }
};

console.log(getObjectValue(user, 'name.first')); // 输出: 'John'
console.log(getObjectValue(user, 'address.country', 'USA')); // 输出: 'USA'，因为 'address.country' 不存在，使用默认值 'USA'
```

在这个示例中，`getObjectValue` 函数接受三个参数：`obj` 表示要获取属性值的对象，`path` 表示属性路径的字符串，`defaultValue` 是可选的默认值。函数首先将路径字符串拆分为属性键组成的数组，然后逐级深入对象，直到找到路径对应的属性值。如果任何一级的属性不存在，函数会返回指定的默认值（如果提供了默认值）或者 `undefined`。

请注意，这只是一个简单的实现。在实际应用中，你可能需要添加更多的边界检查和错误处理来提高函数的鲁棒性。

<br/>

### 实现 add(1)(2)(3)

公司：滴滴

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/21)
想要实现一个函数 `add(1)(2)(3)`，这看起来像一个柯里化（Currying）函数的应用。柯里化是一种将接受多个参数的函数转化为接受单个参数的函数序列的技术。让我们来实现这个函数：

```javascript
function add(x) {
  return function(y) {
    // 返回一个新的函数，接受参数 y
    return function(z) {
      // 返回一个新的函数，接受参数 z
      return x + y + z; // 在最后一个函数中返回累积的结果
    };
  };
}

const result = add(1)(2)(3); // 连续调用三次函数
console.log(result); // 输出 6
```

在上面的代码中，`add` 函数接受一个参数 `x`，然后返回一个函数，这个返回的函数接受参数 `y`，再返回一个函数，接受参数 `z`，最终在最后一个函数中将这三个参数相加并返回结果。这使得你可以像 `add(1)(2)(3)` 这样连续调用三次函数，实现参数的累积相加，最终得到结果 6。

这种柯里化的方法可以用于创建更灵活的函数，使函数的参数传递更加清晰和易于使用。你可以进一步扩展这个模式，以实现任意数量的参数相加。

<br/>

### 实现链式调用

公司：滴滴

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/22)
要实现链式调用，你可以确保每个方法在执行后返回调用该方法的对象本身。这样，你就可以在返回的对象上继续调用其他方法。以下是一个简单的示例，演示如何实现链式调用：

```javascript
class Chainable {
  constructor(value) {
    this.value = value;
  }

  add(value) {
    this.value += value;
    return this; // 返回当前对象，以支持链式调用
  }

  multiply(value) {
    this.value *= value;
    return this; // 返回当前对象，以支持链式调用
  }

  subtract(value) {
    this.value -= value;
    return this; // 返回当前对象，以支持链式调用
  }

  getValue() {
    return this.value;
  }
}

// 使用示例
const chainable = new Chainable(0);
const result = chainable.add(5).multiply(3).subtract(2).getValue();

console.log(result); // 输出: 13，((0 + 5) * 3) - 2 = 13
```

在这个示例中，`Chainable` 类有三个方法：`add`、`multiply` 和 `subtract`，它们分别执行加法、乘法和减法操作，并且每个方法在执行后返回当前对象 `this`。这样，你就可以在一个语句中链接多个方法，形成链式调用。

请注意，当你在一个方法中返回 `this` 时，它指的是调用该方法的对象。这种技术通常用于构建流畅的、易读的 API。

<br/>

### 类数组和数组的区别，dom 的类数组如何转换成数组

公司：海康威视

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/24)
类数组（array-like object）是指具有类似数组的特性，但不是真正的数组对象。它们通常具有数字索引和 `length` 属性，但没有数组的方法（如 `push`、`pop`、`forEach` 等）。常见的类数组包括函数的 `arguments` 对象和 DOM 元素集合。

类数组与数组的区别在于它们的原型链不同，类数组并没有继承自 `Array` 原型链上的方法。因此，如果我们想要对类数组执行数组的方法，需要先将其转换为真正的数组。

**将 DOM 的类数组转换为数组**：
DOM 的类数组是指通过 DOM 操作获取的元素集合，如 `querySelectorAll` 返回的结果。这些集合看起来像数组，但实际上是类数组对象。要将 DOM 的类数组转换为数组，有几种常见的方法：

1. **Array.from() 方法**：`Array.from()` 方法可以将类数组对象或可迭代对象转换为真正的数组。我们可以将 DOM 的类数组对象作为参数传递给 `Array.from()` 方法，它会返回一个新的数组。

   ```javascript
   const nodeList = document.querySelectorAll('.my-class');
   const array = Array.from(nodeList);
   ```

2. **Array.prototype.slice.call() 方法**：`Array.prototype.slice.call()` 方法可以将一个类数组对象转换为数组。我们可以通过调用 `slice` 方法并将类数组对象作为 `this` 对象传递给它来实现转换。

   ```javascript
   const nodeList = document.querySelectorAll('.my-class');
   const array = Array.prototype.slice.call(nodeList);
   ```

3. **Spread Operator（展开运算符）**：展开运算符 `...` 可以将可迭代对象展开为数组。我们可以使用展开运算符将类数组对象转换为数组。

   ```javascript
   const nodeList = document.querySelectorAll('.my-class');
   const array = [...nodeList];
   ```

以上三种方法都可以将 DOM 的类数组对象转换为真正的数组，从而可以使用数组的方法对其进行操作。

需要注意的是，转换为数组后，得到的是一个新的数组，对该数组的修改不会影响原始的类数组对象。

<br/>

### 介绍下 promise 的特性、优缺点，内部是如何实现的，动手实现 Promise

公司：滴滴、头条、喜马拉雅、兑吧、寺库、百分点、58、安居客

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/29)
### Promise 的特性：

1. **异步操作管理**：Promise 提供了更优雅的方式来处理异步操作，使得代码更易读和维护。
2. **链式调用**：Promise 允许你通过 `.then()` 方法和 `.catch()` 方法进行链式调用，处理异步操作的结果或错误。
3. **状态管理**：Promise 有三种状态：pending（进行中）、fulfilled（已成功）和rejected（已失败），状态不可逆，只能从 pending 转变为 fulfilled 或从 pending 转变为 rejected。
4. **错误处理**：Promise 具备错误捕获的能力，你可以通过 `.catch()` 或 `.then(null, errorHandler)` 来捕获并处理错误。
5. **并行执行**：可以利用 `Promise.all()` 来处理多个 Promise 实例的并行执行，等待它们全部完成。

### Promise 的优点：

1. **更清晰的异步代码**：Promise 可以将异步代码组织成更具可读性和可维护性的形式，避免了回调地狱。
2. **更好的错误处理**：Promise 允许你使用 `.catch()` 统一处理错误，使得错误处理更加方便。
3. **更好的状态管理**：Promise 的状态明确，状态不可逆，避免了复杂的状态管理逻辑。

### Promise 的缺点：

1. **不可取消**：一旦创建了一个 Promise，它就不能被取消，只能等待它的状态变化。
2. **无法中断**：与取消类似，一旦 Promise 开始执行，就无法中断它，可能会导致不必要的计算浪费。
3. **错误不会冒泡**：Promise 内部的错误不会冒泡到全局作用域，如果你不在合适的地方进行错误处理，可能会导致未捕获的错误。

### Promise 内部实现：

Promise 内部实现通常基于状态机，有三种状态：pending、fulfilled、rejected。Promise 会持有一个结果（可能是成功的值或错误原因）和一个状态。

- 当 Promise 是 pending 状态时，它可以转变为 fulfilled 状态（表示成功）或 rejected 状态（表示失败），并且一旦转变，就无法再改变状态。
- 当 Promise 转变为 fulfilled 状态时，它会调用 `.then()` 方法中的回调函数。
- 当 Promise 转变为 rejected 状态时，它会调用 `.catch()` 方法中的回调函数。

Promise 内部实现需要处理异步操作、状态变化通知和链式调用的逻辑。

### 手动实现 Promise：

以下是一个简单版本的 Promise 实现：

```javascript
class MyPromise {
  constructor(executor) {
    this.status = 'pending';
    this.value = undefined;
    this.error = undefined;
    this.resolveCallbacks = [];
    this.rejectCallbacks = [];

    const resolve = (value) => {
      if (this.status === 'pending') {
        this.status = 'fulfilled';
        this.value = value;
        this.resolveCallbacks.forEach(callback => callback(this.value));
      }
    };

    const reject = (error) => {
      if (this.status === 'pending') {
        this.status = 'rejected';
        this.error = error;
        this.rejectCallbacks.forEach(callback => callback(this.error));
      }
    };

    try {
      executor(resolve, reject);
    } catch (error) {
      reject(error);
    }
  }

  then(onFulfilled, onRejected) {
    if (this.status === 'fulfilled') {
      onFulfilled(this.value);
    } else if (this.status === 'rejected') {
      onRejected(this.error);
    } else {
      this.resolveCallbacks.push(onFulfilled);
      this.rejectCallbacks.push(onRejected);
    }
    return this;
  }

  catch(onRejected) {
    if (this.status === 'rejected') {
      onRejected(this.error);
    } else {
      this.rejectCallbacks.push(onRejected);
    }
    return this;
  }
}
```

这个简化的实现并没有处理异步操作，也没有实现 `Promise.all()`、`Promise.race()` 等功能，但它基本上展示了 Promise 的核心概念和链式调用的原理。在实际的应用中，一个完整的 Promise 实现需要处理更多的边界情况和异步操作。

<br/>

### 实现 Promise.all

```js
Promise.all = function (arr) {
  // 实现代码
};
```

公司：滴滴、头条、有赞、微医

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/30)
`Promise.all` 是一个用于处理多个 Promise 对象的工具函数，它接受一个包含多个 Promise 对象的可迭代对象（通常是数组），并在所有 Promise 都成功（resolved）时返回一个包含所有结果的新 Promise，如果任何一个 Promise 失败（rejected），则返回的 Promise 也会失败。

下面是一个自定义实现 `Promise.all` 的简单示例：

```javascript
function customPromiseAll(promises) {
  return new Promise((resolve, reject) => {
    const results = [];
    let completedPromises = 0;

    if (promises.length === 0) {
      resolve(results); // 如果没有 Promise，则直接返回一个已解决的 Promise
    } else {
      promises.forEach((promise, index) => {
        promise
          .then((result) => {
            results[index] = result;
            completedPromises++;

            if (completedPromises === promises.length) {
              resolve(results); // 所有 Promise 都成功，返回包含所有结果的 Promise
            }
          })
          .catch(reject); // 任何一个 Promise 失败，都会导致返回的 Promise 失败
      });
    }
  });
}

// 使用示例
const promise1 = Promise.resolve(1);
const promise2 = Promise.resolve(2);
const promise3 = Promise.resolve(3);

customPromiseAll([promise1, promise2, promise3])
  .then((results) => {
    console.log(results); // 输出 [1, 2, 3]
  })
  .catch((error) => {
    console.error(error);
  });
```

在上面的代码中，`customPromiseAll` 函数接受一个包含多个 Promise 对象的数组 `promises`，它创建一个新的 Promise 对象，并迭代处理每个 Promise。当所有 Promise 都成功时，它将返回包含所有结果的新 Promise；如果任何一个 Promise 失败，它将返回的 Promise 标记为失败。这个示例非常简化了实际的 `Promise.all` 实现，实际实现会更复杂，考虑到错误处理、可迭代对象的处理等。

请注意，如果你使用现代 JavaScript，你可以直接使用内置的 `Promise.all` 方法，它是标准的 Promise 方法，更为健壮和高效。

<br/>

### 手写发布订阅

公司：滴滴、头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/34)
发布-订阅模式（Publish-Subscribe Pattern）是一种常见的设计模式，用于在对象之间建立松散耦合的通信机制。它允许一个对象（发布者/发布者）向多个其他对象（订阅者/观察者）发送通知，而订阅者可以自由订阅或取消订阅感兴趣的事件。下面是一个手写发布-订阅模式的简单示例：

```javascript
// 发布者对象
class Publisher {
  constructor() {
    this.subscribers = [];
  }

  // 添加订阅者
  subscribe(subscriber) {
    this.subscribers.push(subscriber);
  }

  // 移除订阅者
  unsubscribe(subscriber) {
    this.subscribers = this.subscribers.filter((sub) => sub !== subscriber);
  }

  // 发布消息给所有订阅者
  publish(message) {
    this.subscribers.forEach((subscriber) => subscriber.notify(message));
  }
}

// 订阅者对象
class Subscriber {
  constructor(name) {
    this.name = name;
  }

  // 接收发布者消息的方法
  notify(message) {
    console.log(`${this.name} received message: ${message}`);
  }
}

// 创建发布者和订阅者
const publisher = new Publisher();
const subscriber1 = new Subscriber('Subscriber 1');
const subscriber2 = new Subscriber('Subscriber 2');

// 订阅者订阅发布者
publisher.subscribe(subscriber1);
publisher.subscribe(subscriber2);

// 发布者发布消息
publisher.publish('Hello, subscribers!');

// 输出:
// Subscriber 1 received message: Hello, subscribers!
// Subscriber 2 received message: Hello, subscribers!
```

在上述示例中，我们创建了一个 `Publisher` 类和一个 `Subscriber` 类。`Publisher` 类具有订阅（`subscribe`）、取消订阅（`unsubscribe`）和发布（`publish`）的方法。`Subscriber` 类有一个 `notify` 方法，用于接收发布者发送的消息。

我们创建了一个发布者和两个订阅者，然后订阅者订阅了发布者。当发布者发布消息时，所有订阅者都会接收到该消息。

这是一个非常基本的发布-订阅模式示例。在实际应用中，你可以根据需要扩展功能，支持不同的事件、参数传递等。这个模式在前端开发中常用于处理事件和状态管理，如在前端框架中的事件系统、Redux 的状态管理等。

<br/>

### 手写数组转树

公司：滴滴

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/35)
将一个扁平化的数组转换成树形结构是一个常见的操作，特别在处理嵌套数据时非常有用。以下是一个手写 JavaScript 函数，用于将扁平化数组转换成树：

```javascript
function arrayToTree(items) {
  const result = [];
  const itemMap = {};

  // 将数组中的每个元素都转换为一个节点，并将其存储在itemMap中，以便后续查找父节点
  items.forEach((item) => {
    const newItem = { ...item };
    itemMap[newItem.id] = newItem;
  });

  items.forEach((item) => {
    const parent = itemMap[item.parentId];
    if (parent) {
      if (!parent.children) {
        parent.children = [];
      }
      parent.children.push(itemMap[item.id]);
    } else {
      result.push(itemMap[item.id]);
    }
  });

  return result;
}

// 示例用法
const flatData = [
  { id: 1, name: 'Node 1', parentId: null },
  { id: 2, name: 'Node 2', parentId: null },
  { id: 3, name: 'Node 1.1', parentId: 1 },
  { id: 4, name: 'Node 1.2', parentId: 1 },
  { id: 5, name: 'Node 2.1', parentId: 2 },
];

const treeData = arrayToTree(flatData);
console.log(treeData);
```

这个 `arrayToTree` 函数接受一个扁平化的数组 `items`，其中每个元素包括一个 `id` 表示节点的唯一标识，`name` 表示节点的名称，和 `parentId` 表示父节点的 `id`。它通过两次遍历数组来构建树形结构。

首先，它创建一个 `itemMap` 对象，用于存储每个节点，以 `id` 为键。然后，它遍历数组的每个元素，并根据 `parentId` 将节点插入到其父节点的 `children` 属性中，或者如果没有父节点，则将其插入到最顶层的 `result` 数组中。

最终，`arrayToTree` 函数返回一个树形结构的数组，可以通过根节点来访问整个树。

这是一个基本的示例，你可以根据实际需要进行更复杂的定制，例如添加深度限制、过滤等功能。这个函数对于处理具有层次结构的数据非常有用，如组织结构、评论系统等。

<br/>

### 手写用 ES6proxy 如何实现 arr[-1] 的访问

公司：滴滴

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/36)
你可以使用ES6的Proxy对象来实现负数索引的数组访问。Proxy对象允许你创建一个代理来拦截对对象的操作，包括读取属性。以下是一个示例，展示如何使用Proxy实现负数索引的数组访问：

```javascript
const createNegativeIndexArrayProxy = (array) => {
  return new Proxy(array, {
    get(target, prop, receiver) {
      const index = parseInt(prop);
      if (index < 0) {
        // 如果索引为负数，从数组末尾开始计算索引
        const positiveIndex = target.length + index;
        return target[positiveIndex];
      }
      // 如果索引为非负数，直接返回数组的值
      return Reflect.get(target, prop, receiver);
    }
  });
};

// 示例用法
const array = [1, 2, 3, 4, 5];
const proxyArray = createNegativeIndexArrayProxy(array);

console.log(proxyArray[-1]); // 输出：5，访问倒数第一个元素
console.log(proxyArray[-2]); // 输出：4，访问倒数第二个元素
console.log(proxyArray[2]);  // 输出：3，访问正数索引的元素
```

在这个示例中，`createNegativeIndexArrayProxy` 函数接受一个数组作为参数，并返回了一个Proxy对象。在Proxy的`get`处理函数中，如果索引是负数，它会从数组末尾开始计算索引，并返回对应的值。如果索引是非负数，则直接返回数组的值。这样就实现了负数索引的数组访问功能。

<br/>

### 手写实现 Array.flat()

公司：滴滴、快手、携程

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/242)
`Array.flat()` 方法用于将嵌套的数组扁平化为一个新的一维数组。以下是一个手写实现 `Array.flat()` 的 JavaScript 函数：

```javascript
function flatArray(arr, depth = 1) {
  if (depth < 1) {
    return arr.slice();
  }

  return arr.reduce((result, item) => {
    if (Array.isArray(item)) {
      result.push(...flatArray(item, depth - 1));
    } else {
      result.push(item);
    }
    return result;
  }, []);
}

// 示例用法
const nestedArray = [1, [2, [3, 4], 5], 6];
const flattenedArray = flatArray(nestedArray);
console.log(flattenedArray);
```

这个 `flatArray` 函数接受两个参数：`arr` 表示要扁平化的数组，`depth` 表示扁平化的深度，默认为 1。

函数首先检查 `depth` 的值，如果小于 1，则直接返回数组的副本。这是递归的终止条件。

然后，函数使用 `reduce` 方法遍历数组的每个元素。如果元素是一个数组，函数递归调用自身，并将深度减 1，然后将返回的扁平化数组的元素添加到结果数组中。如果元素不是数组，则直接将其添加到结果数组中。

最终，`flatArray` 函数返回一个扁平化的新数组。

在示例中，我们将一个嵌套的数组 `[1, [2, [3, 4], 5], 6]` 传递给 `flatArray` 函数，并将其扁平化为 `[1, 2, 3, 4, 5, 6]`。

需要注意的是，这个手写实现只支持传递一个数字作为 `depth` 参数，而原生的 `Array.flat()` 方法还支持传递 `Infinity` 表示完全扁平化。如果需要支持更复杂的用例，可以对这个实现进行进一步的扩展。

<br/>

### 大数计算如何实现

公司：洋葱学院

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/235)
在计算机中，处理大数（大于计算机内部表示范围的整数）通常需要使用特定的数据结构和算法。以下是几种处理大数的常见方法：

### 1. **字符串表示法**

大数可以用字符串来表示，每位数字存储在字符串的一个元素中。你可以自己编写加法、减法、乘法和除法等基本运算的函数，处理字符串表示的大数。

### 2. **数组表示法**

类似于字符串表示法，大数也可以表示为数组，其中每个元素存储一个数字。数组表示法可以更容易地进行进位和其他数学运算。

### 3. **使用现成的大数库**

很多编程语言提供了处理大数的库，比如：

- **JavaScript**：JavaScript 的内置类型 Number 可以表示的最大安全整数是 2^53 - 1，如果超过这个范围，可以使用 `BigInt` 类型来处理大数。此外，也有第三方库如 `bignumber.js`，提供了更多的大数处理功能。
  
  ```javascript
  const bigNum = BigInt("1234567890123456789012345678901234567890");
  ```

- **Python**：Python 内置的 `int` 类型可以处理任意大的整数。

  ```python
  big_num = 1234567890123456789012345678901234567890
  ```

- **Java**：Java 中有 `BigInteger` 类可以用于大数计算。

  ```java
  import java.math.BigInteger;
  
  BigInteger bigNum = new BigInteger("1234567890123456789012345678901234567890");
  ```

### 4. **快速幂算法**

在大数计算中，特别是在密码学和数论中，经常会用到大数的幂运算。快速幂算法（exponentiation by squaring）可以高效地计算大数的幂。该算法的基本思想是将幂次数进行二进制分解，以减少乘法次数。

这只是大数计算的一些常见方法。具体选择哪种方法取决于你的需求和编程语言的支持。对于复杂的大数运算，你可能需要实现自己的算法或使用特定的库来处理。

<br/>

### 什么是深拷贝，和浅拷贝有什么区别，动手实现一个深拷贝

公司：顺丰、新东方、高德、虎扑、微医、百分点、酷狗

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/903)
深拷贝（Deep Copy）和浅拷贝（Shallow Copy）都是在编程中用于复制数据结构的概念，它们之间的主要区别在于复制的深度和复制后的数据独立性。

1. **浅拷贝**：
   - 浅拷贝仅复制了数据结构的第一层，而不会递归复制嵌套的子数据结构。
   - 复制后的数据结构中的基本数据类型（如数字、字符串）是独立的，但嵌套对象和数组等引用类型仍然共享相同的引用，因此对其中一个的修改会影响到另一个。
   - 常见的浅拷贝方法包括对象的扩展运算符 `{...obj}` 和数组的 `Array.slice()` 或 `Array.concat()`。

2. **深拷贝**：
   - 深拷贝会递归复制数据结构的所有层级，确保复制后的数据结构是完全独立的，对一个数据结构的修改不会影响到另一个。
   - 深拷贝通常需要更多的计算和内存资源，因为它需要复制所有嵌套的数据。
   - 常见的深拷贝方法包括递归遍历数据结构并创建一个全新的数据结构。

以下是一个手写实现深拷贝的 JavaScript 函数：

```javascript
function deepCopy(obj) {
  if (obj === null || typeof obj !== 'object') {
    return obj; // 对于基本数据类型或null，直接返回
  }

  if (Array.isArray(obj)) {
    const copy = [];
    for (let i = 0; i < obj.length; i++) {
      copy[i] = deepCopy(obj[i]); // 递归拷贝数组元素
    }
    return copy;
  }

  if (typeof obj === 'object') {
    const copy = {};
    for (let key in obj) {
      if (obj.hasOwnProperty(key)) {
        copy[key] = deepCopy(obj[key]); // 递归拷贝对象属性
      }
    }
    return copy;
  }
}

// 示例用法
const originalData = {
  name: 'John',
  age: 30,
  hobbies: ['reading', 'gaming'],
  address: {
    city: 'New York',
    zip: '10001',
  },
};

const copiedData = deepCopy(originalData);
console.log(copiedData);
```

这个 `deepCopy` 函数使用递归来深度复制对象和数组。它会遍历原始对象，对于每个属性或元素，如果是基本数据类型或null，就直接复制；如果是数组，就递归复制数组的每个元素；如果是对象，就递归复制对象的每个属性。

这样，`copiedData` 将是原始数据的一个完全独立的深度拷贝，对其中一个的修改不会影响另一个。请注意，这个简单的示例不考虑循环引用等复杂情况，实际应用中可能需要更复杂的深拷贝实现。

<br/>

### 实现一个方法判断 html 中的标签是否闭合

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/234)
要判断HTML中的标签是否闭合，可以使用堆栈（stack）数据结构来跟踪已经打开的标签。当遇到一个标签开始（例如`<div>`），将其推入堆栈中。当遇到一个闭合标签（例如`</div>`），则从堆栈中弹出相应的开始标签。如果在处理完所有标签后堆栈为空，则所有标签都闭合。

以下是一个JavaScript函数，可以用来判断HTML中的标签是否闭合：

```javascript
function isHTMLTagsClosed(html) {
  const stack = [];

  // 使用正则表达式匹配HTML标签
  const tagRegex = /<\s*\/?\s*([a-zA-Z]+)\s*>/g;
  let match;

  while ((match = tagRegex.exec(html)) !== null) {
    const tag = match[1];
    if (tag[0] !== '/') {
      // 如果是开始标签，将其推入堆栈
      stack.push(tag);
    } else {
      // 如果是闭合标签，与堆栈中的标签匹配
      const startTag = stack.pop();
      if (!startTag || startTag !== tag.substring(1)) {
        return false; // 不匹配，标签没有闭合
      }
    }
  }

  // 如果堆栈为空，则所有标签闭合
  return stack.length === 0;
}

// 示例用法
const html1 = '<div><p></p></div>';
const html2 = '<div><p></div></p>';

console.log(isHTMLTagsClosed(html1)); // 输出: true，所有标签闭合
console.log(isHTMLTagsClosed(html2)); // 输出: false，标签没有闭合
```

在这个函数中，我们使用正则表达式匹配HTML标签，并且使用堆栈来跟踪标签的打开和闭合。如果在处理所有标签后堆栈为空，那么所有标签都闭合，函数返回true。如果堆栈不为空，或者标签不匹配，函数返回false，表示HTML中的标签没有闭合。

<br/>

### 箭头函数和普通函数的区别

公司：酷家乐

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/230)
箭头函数（Arrow Function）和普通函数（Regular Function）是 JavaScript 中定义函数的两种不同方式，它们之间有以下区别：

1. **语法简洁性**：
   - 箭头函数的语法更为简洁，可以通过 `=>` 符号来定义函数，省略了 `function` 关键字和大括号 `{}`。
   - 普通函数需要使用完整的函数声明语法，包括 `function` 关键字、函数名和大括号 `{}`。

2. **this 的指向**：
   - 箭头函数没有自己的 `this`，它会继承外层作用域的 `this` 值。这意味着在箭头函数内部，`this` 的值是固定的，指向定义时所在的上下文。
   - 普通函数的 `this` 值是在运行时动态确定的，它的指向取决于函数的调用方式。

3. **arguments 对象**：
   - 箭头函数没有自己的 `arguments` 对象，但可以通过扩展运算符 `...` 来获取传入的参数。
   - 普通函数有自己的 `arguments` 对象，可以直接访问传入的参数。

4. **构造函数**：
   - 箭头函数不能用作构造函数，不能使用 `new` 关键字实例化对象。
   - 普通函数可以用作构造函数，通过 `new` 关键字可以创建对象实例。

5. **适用场景**：
   - 箭头函数适合于简单的函数表达式，特别是在需要保持代码简洁性和可读性的情况下。
   - 普通函数适用于需要更多功能和灵活性的情况，例如需要使用 `this`、`arguments`、`new` 等特性的场景。

下面是一些示例代码，展示了箭头函数和普通函数的不同用法：

```javascript
// 箭头函数示例
const sum = (a, b) => a + b;
console.log(sum(2, 3)); // 输出: 5

const double = num => num * 2;
console.log(double(5)); // 输出: 10

const greet = name => `Hello, ${name}!`;
console.log(greet('John')); // 输出: Hello, John!

// 普通函数示例
function multiply(a, b) {
  return a * b;
}
console.log(multiply(2, 3)); // 输出: 6

function sayHello() {
  console.log('Hello!');
}
sayHello(); // 输出: Hello!

function Person(name) {
  this.name = name;
}
const john = new Person('John');
console.log(john.name); // 输出: John
```

总结来说，箭头函数和普通函数在语法和功能上有一些区别，根据具体的需求和场景选择合适的函数类型。

<br/>

### es5 实现 isInteger

公司：头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/215)
在ECMAScript 5中，我们可以通过正则表达式和数字类型的检查来实现`isInteger`函数。以下是一个实现：

```javascript
function isInteger(value) {
  return typeof value === 'number' && isFinite(value) && Math.floor(value) === value;
}

// 示例用法
console.log(isInteger(5)); // 输出: true
console.log(isInteger(5.5)); // 输出: false
console.log(isInteger('5')); // 输出: false
console.log(isInteger(null)); // 输出: false
```

这个实现利用了`typeof`操作符来检查`value`是否是一个"number"类型。然后，`isFinite(value)`检查数字是否是有限的，避免了Infinity和-Infinity。最后，`Math.floor(value) === value`检查数字是否是整数。

需要注意的是，这种方法对于整数的检查是有效的，但它也会返回`true`对于JavaScript中的浮点数，例如`5.0`。如果你需要更严格地检查整数（不希望接受5.0这样的输入），你可以将`value`转换为字符串，然后检查字符串是否表示整数。但是，请注意这种方法也会将字符串'5'视为整数，所以在具体使用时要根据需求选择合适的方法。

<br/>

### 写出输出结果

```js
function Foo() {
  getName = function () {
    alert(1);
  };
  return this;
}
var getName;
function getName() {
  alert(5);
}
Foo.getName = function () {
  alert(2);
};
Foo.prototype.getName = function () {
  alert(3);
};
getName = function () {
  alert(4);
};

Foo.getName(); // ？
getName(); // ？
Foo().getName(); // ？
getName(); // ？
new Foo.getName(); // ?
new Foo().getName(); // ?
new new Foo().getName(); // ？
```

公司：心娱

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/213)
```javascript
function Foo() {
  getName = function () {
    alert(1);
  };
  return this;
}
var getName;

function getName() {
  alert(5);
}

Foo.getName = function () {
  alert(2);
};

Foo.prototype.getName = function () {
  alert(3);
};

getName = function () {
  alert(4);
};
```

1. `Foo.getName();` 
   - 这会调用`Foo`函数对象上的`getName`方法。
   - 输出：`2`

2. `getName();`
   - 这将调用全局作用域中的`getName`函数。
   - 输出：`4`

3. `Foo().getName();`
   - 首先，`Foo()`调用函数`Foo`，它会返回全局对象（通常是`window`），并且在这个调用中`getName`函数被重新赋值为内部函数。
   - 然后，调用返回的全局对象的`getName`方法，即调用内部函数。
   - 输出：`1`

4. `getName();`
   - 这将调用全局作用域中的`getName`函数。
   - 输出：`1`

5. `new Foo.getName();`
   - 这会创建一个新的实例对象并立即调用`Foo.getName`方法。
   - 输出：`2`

6. `new Foo().getName();`
   - 首先，`new Foo()`创建一个新的`Foo`实例对象。
   - 然后，调用该实例对象上的`getName`方法，由于在`Foo`原型上定义了`getName`方法，这将调用原型上的方法。
   - 输出：`3`

7. `new new Foo().getName();`
   - 这是一个非常不寻常的表达式，其中两个`new`操作符连续出现。它将首先创建一个新的`Foo`实例对象，然后尝试再次使用`new`运算符调用该实例对象上的`getName`方法。这会导致错误。
   - 不会输出任何内容，而是抛出一个错误。

需要特别注意的是，JavaScript中的函数声明会被提升（hoisted），这意味着它们在实际执行之前会被移动到作用域的顶部。这也会影响到`getName`函数的行为，因为它在全局作用域被声明两次，但只有最后一次声明（`getName = function () {...}`）会覆盖前一次的声明。

<br/>

### 手写 dom 操作，翻转 li 标签，如何处理更优

```js
/*
 *有下边这样的dom结构，现在可以获取到ul，要求翻转里边li标签，如何处理更优
 */
<ul>
  <li>1</li>
  <li>2</li>
  <li>3</li>
</ul>
```

公司：快手

分类：

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/211)
要更优雅地翻转`<li>`标签的顺序，你可以使用以下方法：

HTML 结构示例：
```html
<ul id="myList">
  <li>1</li>
  <li>2</li>
  <li>3</li>
</ul>
```

JavaScript 代码示例：
```javascript
const ul = document.querySelector('ul');
const fragment = document.createDocumentFragment();

while (ul.firstChild) {
  fragment.appendChild(ul.lastChild);
}

ul.appendChild(fragment);
```

这段代码的步骤如下：

1. 首先，我们使用`document.querySelector`获取`<ul>`元素。

2. 然后，我们创建一个文档片段（`DocumentFragment`），这是一个轻量级的文档容器，可以用于在内存中组织DOM元素。

3. 使用`while`循环，我们将`<ul>`的最后一个子元素（即最后一个`<li>`标签）从`<ul>`中移除，并将其添加到文档片段中。这个过程会反复执行，直到`<ul>`中没有子元素。

4. 最后，我们将文档片段再次添加到`<ul>`中，这将导致`<li>`标签的顺序被反转。

这种方法不需要明确地处理`<li>`标签的顺序，而是通过将它们从一个容器移动到另一个容器来实现反转，从而避免了显式地创建和销毁元素。这有助于提高性能，特别是在处理大量DOM元素时。

<br/>

### 怎样判断一个对象是否是数组，如何处理类数组对象

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/210)
要判断一个对象是否是数组，可以使用`Array.isArray()`方法。这个方法会返回一个布尔值，如果对象是数组，则返回`true`，否则返回`false`。

例如，假设我们有一个对象`obj`，我们可以使用`Array.isArray(obj)`来判断它是否是数组。

```javascript
const obj = [1, 2, 3];
console.log(Array.isArray(obj)); // 输出 true
```

如果要处理类数组对象（array-like objects），即具有类似数组结构但不是真正的数组的对象，可以使用以下方法：

1. 转换为真正的数组：可以使用`Array.from()`方法或者扩展运算符（spread operator）`[...obj]`将类数组对象转换为真正的数组。这样就可以使用数组的方法和属性来处理它。

```javascript
const obj = { 0: 'a', 1: 'b', 2: 'c', length: 3 };

// 使用Array.from()方法
const arr1 = Array.from(obj);
console.log(arr1); // 输出 ['a', 'b', 'c']

// 使用扩展运算符
const arr2 = [...obj];
console.log(arr2); // 输出 ['a', 'b', 'c']
```

2. 使用`Array.prototype.forEach()`方法：如果不想转换为真正的数组，可以使用`forEach()`方法来迭代类数组对象的元素。

```javascript
const obj = { 0: 'a', 1: 'b', 2: 'c', length: 3 };

Array.prototype.forEach.call(obj, (element, index) => {
  console.log(`Index: ${index}, Element: ${element}`);
});
// 输出：
// Index: 0, Element: a
// Index: 1, Element: b
// Index: 2, Element: c
```

3. 使用`for...of`循环：类数组对象可以通过`for...of`循环进行迭代。

```javascript
const obj = { 0: 'a', 1: 'b', 2: 'c', length: 3 };

for (const element of obj) {
  console.log(element);
}
// 输出：
// 'a'
// 'b'
// 'c'
```

这些方法可以帮助你处理类数组对象，无论是将其转换为真正的数组，还是使用迭代方法进行处理。

<br/>

### 是否了解 glob，glob 是如何处理文件的，业界是否还有其它解决方案

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/208)
 glob 是一种常用于匹配文件路径和文件名的模式匹配工具。Glob允许你使用通配符（如`*`、`?`等）来匹配文件和文件夹的名称。在许多编程语言和工具中都有对glob模式的支持，例如Node.js中的`glob`模块、Unix/Linux命令行中的`ls`、Python中的`glob`模块等。

Glob的工作原理通常是基于以下原则：

1. `*`通配符匹配零个或多个字符。
2. `?`通配符匹配一个字符。
3. `[...]`字符集匹配包含在括号内的任何一个字符。
4. `{...}`花括号扩展，用于指定多个可能的匹配。

例如，如果你使用`*.txt`的glob模式，它将匹配所有以`.txt`结尾的文件。

虽然glob是一个常见的文件匹配工具，但也有一些替代方案，其中一些包括：

1. **正则表达式（Regular Expressions）**：正则表达式是一种更强大的模式匹配工具，可以用于匹配文件名、路径等。不过正则表达式的语法相对较复杂。

2. **`find`命令**：在Unix/Linux系统中，`find`命令可以用于查找文件和目录，支持多种条件过滤。

3. **`pathlib`（Python）**：Python的`pathlib`模块提供了更强大和面向对象的文件操作功能，可以用于匹配文件和目录。

4. **Glob的改进版本**：一些编程语言和工具提供了比标准glob更强大的文件匹配功能，例如Node.js中的`globby`和`fast-glob`模块，它们提供了更高级的匹配和性能优化功能。

5. **文件系统遍历**：有时，如果需要执行更复杂的文件操作，可以使用递归文件系统遍历，然后根据特定的条件筛选文件。

选择文件匹配工具或方法取决于你的具体需求和编程环境。如果只是简单的文件名匹配，glob通常足够了，但对于更复杂的需求，可能需要考虑使用正则表达式或其他替代方案

<br/>

### 随便打开一个网页，用 JavaScript 打印所有以 s 和 h 开头的标签，并计算出标签的种类

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/204)
要实现这个功能，你可以使用JavaScript中的DOM操作，遍历页面上的所有HTML标签，然后筛选出以"s"和"h"开头的标签，并统计其种类。以下是一个实现的方法：

```javascript
// 获取页面上的所有标签
const allTags = document.getElementsByTagName('*');

// 用于存储以"s"和"h"开头的标签及其种类
const matchedTags = {};

// 遍历所有标签
for (let i = 0; i < allTags.length; i++) {
  const tag = allTags[i].tagName.toLowerCase(); // 获取标签名，并转换为小写

  // 如果标签名以"s"或"h"开头
  if (tag.startsWith('s') || tag.startsWith('h')) {
    // 如果已经存在该标签种类，增加计数，否则初始化计数为1
    matchedTags[tag] = matchedTags[tag] ? matchedTags[tag] + 1 : 1;
  }
}

// 打印匹配的标签及其种类
console.log(matchedTags);
```

这段代码将遍历页面上的所有标签，如果标签名以"s"或"h"开头，就会将其添加到`matchedTags`对象中，并统计每种标签的数量。最终，`matchedTags`对象将包含所有以"s"和"h"开头的标签及其种类。你可以在控制台中查看输出结果。请注意，这段代码需要在浏览器的开发者工具控制台中运行，因为它依赖于DOM操作。

<br/>

### `1000*1000` 的画布，上面有飞机、子弹，如何划分区域能够更有效的做碰撞检测，类似划分区域大小与碰撞检测效率的算法，说一下大致的思路

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/203)
对于游戏或图形应用中的碰撞检测，划分区域以提高效率是一个重要的优化策略。以下是一种大致的思路，可以帮助提高碰撞检测的效率：

1. **划分画布为网格**：首先，将整个画布划分为网格，每个网格是一个矩形区域。这个网格的大小可以根据游戏的需求进行调整。通常，网格的大小应该足够小以捕捉到可能的碰撞，但也不要太小，以免引入不必要的复杂性。网格的数量通常等于画布宽度除以网格大小。

2. **对象注册到网格**：每个游戏对象（飞机、子弹等）都会被注册到一个或多个网格中，具体取决于它们的位置和大小。一个对象可以同时注册到多个网格，以确保跨网格的碰撞也能够被检测到。

3. **更新对象位置**：在每一帧中，更新游戏对象的位置。当一个对象跨越网格的边界时，需要将其从一个网格注销并注册到新的网格中。

4. **碰撞检测**：碰撞检测只需要在对象所在的网格以及相邻的网格中执行，而不是遍历整个画布。对于每个对象，只需要检查它所在网格中的其他对象以及相邻网格中的对象是否发生碰撞。这将大大减少要检查的对象数量。

5. **优化相交测试**：在每个网格中，可以进一步优化碰撞检测，例如使用边界框碰撞检测来排除不可能发生碰撞的对象。

6. **空间分区的动态调整**：如果游戏中的对象在不同帧之间移动很快，可以考虑动态调整网格的位置，以适应对象的运动。

7. **碰撞响应**：一旦检测到碰撞，需要执行适当的碰撞响应，例如更新对象的状态、分数、生命等。

这种划分区域的方法将大大减少碰撞检测的计算量，特别是在具有大量对象的情况下，能够显著提高游戏的性能。这个方法也可以灵活地根据游戏的需要进行调整，例如更改网格大小或对象注册到的网格数量。

<br/>

### 移动设备安卓与 iOS 的软键盘弹出的处理方式有什么不同

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/202)
在移动设备上，Android 和 iOS 在处理软键盘（virtual keyboard）的弹出方式上有一些不同。以下是它们的主要差异：

### Android（Android键盘）

在Android设备上，当输入框（例如文本框或文本域）获得焦点时，通常会自动弹出软键盘。开发者通常不需要太多干预，系统会自动处理键盘的弹出和收起。

在Android上，你可以通过在Activity的`AndroidManifest.xml`文件中指定`android:windowSoftInputMode`属性，来设置键盘的显示模式，例如：

- `adjustPan`：窗口不会移动，但会被压缩，让键盘能够覆盖在窗口上面。
- `adjustResize`：窗口会被整体调整大小，以便键盘能够显示在窗口的上面。

### iOS（iOS键盘）

在iOS设备上，软键盘的弹出和收起通常需要开发者更多的干预。iOS不会自动弹出软键盘，开发者需要在相应的事件（例如点击输入框时）中手动调用输入框的`focus()`方法来使得键盘弹出。

另外，在iOS上，键盘的弹出和收起通常伴随着动画效果。你可以监听键盘的弹出和收起事件，以便在键盘显示或隐藏时执行相应的操作。

总的来说，虽然Android和iOS都提供了API和事件供开发者控制和响应键盘的弹出和收起，但是在具体的使用上，可能需要根据不同平台的特性进行相应的处理。

<br/>

### iPhone 里面 Safari 上如果一个输入框 fixed 绝对定位在底部，当软键盘弹出的时候会有什么问题，如何解决

公司：快手

分类：JavaScript、Css

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/201)
在 Safari 中，当一个输入框使用 fixed 或 absolute 定位在底部时，当软键盘弹出时可能会出现一些布局问题。这是因为软键盘的弹出会改变视口的大小，可能导致固定在底部的元素被遮挡或者布局错乱。以下是一些可能的问题以及相应的解决方法：

1. **输入框被遮挡**：
   - **问题：** 当软键盘弹出时，固定在底部的输入框可能会被遮挡，用户无法看到输入的内容。
   - **解决方法：** 在输入框被遮挡时，可以通过监听软键盘弹出事件和收起事件，调整输入框的位置。可以使用 JavaScript 监听 `focus` 和 `blur` 事件，或者使用 `window.innerHeight` 的变化来检测软键盘的状态，然后相应地调整输入框的位置。

2. **页面布局错乱**：
   - **问题：** 软键盘的弹出可能导致页面布局错乱，特别是对于使用 fixed 或 absolute 定位的元素。
   - **解决方法：** 可以尝试使用 CSS 的 `position: sticky` 属性，而不是 `fixed` 或 `absolute`。`position: sticky` 在软键盘弹出时会根据上下文进行相应的调整，避免了一些布局问题。同时，确保其他元素也能适应视口大小的变化。

3. **滚动问题**：
   - **问题：** 在某些情况下，软键盘的弹出可能导致页面的滚动行为不符合预期。
   - **解决方法：** 可以尝试监听软键盘的弹出和收起事件，然后在相应事件中阻止或调整滚动行为。这可以通过 JavaScript 来实现，确保在软键盘状态变化时，适时地修改页面滚动。

4. **iOS 版本兼容性**：
   - **问题：** 不同版本的 iOS 可能对底部固定元素的处理方式有差异。
   - **解决方法：** 在实现时，最好进行一些测试，确保在不同版本的 iOS 上都能够正常工作。在出现问题时，可以考虑为特定版本的 iOS 应用不同的样式或逻辑。

综合来说，通过监听软键盘的弹出和收起事件，使用适当的 CSS 属性，以及根据具体情况调整布局，可以在 Safari 中较好地处理底部固定元素与软键盘弹出时可能出现的问题。

<br/>

### 给定一个数组，按找到每个元素右侧第一个比它大的数字，没有的话返回-1 规则返回一个数组

```js
/*
 *示例：
 *给定数组：[2,6,3,8,10,9]
 *返回数组：[6,8,8,10,-1,-1]
 */
```

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/199)
你可以使用一个栈来解决这个问题，通过遍历数组并使用栈来跟踪右侧第一个比当前元素大的数字。以下是具体的 JavaScript 代码示例：

```js
function findNextGreaterElements(arr) {
    const result = []; // 用于存放结果的数组
    const stack = []; // 用于存放索引的栈

    for (let i = 0; i < arr.length; i++) {
        // 如果栈不为空且当前元素大于栈顶元素，表示找到右侧第一个比它大的数字
        while (stack.length > 0 && arr[i] > arr[stack[stack.length - 1]]) {
            const topIndex = stack.pop(); // 弹出栈顶索引
            result[topIndex] = arr[i]; // 更新结果数组
        }
        stack.push(i); // 当前元素的索引入栈
    }

    // 处理栈中剩余的元素，它们没有右侧比它们大的数字
    while (stack.length > 0) {
        const topIndex = stack.pop();
        result[topIndex] = -1;
    }

    return result;
}

const inputArray = [2, 6, 3, 8, 10, 9];
const resultArray = findNextGreaterElements(inputArray);
console.log(resultArray); // [6, 8, 8, 10, -1, -1]
```

上面的代码首先初始化一个空栈和一个结果数组。然后，它遍历输入数组，对于每个元素，它在栈中查找右侧第一个比它大的元素，更新结果数组，同时将当前元素的索引入栈。最后，处理栈中剩余的元素，它们没有右侧比它们大的数字，将它们的结果设为-1。最终，返回结果数组。这样就得到了期望的

<br/>

### 说一说 promise，有几个状态，通过 catch 捕获到 reject 之后，在 catch 后面还能继续执行 then 方法嘛，如果能执行执行的是第几个回调函数

公司：伴鱼、喜马拉雅

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/198)
Promise 是 JavaScript 中用于处理异步操作的一种机制。Promise 可以处于三种状态之一：

1. **Pending（进行中）**：Promise 的初始状态，表示操作还在进行中，既不是成功（fulfilled）也不是失败（rejected）。

2. **Fulfilled（已成功）**：表示操作成功完成，Promise 对象的状态从 Pending 变为 Fulfilled，此时会调用 `.then()` 方法中的回调函数。

3. **Rejected（已失败）**：表示操作失败，Promise 对象的状态从 Pending 变为 Rejected，此时会调用 `.catch()` 或者 `.then(null, rejectionHandler)` 方法中的回调函数。

当 Promise 的状态变为 Rejected，并且没有提供 `.catch()` 方法或者 `.then(null, rejectionHandler)` 方法来处理错误的情况下，错误会被抛出到 JavaScript 运行时环境，可能导致未捕获的异常。

如果在 `.catch()` 方法中捕获到了错误，后续的 `.then()` 方法仍然可以被执行。这是 Promise 链式调用的一个关键特性。在 Promise 链中，只要某个 Promise 的状态变为 Rejected，就会跳过所有后续的 `.then()` 方法，直到遇到 `.catch()` 方法或者下一个 `.then(null, rejectionHandler)` 方法。

以下是一个示例：

```javascript
function asyncTask() {
  return new Promise((resolve, reject) => {
    setTimeout(() => {
      // 模拟异步操作
      const randomNumber = Math.random();
      if (randomNumber < 0.5) {
        resolve(randomNumber); // 成功，状态变为 Fulfilled
      } else {
        reject('Error: Operation failed'); // 失败，状态变为 Rejected
      }
    }, 1000);
  });
}

asyncTask()
  .then(result => {
    console.log('Success:', result);
    return result + 1;
  })
  .catch(error => {
    console.error('Error:', error);
    return 'Default Value'; // 在 catch 中处理错误，并返回默认值
  })
  .then(finalResult => {
    console.log('Final Result:', finalResult);
  });
```

在上面的示例中，如果异步操作成功，将会输出 `Success:` 和 `Final Result:`，并且后续 `.then()` 方法的结果会传递给下一个 `.then()` 方法。如果异步操作失败，将会输出 `Error:` 和 `Final Result:`，并且 `.catch()` 方法中返回的默认值会传递给下一个 `.then()` 方法。

<br/>

### var、let、const 的区别

公司：伴鱼、百分点、心娱

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/197)
`var`、`let`和`const`是 JavaScript 中用于声明变量的关键字，它们之间有一些区别。

1. **作用域：**
   - `var`：`var` 声明的变量具有函数作用域，即在声明它的函数内部可见。如果在函数内部使用 `var` 声明的变量没有使用 `var` 关键字，它将成为全局变量。
   - `let` 和 `const`：`let` 和 `const` 声明的变量具有块级作用域，即在声明它的块（例如，if语句、for循环等）内部可见。

2. **变量提升：**
   - `var`：`var` 声明的变量会进行变量提升，即在声明之前就可以访问变量，但其值为 `undefined`。这意味着可以在变量声明之前使用变量，但是变量的赋值操作需要在声明之后进行。
   - `let` 和 `const`：`let` 和 `const` 声明的变量不会进行变量提升，即在声明之前访问变量会导致引用错误。

3. **重复声明：**
   - `var`：可以重复声明同一个变量，而且不会引发错误。后续的声明将覆盖之前的声明。
   - `let` 和 `const`：不允许在同一作用域内重复声明同一个变量。如果尝试重复声明，将引发语法错误。

4. **可变性：**
   - `var` 和 `let`：声明的变量可以重新赋值。
   - `const`：声明的变量是常量，不可重新赋值。但是，对于复合类型（如数组和对象），其内部的属性或元素仍然可以修改。

5. **暂时性死区（Temporal Dead Zone，TDZ）：**
   - `let` 和 `const`：在块级作用域中，使用 `let` 或 `const` 声明的变量会在声明之前形成一个暂时性死区。在暂时性死区中，如果尝试访问变量，将会抛出引用错误。

6. **全局对象属性：**
   - `var`：使用 `var` 声明的全局变量会成为全局对象（如 `window`）的属性。
   - `let` 和 `const`：在全局作用域中使用 `let` 或 `const` 声明的变量不会成为全局对象的属性。

综上所述，`var`、`let`和`const`在作用域、变量提升、重复声明、可变性、暂时性死区和全局对象属性等方面有所不同。在现代 JavaScript 中，推荐使用 `let` 和 `const` 来声明变量，因为它们提供了更好的作用域控制和更严格的变量声明规则。

<br/>

### 说一下 GC

公司：伴鱼

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/195)
GC（Garbage Collection，垃圾回收）是一种自动管理计算机程序中内存的机制，用于跟踪程序中不再使用的对象，并自动释放这些对象所占用的内存空间。垃圾回收是现代编程语言中的一项重要功能，它帮助开发者避免手动释放内存的繁琐工作，从而提高了编程的效率和可靠性。

在主要的编程语言中，垃圾回收通常基于以下两个原则：

### 1. 引用计数法（Reference Counting）

引用计数法是一种最简单的垃圾回收算法，它基于一个简单的思想：对象被引用时，计数器加1；当引用被删除时，计数器减1。当计数器为零时，对象就可以被回收。

然而，引用计数法并不是一种完美的垃圾回收方式，因为它无法处理循环引用（两个或多个对象相互引用，但被其他部分程序不再引用），导致循环引用的对象无法被垃圾回收，从而可能引发内存泄漏。

### 2. 标记-清除法（Mark and Sweep）

标记-清除法是一种更为复杂但也更可靠的垃圾回收算法。该算法分两个阶段：

- **标记阶段**：垃圾回收器会从根对象（例如全局对象、调用栈等）出发，递归地标记所有能够被引用到的对象。所有未被标记的对象将被认定为垃圾。

- **清除阶段**：垃圾回收器会遍历所有对象，清除未被标记的对象，即回收垃圾。这样，被标记的对象就会被保留，未被标记的对象会被释放。

标记-清除法能够解决引用计数法中的循环引用问题，但也有一定的性能开销，因为在标记和清除的过程中，程序的运行可能会被暂停。

现代的 JavaScript 引擎（例如V8引擎）通常使用基于标记-清除法的垃圾回收算法，同时结合了一些优化策略，例如分代垃圾回收（Generational Garbage Collection），这样可以在不同情况下选择合适的垃圾回收策略，以提高性能。

<br/>

### 如何实现按需加载

公司：伴鱼、腾讯应用宝

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/189)
按需加载（也称为懒加载）是一种优化网页性能的技术，它允许在需要时延迟加载资源，而不是一次性加载所有资源。这可以减少初始加载时间，提高页面加载速度。以下是一些实现按需加载的常用方法：

1. **条件加载：** 使用条件语句（如 `if`）来判断是否需要加载某个资源。例如，在滚动到页面底部时，可以使用 JavaScript 监听滚动事件，并在满足条件时动态加载更多内容。

2. **延迟加载：** 使用 `defer` 或 `async` 属性来延迟脚本的加载和执行。`defer` 属性用于延迟脚本的执行，直到文档解析完成。`async` 属性用于异步加载脚本，不会阻塞页面的解析和渲染。这样可以确保脚本在需要时才会加载和执行。

3. **动态创建元素：** 使用 JavaScript 动态创建 `<script>`、`<link>` 或 `<img>` 等元素，并将它们添加到文档中。通过在需要时创建元素并设置其 `src` 或 `href` 属性，可以实现按需加载。例如，当用户点击某个按钮时，动态创建一个 `<script>` 元素来加载相关的 JavaScript 文件。

4. **模块化加载：** 使用模块化加载器（如 RequireJS、SystemJS 或 webpack）来按需加载模块。模块化加载器可以将代码拆分为多个模块，并在需要时动态加载这些模块。这样可以减少初始加载时间，并根据需要加载所需的模块。

5. **图片懒加载：** 对于页面中的图片，可以使用懒加载技术来延迟加载图片。当图片进入可视区域时，再进行加载。这可以通过监听滚动事件并计算图片位置来实现。

6. **异步加载资源：** 使用异步加载资源的方式，如使用 AJAX 或 Fetch API 异步加载数据，或使用动态创建 `<script>` 元素来异步加载 JavaScript 文件。这样可以在需要时才加载资源，而不会阻塞页面的加载和渲染。

以上是一些常用的按需加载技术和方法。根据具体的应用场景和需求，可以选择适合的方法来实现按需加载，以提高网页性能和用户体验。

<br/>

### 讲一下 import 的原理，与 require 有什么不同

公司：伴鱼、腾讯应用宝

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/188)
`import` 和 `require` 是两种在 JavaScript 中用于导入模块的不同语法。它们在ES6和CommonJS规范中分别被引入。

### 1. `import` 的原理：

- `import` 是ES6中的模块加载系统的一部分，它允许你按名称导入其他模块中导出的功能（变量、函数、类等）。

- `import` 是一种静态导入，意味着导入的模块路径必须是字符串常量，不能在运行时动态生成。

- `import` 语句在代码执行前会被处理，因此它在模块的顶层上下文执行，而不是在函数或块级作用域中执行。这意味着它不会受到变量提升的影响。

- `import` 语句是异步加载的，它会等待所有依赖模块都被下载和解析完成，然后再执行模块的代码。这种行为通常被称为"静态结构"，因为它在编译时就确定了模块的依赖关系。

```javascript
// ES6 的 import 语法
import { functionName } from 'module-name';
```

### 2. `require` 的原理：

- `require` 是CommonJS规范中的模块加载系统的一部分，它允许你同步或异步地导入其他模块中导出的功能。

- `require` 是一种动态导入，它可以接受表达式作为参数，因此可以在运行时动态生成导入路径。

- `require` 语句是同步加载的，它会在代码执行到 `require` 语句时立即加载并执行模块，然后将导出的对象返回。这种行为通常被称为"动态结构"，因为它在运行时确定了模块的依赖关系。

- 在Node.js环境中，`require` 是同步的，但在一些前端工程中，例如使用Webpack等构建工具时，也可以使用异步的 `import()` 语法。

```javascript
// CommonJS 的 require 语法
const moduleName = require('module-name');
```

### 不同点总结：

- `import` 是ES6的语法，`require` 是CommonJS的语法。

- `import` 是静态导入，`require` 是动态导入。

- `import` 是异步加载的，`require` 是同步加载的（在Node.js环境中）。

- `import` 语句在模块的顶层上下文执行，`require` 语句可以在函数或块级作用域中执行。

<br/>

### 请实现如下的函数

```js
/*
	可以批量请求数据，所有的 URL 地址在 urls 参数中，同时可以通过 max 参数控制请求的并发度，当所有请求结束之后，需要执行 callback 回调函数。发请求的函数可以直接使用 fetch 即可
*/
```

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/185)
你可以使用 JavaScript 的 `fetch` 函数和 `Promise` 来实现这个需求。下面是一个实现批量请求数据的函数：

```javascript
function fetchDataBatch(urls, max, callback) {
  const results = []; // 存储请求结果
  let completed = 0; // 记录已完成的请求数量
  let index = 0; // 记录当前请求的 URL 索引

  function fetchUrl(url) {
    return fetch(url)
      .then(response => response.json())
      .then(data => {
        results[index] = data; // 将请求结果保存到对应的位置
        completed++; // 完成的请求数加1

        // 如果所有请求已完成，则执行回调函数
        if (completed === urls.length) {
          callback(results);
        } else if (index < urls.length) {
          // 如果还有未处理的 URL，则继续发起请求
          fetchUrl(urls[index]);
          index++;
        }
      })
      .catch(error => {
        console.error('Error fetching data:', error);
        // 如果请求失败，继续处理下一个 URL
        index++;
        if (index < urls.length) {
          fetchUrl(urls[index]);
        }
      });
  }

  // 控制并发请求数量，最多同时发起 max 个请求
  for (let i = 0; i < Math.min(max, urls.length); i++) {
    fetchUrl(urls[i]);
    index++;
  }
}

// 示例用法
const urls = ['url1', 'url2', 'url3']; // 要请求的 URL 列表
const maxConcurrentRequests = 2; // 最大并发请求数量
const callback = function(results) {
  console.log('All requests completed:', results);
};

fetchDataBatch(urls, maxConcurrentRequests, callback);
```

在这个示例中，`fetchDataBatch` 函数接受三个参数：`urls` 包含了所有要请求的 URL 地址，`max` 是最大的并发请求数量，`callback` 是所有请求完成后执行的回调函数。函数内部使用递归和 `Promise` 控制请求的并发度，并将结果保存到 `results` 数组中。当所有请求完成后，调用回调函数并传递请求结果。

<br/>

### 是否用过 restful 接口，和其他风格的有什么区别

公司：边锋

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/175)
是的，我熟悉 RESTful 接口。REST（Representational State Transfer）是一种软件架构风格，用于构建可扩展的网络应用程序。RESTful 接口是符合 REST 原则的接口设计。

RESTful 接口与其他风格的接口设计有以下区别：

1. **统一接口：** RESTful 接口使用统一的接口设计原则，包括使用标准的 HTTP 方法（如 GET、POST、PUT、DELETE）来表示对资源的不同操作，使用 URI（统一资源标识符）来标识资源，使用 HTTP 状态码来表示请求的结果。

2. **无状态性：** RESTful 接口是无状态的，即服务器不会保存客户端的状态信息。每个请求都应该包含足够的信息，以便服务器理解和处理请求。这样可以提高系统的可伸缩性和可靠性。

3. **资源导向：** RESTful 接口将系统中的数据和功能抽象为资源，并通过 URI 来标识这些资源。客户端可以使用 HTTP 方法对资源进行操作，如 GET 获取资源，POST 创建资源，PUT 更新资源，DELETE 删除资源。

4. **自描述性：** RESTful 接口应该是自描述的，即客户端可以通过资源的 URI 和 HTTP 方法来理解如何与服务器进行交互。此外，可以使用标准的媒体类型（如 JSON、XML）来表示资源的表现形式，使客户端和服务器之间的通信更加灵活和可扩展。

5. **超媒体驱动：** RESTful 接口可以使用超媒体（HATEOAS）来驱动客户端的导航和操作。服务器可以在响应中包含链接和相关资源的信息，使客户端能够动态地发现和访问其他资源。

与其他风格的接口设计相比，RESTful 接口具有以下优点：

- 简单性：RESTful 接口使用标准的 HTTP 方法和 URI，易于理解和使用。
- 可扩展性：通过使用资源和超媒体，RESTful 接口可以支持系统的演化和扩展。
- 可见性：RESTful 接口的设计可以使资源和操作对客户端可见，提高系统的可发现性和可用性。
- 松耦合性：RESTful 接口通过使用无状态性和资源导向的设计原则，实现了客户端和服务器之间的松耦合。

总之，RESTful 接口是一种基于统一接口、无状态性、资源导向、自描述性和超媒体驱动的接口设计风格，具有简单性、可扩展性、可见性和松耦合性的优点。

<br/>

### 说一下 get、post、put 的区别

公司：边锋、虎扑、酷家乐、酷狗、安居客

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/174)
`GET`、`POST` 和 `PUT` 是 HTTP 协议中的不同请求方法（Request Methods），用于在客户端和服务器之间进行数据交换。它们在使用时有一些明显的区别：

#### 1. GET 请求：

- `GET` 请求用于请求指定的资源。它是一种幂等（Idempotent）方法，多次请求相同的资源返回的结果应该相同。
- GET 请求将请求参数附加在 URL 的末尾（例如 `https://example.com/resource?param1=value1&param2=value2`）。
- GET 请求通常用于获取数据，不应该用于发送敏感数据，因为请求参数会暴露在 URL 中，可能会被浏览器保存在历史记录或服务器日志中。

#### 2. POST 请求：

- `POST` 请求用于向服务器提交数据，常用于表单提交、文件上传等场景。
- POST 请求将请求参数放在请求体（Request Body）中，而不是在 URL 中，因此它相对于 GET 请求更安全，可以用于传递敏感数据。
- POST 请求不是幂等的，多次提交相同的数据可能会导致不同的结果。

#### 3. PUT 请求：

- `PUT` 请求用于更新或替换服务器上的资源，客户端通常提供完整的资源数据。
- PUT 请求也是幂等的，多次使用相同的请求不会对资源产生不同的影响，因此可以多次安全地发送。
- PUT 请求和 POST 请求的区别在于 PUT 请求通常用于更新已知资源，而 POST 请求用于创建新资源。

总结：

- `GET` 用于获取资源。
- `POST` 用于向服务器提交数据。
- `PUT` 用于更新或替换服务器上的资源。

使用哪种请求方法取决于你的具体需求。GET 用于读取数据，POST 用于创建新数据，PUT 用于更新数据。

<br/>

### 说一下对面向对象的理解，面向对象有什么好处

公司：边锋

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/173)
面向对象编程（Object-Oriented Programming，OOP）是一种常用的编程范式，它以对象为中心，将数据和操作数据的方法封装在一起，以模拟现实世界中的实体和其交互。下面是对面向对象的理解以及它的好处的详细回答：

**面向对象的理解：**

面向对象编程基于以下核心概念：

1. **类（Class）：** 类是一种抽象数据类型，它定义了对象的属性（成员变量）和行为（成员方法）。类可以看作是对象的模板或蓝图。

2. **对象（Object）：** 对象是类的实例，它包含了类定义的属性和方法。对象是程序中的实体，可以通过类来创建多个对象。

3. **封装（Encapsulation）：** 封装是将数据和操作数据的方法封装在一起的概念。这意味着对象的内部细节对外部是隐藏的，只有通过对象的公共接口（方法）才能访问对象的状态。

4. **继承（Inheritance）：** 继承是一种机制，它允许一个类继承另一个类的属性和方法。这可以促进代码的重用和扩展。

5. **多态（Polymorphism）：** 多态允许不同的对象对相同的方法做出不同的响应。这通过方法的重写和方法的重载来实现。

**面向对象的好处：**

1. **模块化和可维护性：** 面向对象编程通过类的封装将复杂系统分解为小的、可维护的模块。这使得代码更易于理解、维护和扩展。

2. **代码重用：** 继承和多态使得代码重用更加容易。你可以创建一个通用的基类，然后派生出不同的子类，以实现特定的功能，而不必从头开始编写新代码。

3. **可扩展性：** 面向对象编程支持代码的可扩展性。你可以添加新类和方法，而不会影响现有的代码。

4. **抽象和模拟现实世界：** 面向对象编程允许你模拟现实世界中的实体和其关系，这有助于更好地理解和解决问题。

5. **团队协作：** 面向对象编程的结构性特点使不同团队成员能够独立开发和测试各自的模块，然后集成到整个系统中。

6. **安全性：** 封装可以隐藏对象的内部状态，只允许通过公共接口来访问，从而提高了数据的安全性。

7. **可读性和可维护性：** 面向对象编程通常导致更具可读性的代码，因为它使用了自然语言的类和方法命名约定，使代码更易于理解和维护。

总的来说，面向对象编程是一种强大的编程范式，它通过封装、继承、多态等概念提供了代码组织和设计的有效方法，有助于构建可维护、可扩展和高效的软件

<br/>

### 类设计：使用面相对象设计一个停车场管理系

```js
/*
 *题目要求
 *使用面相对象设计一个停车场管理系统，该停车场包含：
 *	1.停车位，用于停放车辆；
 *	2.停车位提示牌，用于展示剩余停车位；
 *可以丰富该系统的元素，给出类，类属性，类接口。
 */
```

公司：边锋

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/171)
在设计停车场管理系统时，我们可以定义以下类来实现系统的功能：

#### 类1: `ParkingLot`

- **属性：**
  - `totalSpaces`: 总停车位数量
  - `availableSpaces`: 可用停车位数量
  - `occupiedSpaces`: 已占用停车位数量
  - `parkedVehicles`: 已停放的车辆列表

- **方法：**
  - `parkVehicle(vehicle)`: 停车，将车辆放入停车场。如果有空位，返回 true，否则返回 false。
  - `removeVehicle(vehicle)`: 取车，将车辆从停车场移出。如果车辆存在且被成功移出，返回 true，否则返回 false。
  - `getAvailableSpaces()`: 获取可用停车位数量。
  - `getOccupiedSpaces()`: 获取已占用停车位数量。
  - `displayParkingStatus()`: 展示当前停车场状态，包括总停车位数、可用停车位数和已占用停车位数。

#### 类2: `ParkingSpace`

- **属性：**
  - `number`: 停车位编号
  - `isOccupied`: 是否被占用的标志（布尔值）

- **方法：**
  - `occupy()`: 占用该停车位。
  - `vacate()`: 释放该停车位。

#### 类3: `Vehicle`

- **属性：**
  - `licensePlate`: 车牌号
  - `type`: 车辆类型（例如小型车、大型车等）

这样，我们就可以在 `ParkingLot` 类中使用 `ParkingSpace` 类的实例来表示停车场中的每个停车位。当车辆进入停车场时，我们可以将其信息存储在 `ParkedVehicle` 类的实例中，包括车牌号和停车位编号。当车辆离开停车场时，我们可以根据车牌号找到对应的停车位，将其标记为空闲状态。

这只是一个简单的停车场管理系统的设计概念。在实际应用中，你可能还需要考虑更多的功能，例如停车费用计算、不同车辆类型的收费标准、停车场安全等级等。

<br/>

### 实现输出一个十六进制的随机颜色(#af0128a)

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/170)

<br/>



### 手写代码实现`kuai-shou-front-end=>KuaiShouFrontEnd`

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/168)

```javascript
function getRandomColor() {
  // 生成随机的RGB颜色值
  var randomColor = Math.floor(Math.random()*16777215).toString(16);

  // 补全颜色值，确保为六位
  while(randomColor.length < 6){
    randomColor = "0" + randomColor;
  }

  // 添加十六进制颜色标识符"#"
  randomColor = "#" + randomColor;

  return randomColor;
}

// 获取随机颜色并输出
var randomHexColor = getRandomColor();
console.log("随机颜色: " + randomHexColor);
```

这个代码中，我们定义了一个`getRandomColor`函数，它生成一个随机的六位十六进制颜色值。

具体步骤如下：

1. 使用`Math.random()`生成一个0到1之间的随机小数。

2. 将该随机小数乘以`16777215`，这是十六进制颜色的最大值，得到一个随机的RGB颜色值。

3. 使用`.toString(16)`将RGB颜色值转换为十六进制字符串。

4. 如果转换后的字符串长度不足6位，使用`while`循环在前面补充0，确保为六位。

5. 添加十六进制颜色标识符"#”。

6. 返回最终的随机颜色值。

通过调用`getRandomColor`函数，你可以获取一个随机的十六进制颜色值，并在控制台输出。例如，运行上述代码可能会输出类似"随机颜色: #1a4f8c"的结果。

这个方法是通过生成随机的RGB颜色值，然后将其转换为十六进制表示的。希望这个代码满足你的需求！

```javascript
function convertToCamelCase(string) {
  // 将字符串按照"-"分割成单词数组
  var words = string.split("-");
  
  // 将每个单词的首字母大写，并拼接起来
  var camelCase = words.map(function(word, index) {
    // 对第一个单词不进行首字母大写处理
    if (index === 0) {
      return word;
    }
    return word.charAt(0).toUpperCase() + word.slice(1);
  }).join("");
  
  return camelCase;
}

// 转换字符串为驼峰命名格式
var inputString = "kuai-shou-front-end";
var camelCaseString = convertToCamelCase(inputString);

console.log("驼峰命名格式: " + camelCaseString);
```

这个代码中，我们定义了一个`convertToCamelCase`函数，它接受一个字符串作为输入，并将其转换为驼峰命名格式。

具体步骤如下：

1. 使用`string.split("-")`将输入的字符串按照"-"进行分割，得到一个单词数组。

2. 使用`map`方法遍历单词数组，并对每个单词进行处理。对于第一个单词，我们不进行首字母大写处理，直接返回原单词。对于其他单词，我们使用`charAt(0).toUpperCase() + word.slice(1)`将首字母大写，并将剩余部分拼接起来。

3. 使用`join("")`将每个单词拼接起来，形成最终的驼峰命名格式的字符串。

4. 最后，将转换后的字符串返回。

通过调用`convertToCamelCase`函数，你可以将"kuai-shou-front-end"转换为"KuaiShouFrontEnd"。例如，运行上述代码可能会在控制台输出"驼峰命名格式: KuaiShouFrontEnd"。

请注意，这个代码示例假设输入的字符串中的单词是以"-"分隔的。如果你的实际需求中使用的是其他分隔符，你可以相应地修改代码中的分隔符。

<br/>

### 设计一个 Student 组件，实现输入姓名性别成绩（这三个必填），还有几个不是必填的属性，要设置默认值，点击弹出成绩

公司：老虎

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/163)

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Student Information</title>
  <style>
    #student-info {
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <div id="student-info">
    <p><strong>Name:</strong> <span id="name"></span></p>
    <p><strong>Gender:</strong> <span id="gender"></span></p>
    <p><strong>Score:</strong> <span id="score"></span></p>
    <p><strong>Age:</strong> <span id="age"></span></p>
    <p><strong>Grade:</strong> <span id="grade"></span></p>
    <button onclick="showScore()">Show Score</button>
  </div>

  <script>
    function showScore() {
      var name = prompt("Enter Name:");
      var gender = prompt("Enter Gender:");
      var score = parseFloat(prompt("Enter Score:"));
      var age = prompt("Enter Age (default is 18):") || 18;
      var grade = prompt("Enter Grade (default is 'A'):") || 'A';

      document.getElementById("name").textContent = name;
      document.getElementById("gender").textContent = gender;
      document.getElementById("score").textContent = score;
      document.getElementById("age").textContent = age;
      document.getElementById("grade").textContent = grade;
    }
  </script>
</body>
</html>
```

在这个示例中，当用户点击 "Show Score" 按钮时，会通过 `prompt` 函数获取用户输入的信息，然后将信息显示在页面上。这是一个基本的示例，你可以根据你的需求进一步扩展和定制。

<br/>

### 设计一个函数，奇数次执行的时候打印 1，偶数次执行的时候打印 2

公司：老虎

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/162)
你可以使用一个闭包来实现这个需求。闭包是一个函数和它的词法环境的组合，可以记录函数定义时的外部变量。以下是一个可以实现奇数次执行时打印1，偶数次执行时打印2的函数：

```javascript
function createCounter() {
  let count = 0; // 用于记录函数调用次数

  return function() {
    count++; // 每次调用增加计数器

    if (count % 2 === 1) {
      console.log(1); // 如果调用次数为奇数，打印1
    } else {
      console.log(2); // 如果调用次数为偶数，打印2
    }
  };
}

const printOddEven = createCounter();

// 调用函数，观察输出
printOddEven(); // 输出 1
printOddEven(); // 输出 2
printOddEven(); // 输出 1
printOddEven(); // 输出 2
```

在这个例子中，`createCounter` 函数返回了一个闭包，它可以记录调用次数。每次调用 `printOddEven` 函数时，闭包中的 `count` 变量会被增加。如果 `count` 是奇数，打印1，如果是偶数，打印2。这样，你每次调用 `printOddEven` 函数时，都会根据调用次数打印不同的结果。

<br/>

### 实现 Promise.then

公司：高德、百分点

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/161)
当你调用 `Promise.then` 方法时，你可以将一个回调函数作为参数传递给它。这个回调函数将在 Promise 对象的状态变为 resolved（已解决）时被调用，并且会接收到 Promise 对象的解决值作为参数。

下面是一个简单的示例，展示了如何实现一个自定义的 `Promise` 类，并在其中实现 `then` 方法：

```javascript
class MyPromise {
  constructor(executor) {
    this.state = 'pending';
    this.value = undefined;
    this.onResolvedCallbacks = [];

    const resolve = (value) => {
      if (this.state === 'pending') {
        this.state = 'resolved';
        this.value = value;
        this.onResolvedCallbacks.forEach(callback => callback(this.value));
      }
    };

    executor(resolve);
  }

  then(callback) {
    if (this.state === 'resolved') {
      callback(this.value);
    } else {
      this.onResolvedCallbacks.push(callback);
    }
  }
}

// 创建一个 Promise 对象
const myPromise = new MyPromise((resolve) => {
  setTimeout(() => {
    resolve('Hello, Promise!');
  }, 2000);
});

// 调用 then 方法，传入回调函数
myPromise.then((value) => {
  console.log(value);
});
```

在这个示例中，我们定义了一个 `MyPromise` 类，它接受一个 `executor` 函数作为参数。`executor` 函数在创建 `MyPromise` 实例时立即执行，并接收一个 `resolve` 函数作为参数。

在 `resolve` 函数内部，我们首先检查当前 `MyPromise` 实例的状态是否为 `'pending'`。如果是，我们将状态改为 `'resolved'`，并将传入的值赋给 `this.value`。然后，我们遍历 `this.onResolvedCallbacks` 数组，依次调用其中的回调函数，并将 `this.value` 作为参数传递给它们。

`then` 方法用于注册回调函数。如果当前 `MyPromise` 实例的状态已经是 `'resolved'`，则直接调用传入的回调函数，并将 `this.value` 作为参数传递给它。否则，将回调函数添加到 `this.onResolvedCallbacks` 数组中，以便在状态变为 `'resolved'` 时调用。

在示例中，我们创建了一个 `MyPromise` 实例，并在 2 秒后将其状态改为 `'resolved'`，并传递 `'Hello, Promise!'` 作为解决值。然后，我们调用 `then` 方法，传入一个回调函数，以便在 `MyPromise` 实例的状态变为 `'resolved'` 时被调用。在回调函数中，我们将接收到的值打印到控制台上。

这就是一个简单的 `Promise.then` 方法的实现。当然，实际的 `Promise` 实现要更复杂，还需要处理错误处理、链式调用等功能。但是这个示例可以帮助你理解 `Promise.then` 方法的基本原理。

<br/>

### 平时在项目开发中都做过哪些前端性能优化

公司：阿里、顺丰、易车、有赞、挖财、喜马拉雅、兑吧、寺库、海康威视、道一云、58

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/160)
前端性能优化是提高网站或应用性能、用户体验和搜索引擎排名的关键步骤。以下是一些常见的前端性能优化技术，它们可以应用于各种类型的项目：

1. **减少 HTTP 请求：**
   - 合并和压缩文件（CSS、JavaScript、图片等）以减少请求次数。
   - 使用 CSS 精灵图合并小图标，减少图片请求。
   - 使用字体图标替代图像图标，减少图片请求。

2. **使用 CDN（内容分发网络）：**
   - 将静态资源（例如库、框架、样式表、脚本等）托管在 CDN 上，加速资源加载。

3. **优化图片：**
   - 使用适当的图片格式（如WebP）。
   - 选择正确的图片分辨率和质量。
   - 使用懒加载（Lazy Loading）加载屏幕上方的图片。

4. **使用浏览器缓存：**
   - 设置适当的缓存头，使得浏览器能够缓存静态资源。
   - 使用 Service Workers 实现离线缓存。

5. **使用异步加载和延迟加载：**
   - 使用 `async` 或 `defer` 属性加载 JavaScript 文件，确保不会阻塞页面渲染。
   - 将不关键的脚本推迟到页面加载完成后再加载。

6. **代码优化：**
   - 将 JavaScript 和 CSS 文件进行压缩和混淆。
   - 删除不必要的注释和空格。
   - 避免使用全局变量，使用模块化的开发方式。
   - 使用事件委托来减少事件处理器的数量。

7. **前端框架和库的优化：**
   - 选择轻量级的框架或库，避免引入不必要的功能。
   - 及时更新框架和库版本，以获取性能改进。

8. **网络请求的优化：**
   - 使用 HTTP/2 协议，它支持多路复用、头部压缩等特性。
   - 减小接口返回的数据量，使用分页加载和惰性加载。

9. **页面渲染性能优化：**
   - 避免使用表格布局，使用 CSS Flexbox 和 Grid 布局。
   - 使用 CSS 动画替代 JavaScript 动画，因为它们可以利用硬件加速。
   - 将脚本放在页面底部，确保页面内容能够快速加载。

10. **监控和分析性能：**
    - 使用性能分析工具（如Chrome开发者工具）来检测性能问题。
    - 使用实时监控工具，了解用户在不同地区和设备上的性能体验。

这些是一些常见的前端性能优化技术。在实际项目中，根据具体的需求和项目特点，可能需要选择性地应用这些技术，以便在不影响功能和用户体验的前提下提高网站或应用的性能。

<br/>

### 给定起止日期，返回中间的所有月份

```js
// 输入两个字符串 2018-08  2018-12
// 输出他们中间的月份 [2018-9,2018-10, 2018-11]
```

公司：顺丰

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/159)
要实现给定起止日期，返回中间的所有月份的功能，你可以按照以下步骤进行：

1. 将输入的字符串日期解析为 JavaScript 的 Date 对象，以便进行日期计算。
2. 获取起止日期之间的所有月份。
3. 将每个月份转换为指定格式的字符串。

下面是一个实现这个功能的 JavaScript 代码：

```js
function getMonthsBetweenDates(startDateStr, endDateStr) {
  // 解析输入日期字符串为 Date 对象
  const startDate = new Date(startDateStr);
  const endDate = new Date(endDateStr);

  // 存储中间的月份
  const months = [];

  // 循环遍历每个月
  let currentDate = new Date(startDate);
  while (currentDate <= endDate) {
    const year = currentDate.getFullYear();
    const month = currentDate.getMonth() + 1; // 月份从0开始，需要加1
    const formattedMonth = `${year}-${month < 10 ? '0' : ''}${month}`;
    
    // 将格式化后的月份字符串存入数组
    months.push(formattedMonth);

    // 增加一个月
    currentDate.setMonth(currentDate.getMonth() + 1);
  }

  return months.slice(0, -1); // 去掉结束日期所在的月份
}

// 输入两个字符串日期
const startDateStr = '2018-08';
const endDateStr = '2018-12';

// 获取中间的月份
const result = getMonthsBetweenDates(startDateStr, endDateStr);

// 输出结果
console.log(result); // 输出 [ '2018-09', '2018-10', '2018-11' ]
```

在这个例子中，`getMonthsBetweenDates` 函数接收两个字符串日期作为输入，并返回一个包含中间月份的数组。在函数内部，我们首先解析输入的日期字符串为 Date 对象，然后使用循环遍历每个月，将每个月的年份和月份格式化为字符串，并存入数组中。最后，返回数组结果。

希望这个例子能够满足你的需求！

<br/>

### 按要求实现代码

```js
// 给两个数组 [A1,A2,B1,B2,C1,C2,D1,D2] [A,B,C,D]
// 输出 [A1,A2,A,B1,B2,B,C1,C2,C,D1,D2,D]
```

公司：顺丰

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/158)
你可以使用 JavaScript 来实现这个需求，首先将两个数组合并，然后根据元素的字符进行排序。以下是实现的代码：

```javascript
const arr1 = ['A1', 'A2', 'B1', 'B2', 'C1', 'C2', 'D1', 'D2'];
const arr2 = ['A', 'B', 'C', 'D'];

// 合并两个数组
const mergedArray = [...arr1, ...arr2];

// 对合并后的数组进行排序
mergedArray.sort((a, b) => {
  const charA = a[0];
  const charB = b[0];
  
  if (charA < charB) {
    return -1;
  } else if (charA > charB) {
    return 1;
  } else {
    return a.localeCompare(b); // 对相同字符的元素按字符串排序
  }
});

console.log(mergedArray);
```

这段代码首先使用扩展运算符 `...` 合并两个数组，然后使用 `sort` 方法对合并后的数组进行排序。排序时，首先按照元素的第一个字符进行比较，然后对相同字符的元素按字符串进行排序，最终得到按要求排序的数组。

<br/>

### 用尽量短的代码实现一个 arrary 的链式操作，将数组中的大于 10 的值进行一个累加

公司：顺丰

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/156)
你可以使用数组的 `reduce` 方法来实现这个链式操作，将数组中大于 10 的值进行累加。以下是代码示例：

```js
const result = [1, 5, 12, 8, 15, 3]
  .filter(item => item > 10)   // 过滤出大于 10 的元素
  .reduce((acc, currentValue) => acc + currentValue, 0);  // 对符合条件的元素进行累加

console.log(result); // 输出 27
```

让我来解释一下上面的代码：

1. `filter(item => item > 10)` 会过滤数组中所有大于 10 的元素，返回一个新的数组 `[12, 15]`。

2. `.reduce((acc, currentValue) => acc + currentValue, 0)` 用于将数组中的元素累加起来。`reduce` 接受两个参数，一个是回调函数，另一个是初始值。回调函数接受两个参数，第一个是累加器 `acc`，第二个是当前元素 `currentValue`。

   - `acc` 用于累积结果，初始值为 `0`。
   
   - `currentValue` 是数组中的每一个大于 10 的元素。

   在回调函数中，我们将累加器和当前元素相加，并返回结果。

最终，`reduce` 方法会将所有符合条件的元素进行累加，得到最终的结果。

在这个例子中，数组 `[1, 5, 12, 8, 15, 3]` 中大于 10 的元素是 `[12, 15]`，它们的和是 `27`。

这样，我们就通过链式操作实现了将数组中大于 10 的值进行累加的功能。希望这符合你的要求！如果你有任何问题或者需要进一步的解释，请随时告诉我。

<br/>

### 简单封装一个异步 fecth，使用 async await 的方式来使用

公司：顺丰

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/155)
当封装一个异步的 `fetch` 请求时，可以使用 `async/await` 来简化异步操作的处理。下面是一个简单的示例，展示如何封装一个使用 `async/await` 的异步 `fetch` 函数：

```js
async function fetchData(url) {
  try {
    const response = await fetch(url); // 发起异步请求并等待响应
    const data = await response.json(); // 解析响应数据为 JSON 格式
    return data; // 返回解析后的数据
  } catch (error) {
    console.error('Error:', error);
    throw error; // 抛出错误
  }
}

// 使用封装的异步 fetch 函数
async function getData() {
  try {
    const url = 'https://api.example.com/data'; // 请求的 URL
    const data = await fetchData(url); // 发起异步请求并等待数据返回
    console.log('Data:', data); // 处理返回的数据
  } catch (error) {
    console.error('Error:', error);
  }
}

// 调用封装的异步函数
getData();
```

在上面的示例中，我们定义了一个名为 `fetchData` 的异步函数，它接收一个 URL 参数，并使用 `fetch` 函数发起异步请求。使用 `await` 关键字可以等待请求的响应返回，并将其赋值给 `response` 变量。然后，我们使用 `await` 关键字再次等待将响应数据解析为 JSON 格式，并将其赋值给 `data` 变量。最后，我们返回解析后的数据。

在 `fetchData` 函数中，我们使用 `try/catch` 块来捕获可能发生的错误。如果发生错误，我们将错误信息打印到控制台，并使用 `throw` 关键字抛出错误。

然后，我们定义了一个名为 `getData` 的异步函数，它调用了封装的异步 `fetch` 函数 `fetchData`。在 `getData` 函数中，我们使用 `try/catch` 块来处理可能发生的错误。在 `try` 块中，我们调用 `fetchData` 函数来获取数据，并使用 `await` 关键字等待数据返回。一旦数据返回，我们可以对其进行处理，例如打印到控制台。

最后，我们调用 `getData` 函数来执行封装的异步操作。

这样，我们就封装了一个使用 `async/await` 的异步 `fetch` 函数，并且使用 `async/await` 的方式来调用它。

<br/>

### 请写一个函数，输出出多级嵌套结构的 Object 的所有 key 值

```js
var obj = {
  a: "12",
  b: "23",
  first: {
    c: "34",
    d: "45",
    second: { 3: "56", f: "67", three: { g: "78", h: "89", i: "90" } },
  },
};
// => [a,b,c,d,e,f,g,h,i]
```

公司：顺丰

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/152)
你可以使用递归来实现遍历多级嵌套结构的对象，并提取所有的 key 值。以下是一个实现的函数：

```javascript
function getAllKeys(obj) {
  const keys = [];
  
  for (const key in obj) {
    keys.push(key);
    if (typeof obj[key] === 'object') {
      const nestedKeys = getAllKeys(obj[key]);
      keys.push(...nestedKeys.map(nestedKey => `${key}.${nestedKey}`));
    }
  }
  
  return keys;
}

const obj = {
  a: "12",
  b: "23",
  first: {
    c: "34",
    d: "45",
    second: { 3: "56", f: "67", three: { g: "78", h: "89", i: "90" } },
  },
};

const keys = getAllKeys(obj);
console.log(keys);
```

在这个函数中，我们首先遍历对象的每个属性，将属性名加入到 `keys` 数组中。如果属性的值是一个对象，我们递归地调用 `getAllKeys` 函数获取嵌套对象的 key，并将当前属性名和嵌套属性名拼接起来，然后加入到 `keys` 数组中。最终，函数返回包含所有 key 值的数组。在你的示例中，`keys` 数组将包含 `[ 'a', 'b', 'first.c', 'first.d', 'first.second.3', 'first.second.f', 'first.second.three.g', 'first.second.three.h', 'first.second.three.i' ]`。

<br/>



### 写出打印结果，并解释为什么

```js
var a = { k1: 1 };
var b = a;
a.k3 = a = { k2: 2 };
console.log(a); // ?
console.log(b); // ?
```

公司：头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/149)
这段代码会输出以下结果：

```javascript
{ k2: 2 }
{ k1: 1, k3: { k2: 2 } }
```

现在来解释为什么会得到这样的结果：

1. 初始时，`a` 是一个对象 `{ k1: 1 }`。
2. 接着，`b` 被赋值为 `a`，即 `b` 和 `a` 指向相同的对象 `{ k1: 1 }`。
3. 在下一行代码中，`a.k3` 被赋值为 `{ k2: 2 }`。但在这之前，`a` 和 `b` 都指向了 `{ k1: 1 }` 对象，所以这行代码实际上在修改 `{ k1: 1 }` 对象的 `k3` 属性。此时对象的状态变为 `{ k1: 1, k3: { k2: 2 } }`。
4. 在这之后，`a` 被重新赋值为 `{ k2: 2 }`。但这并不影响 `b` 的值，它仍然指向修改前的 `{ k1: 1, k3: { k2: 2 } }` 对象。

因此，`console.log(a)` 输出的是 `{ k2: 2 }`，因为此时 `a` 指向了 `{ k2: 2 }` 对象。而 `console.log(b)` 输出的是 `{ k1: 1, k3: { k2: 2 } }`，因为 `b` 仍然指向 `{ k1: 1, k3: { k2: 2 } }` 对象。

<br/>

### 动手实现一个 repeat 方法

```js
function repeat(func, times, wait) {
  // TODO
}
const repeatFunc = repeat(alert, 4, 3000);
// 调用这个 repeatFunc ("hellworld")，会alert4次 helloworld, 每次间隔3秒
```

公司：头条

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/148)
要实现一个 `repeat` 方法，它可以重复调用指定的函数，可以按照指定的次数和时间间隔进行操作。以下是一个可能的实现：

```js
function repeat(func, times, wait) {
  return function (text) {
    const interval = setInterval(function () {
      if (times <= 0) {
        clearInterval(interval);
      } else {
        func(text);
        times--;
      }
    }, wait);
  };
}

// 调用 repeat 方法以创建 repeatFunc
const repeatFunc = repeat(alert, 4, 3000);

// 调用 repeatFunc("helloworld") 会触发 alert 4 次，每次间隔 3 秒
repeatFunc("helloworld");
```

在上面的实现中，`repeat` 函数接受三个参数：

1. `func` 是要重复调用的函数，这里使用 `alert` 作为示例。

2. `times` 是要重复调用函数的次数。

3. `wait` 是每次调用之间的时间间隔（以毫秒为单位）。

`repeat` 函数返回一个新的函数，这个新函数接受一个参数 `text`。这个新函数内部使用 `setInterval` 来定期调用传入的 `func` 函数，直到达到指定的 `times` 次数。在每次调用 `func` 之后，`times` 减少，当 `times` 不再大于 0 时，清除 `setInterval` 定时器。

最后，我们调用 `repeat` 方法以创建 `repeatFunc`，并通过调用 `repeatFunc("helloworld")` 来触发 `alert` 函数的重复调用，实现了在指定次数和时间间隔下重复弹出提示框的功能。

请注意，由于 `alert` 函数是模态对话框，可能会阻塞页面上的其他操作。在实际应用中，你可以替换 `alert` 函数为其他非阻塞的操作，以确保用户体验更好。希望这个示例对你有所帮助！如果你有任何问题，请随时提

<br/>

### setTimeout 有什么缺点，和 requestAnimationFrame 有什么区别

公司：头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/147)
`setTimeout` 和 `requestAnimationFrame` 是两种用于延时执行代码的方式，它们有不同的用途和特性。

#### `setTimeout` 的缺点：

1. **不精确性：** `setTimeout` 的延时时间并不是准确的。尤其是在一些高负荷的页面或者电脑性能不佳的情况下，延时时间可能会超过设定的时间。

2. **不适合动画：** `setTimeout` 不适用于动画的渲染。因为浏览器的渲染帧率通常是 60 FPS（每秒60帧），但 `setTimeout` 的延时时间是毫秒计算，可能无法精确匹配浏览器的刷新频率，导致动画不流畅。

3. **可能导致性能问题：** 如果使用 `setTimeout` 创建一个循环定时器（例如，每隔一段时间执行一次某个函数），如果执行的函数非常耗时，可能会阻塞其他任务，导致页面性能下降。

#### `requestAnimationFrame` 的优势和区别：

1. **精确性：** `requestAnimationFrame` 的回调函数会在浏览器下一次重绘之前执行。因此，它的执行时间会根据浏览器的渲染性能动态调整，确保动画的流畅性。

2. **自动暂停和恢复：** 当页面切换到后台标签页或最小化时，`requestAnimationFrame` 会自动暂停，节省了资源。而 `setTimeout` 在这种情况下不会暂停，可能会浪费 CPU 资源。

3. **适合动画：** 由于 `requestAnimationFrame` 的精确性和流畅性，它非常适合用于实现动画效果，避免了闪烁和撕裂等问题。

4. **帧同步：** 当使用 `requestAnimationFrame` 实现多个动画效果时，浏览器会保证这些动画在同一帧中执行，确保视觉上的一致性。

总之，`requestAnimationFrame` 更适合用于实现动画效果，而 `setTimeout` 则适用于一些不需要高精度时间控制的异步任务。选择使用哪个取决于你的具体需求，但在动画场景下，推荐使用 `requestAnimationFrame`。

<br/>

### versions 是一个项目的版本号列表，因多人维护，不规则，动手实现一个版本号处理函数

```js
var versions = ["1.45.0", "1.5", "6", "3.3.3.3.3.3.3"];
// 要求从小到大排序，注意'1.45'比'1.5'大
function sortVersion(versions) {
  // TODO
}
// => ['1.5','1.45.0','3.3.3.3.3.3','6']
```

公司：头条

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/146)
为了处理版本号列表并按照从小到大的顺序进行排序，你可以编写一个 `sortVersion` 函数。以下是一个可能的实现：

```js
var versions = ["1.45.0", "1.5", "6", "3.3.3.3.3.3.3"];

function sortVersion(versions) {
  return versions.sort((a, b) => {
    const aParts = a.split('.').map(Number);
    const bParts = b.split('.').map(Number);

    const maxLength = Math.max(aParts.length, bParts.length);

    for (let i = 0; i < maxLength; i++) {
      const aVal = aParts[i] || 0;
      const bVal = bParts[i] || 0;

      if (aVal < bVal) return -1;
      if (aVal > bVal) return 1;
    }

    return 0;
  });
}

// 调用 sortVersion 方法
const sortedVersions = sortVersion(versions);

// 打印排序后的版本号数组
console.log(sortedVersions);
// => ['1.5','1.45.0','3.3.3.3.3.3','6']
```

在这个实现中，`sortVersion` 函数使用 `sort` 方法对版本号数组进行排序。在比较两个版本号时，它首先将版本号字符串分割为数字数组（`aParts` 和 `bParts`），然后按照从左到右的顺序逐个比较各个部分。

这样，即使版本号的位数不同，也能正确比较它们。如果某一部分不存在，则默认为 0。最终，返回排序后的版本号数组。

<br/>

### 实现一个多并发的请求

```js
let urls = ['http://dcdapp.com', …];
/*
	*实现一个方法，比如每次并发的执行三个请求，如果超时（timeout）就输入null，直到全部请求完
	*batchGet(urls, batchnum=3, timeout=3000);
	*urls是一个请求的数组，每一项是一个url
	*最后按照输入的顺序返回结果数组[]
*/
```

公司：头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/144)
你可以使用JavaScript的`async/await`和`Promise`来实现一个多并发的请求函数，以满足你的需求。以下是一个可能的实现：

```js
// 模拟一个异步请求函数，你需要替换成实际的请求函数
async function fetchUrl(url) {
  // 这里可以使用fetch或者axios等库来进行实际的HTTP请求
  // 这里简单模拟一个延迟1秒的请求
  return new Promise((resolve, reject) => {
    setTimeout(() => {
      resolve(`Response from ${url}`);
    }, 1000);
  });
}

async function batchGet(urls, batchnum = 3, timeout = 3000) {
  const results = [];
  const promises = [];

  for (let i = 0; i < urls.length; i += batchnum) {
    const batchUrls = urls.slice(i, i + batchnum);

    const batchPromises = batchUrls.map(async (url) => {
      const timeoutPromise = new Promise((resolve) =>
        setTimeout(() => resolve(null), timeout)
      );

      const requestPromise = fetchUrl(url); // 使用fetchUrl替换成实际的请求函数

      const result = await Promise.race([timeoutPromise, requestPromise]);
      results.push(result);
    });

    promises.push(...batchPromises);
  }

  await Promise.all(promises);

  return results;
}

// 调用batchGet方法
const urls = ['http://example.com/1', 'http://example.com/2', 'http://example.com/3', 'http://example.com/4', 'http://example.com/5', 'http://example.com/6'];
batchGet(urls, 3, 3000)
  .then((results) => {
    console.log(results);
  });
```

这个实现中，`batchGet` 函数接受一个URL数组，以及每次并发执行的请求数（`batchnum`）和超时时间（`timeout`）。它会将URL数组分成多个批次，每次并发执行指定数量的请求。

对于每个请求，它使用`Promise.race`来比较实际请求和超时Promise，以确保在超时时返回`null`。最后，使用`Promise.all`来等待所有请求完成，并返回结果数组。

<br/>

### 写出代码执行结果

```js
async function async1() {
  console.log("async1 start");
  await async2();
  console.log("async1 end");
}
async function async2() {
  console.log("async2");
}
console.log("script start");
setTimeout(function () {
  console.log("setTimeout");
}, 0);
async1();
new Promise(function (resolve) {
  console.log("promise1");
  resolve();
}).then(function () {
  console.log("promise2");
});
console.log("scripts end");
// 写出代码执行完成打印的结果
```

公司：头条、网易

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/142)
代码执行结果如下：

```
script start
async1 start
async2
promise1
scripts end
async1 end
promise2
setTimeout
```

解释：

1. `script start` 首先被打印，因为它是同步代码，立即执行。
2. `async1` 函数被调用，打印 `async1 start`。
3. 在 `async1` 函数中，调用 `async2` 函数，打印 `async2`。
4. `async2` 函数执行完毕，控制权返回到 `async1` 函数，打印 `async1 end`。
5. 接着执行 `new Promise` 的构造函数，打印 `promise1`。
6. `.then` 方法注册的回调函数被放入微任务队列，在当前宏任务执行完毕后执行。
7. 打印 `scripts end`。
8. 此时宏任务执行完毕，开始执行微任务。执行 `promise2` 的打印。
9. 最后，由于 `setTimeout` 设置了 0 毫秒，它被放入宏任务队列，等待当前宏任务执行完毕后执行，打印 `setTimeout`。

<br/>

### 按要求实现一个 sum 函数

```js
const a = sum(0); // => a === 0
const b = sum(1)(2); // => b === 3
const c = sum(4)(5); // c === 9
const k = sum(n1)...(nk) // k === n1 + n2 + ... + nk
```

公司：头条

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/141)
你可以实现一个`sum`函数，使其能够根据不同的调用方式返回不同的结果。这需要使用JavaScript的闭包和柯里化（currying）技巧。下面是一个可能的实现：

```js
function sum(value) {
  // 定义一个内部函数，用于实际计算和返回结果
  function add(nextValue) {
    // 如果没有传入下一个值，或者下一个值不是数字，直接返回当前的累积值
    if (typeof nextValue !== 'number') {
      return value;
    }

    // 将下一个值累积到当前值上
    value += nextValue;
    // 返回一个新的函数，以便进行下一次调用
    return add;
  }

  // 返回内部函数，从而支持链式调用
  return add;
}

// 使用示例
const a = sum(0); // => a === 0
const b = sum(1)(2); // => b === 3
const c = sum(4)(5); // c === 9
const k = sum(2)(3)(4)(5); // k === 14

console.log(a);
console.log(b);
console.log(c);
console.log(k);
```

这个实现中，`sum`函数接受一个初始值`value`，并返回一个内部函数`add`。`add`函数用于接收下一个值，将其累积到`value`上，并返回自身以支持链式调用。当不再传入数字时，它会返回当前累积的值。

这允许你按照你的需求进行链式调用，最终返回累积的结果。

<br/>

### 说一下 base64 的编码方式

公司：完美世界

分类：JavaScirpt

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/359)
Base64 是一种用于表示二进制数据的编码方式，它将二进制数据转换成一种文本形式，以便于在文本协议中传输，比如在URL、JSON等文本协议中传输二进制数据。

Base64 编码方式的特点如下：

1. **字符集：** Base64 编码使用 64 个字符（A-Z，a-z，0-9，+，/），再加上一个用于填充的字符（通常是=），一共65个字符。
   
2. **编码规则：** 将输入数据按照每 3 个字节（24 位）一组进行分组，每组按照 8 位一组划分为 4 个小组。然后，将每个小组的数值转换为相应的字符，从而得到 Base64 编码。

3. **填充字符：** 如果输入数据的长度不是 3 的倍数，就需要用填充字符“=”来补齐。一般来说，Base64 编码后的文本长度是输入数据长度的 4/3。

Base64 编码的用途包括但不限于：

- **在URL中传递二进制数据：** Base64 编码后的数据可以放在URL中，因为它只包含URL安全字符，不会破坏URL的结构。
  
- **在数据URI中嵌入图片：** 将图片转换为Base64编码后的字符串，可以直接嵌入HTML文档中，而不需要额外的图片文件。
  
- **在XML、JSON等文本协议中传递二进制数据：** Base64编码后的数据可以直接嵌入到XML或JSON文档中。

Base64 编码并不是一种加密算法，因为它是可逆的。任何人只需要知道编码规则，就可以将Base64编码的文本解码还原成原始的二进制数据。但它对于简单地将二进制数据以文本形式传输或存储在文本文件中是非常有用的。

<br/>

### 改变 this 指向的方式都有哪些？

公司：网易

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/354)
在JavaScript中，有几种方式可以改变函数中`this`的指向。下面是一些常见的方式：

1. 使用`call()`方法：`call()`方法允许你显式地指定函数执行时的`this`值，并传递参数列表。例如：
   ```js
   function greet() {
     console.log(`Hello, ${this.name}`);
   }

   const person = { name: 'Alice' };
   greet.call(person); // 输出：Hello, Alice
   ```

2. 使用`apply()`方法：`apply()`方法与`call()`方法类似，但是参数需要以数组的形式传递。例如：
   ```js
   function greet(greeting) {
     console.log(`${greeting}, ${this.name}`);
   }

   const person = { name: 'Bob' };
   greet.apply(person, ['Hi']); // 输出：Hi, Bob
   ```

3. 使用`bind()`方法：`bind()`方法创建一个新的函数，将指定的`this`值绑定到函数中，并返回这个新函数。这样，无论在何时调用这个新函数，它的`this`值都会保持不变。例如：
   ```js
   function greet() {
     console.log(`Hello, ${this.name}`);
   }

   const person = { name: 'Charlie' };
   const greetPerson = greet.bind(person);
   greetPerson(); // 输出：Hello, Charlie
   ```

4. 使用箭头函数：箭头函数不会绑定自己的`this`值，而是继承外部作用域的`this`值。因此，箭头函数的`this`指向在定义时就确定了。例如：
   ```js
   const person = {
     name: 'David',
     greet: function() {
       const innerFunc = () => {
         console.log(`Hello, ${this.name}`);
       };
       innerFunc();
     }
   };

   person.greet(); // 输出：Hello, David
   ```

<br/>

### 说一下`module.exports`和`exports`的区别，`export`和`export default`的区别

公司：网易

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/350)
在Node.js中，`module.exports` 和 `exports` 是导出模块成员的两种不同方式，它们之间的关系可以理解为：

1. **`exports` 是 `module.exports` 的引用：** 在模块文件的开头，Node.js 实际上有这样一行隐式代码：`var exports = module.exports = {}`。也就是说，`exports` 和 `module.exports` 最初指向同一个空对象。

2. **直接赋值情况下`exports`的引用关系会被断开：** 如果你直接将 `exports` 指向其他对象，例如 `exports = {}`，那么这个时候 `exports` 不再指向 `module.exports`，而只是一个普通的对象，`module.exports` 依然指向原来的对象。这样，`exports` 的引用关系就被断开了，不再影响 `module.exports`。

举个例子：

```javascript
// 导出模块成员的两种方式
// 1. 使用 `exports`
exports.sayHello = function() {
  console.log("Hello!");
};

// 2. 直接赋值给 `module.exports`
module.exports = {
  greet: function() {
    console.log("Greetings!");
  }
};
```

在 ES6 模块系统中，使用了 `export` 和 `export default` 语法来导出模块成员：

- **`export` 用于导出具体的变量、函数、类等。** 可以导出多个变量或函数，并使用解构赋值导入。
  
  ```javascript
  // math.js
  export const PI = 3.1415926;
  export function square(x) {
    return x * x;
  }
  ```

  ```javascript
  // 在其他文件中导入
  import { PI, square } from './math';
  ```

- **`export default` 用于导出默认的变量、函数或类。** 一个模块只能有一个默认导出。导入时可以使用任意名称。

  ```javascript
  // math.js
  const PI = 3.1415926;
  function square(x) {
    return x * x;
  }
  export default {
    PI,
    square
  };
  ```

  ```javascript
  // 在其他文件中导入
  import mathFunctions from './math';
  ```

总结：

- `module.exports` 和 `exports` 是 Node.js 中用于导出模块成员的方式，它们最初是相同的对象，但在赋值情况下它们的引用关系会被断开。
- `export` 和 `export default` 是 ES6 模块系统中用于导出模块成员的语法，它们支持导出具体的变量、函数、类等，并提供了更灵活的导入和导出方式。

<br/>

### number 为什么会出现精度损失，怎样避免

公司：网易

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/348)
JavaScript中的精度损失通常出现在使用浮点数（`number`类型）进行数学计算时，这是因为浮点数的内部表示方式导致了有限的精度。JavaScript使用的浮点数遵循IEEE 754标准，它使用二进制来表示小数，而不是十进制。这导致一些十进制小数无法准确表示为二进制分数，从而引起精度损失。

精度损失的示例：

```js
0.1 + 0.2 // 返回 0.30000000000000004，而不是 0.3
```

这是由于0.1和0.2在二进制中的表示不是精确的十进制分数，因此在计算时会产生微小的误差。

要避免精度损失，可以考虑以下方法：

1. **使用整数进行计算**：如果可能的话，将数值转换为整数，进行整数运算，最后再将结果转换为浮点数或需要的格式。这可以减少精度损失。

2. **使用小数库**：JavaScript中有一些库，如`big.js`或`decimal.js`，它们提供了更高精度的十进制数学运算，可以用来解决精度问题。

3. **四舍五入**：在需要进行精确计算的情况下，使用`toFixed()`方法将结果四舍五入到指定的小数位数。

```js
const result = (0.1 + 0.2).toFixed(1); // 返回 "0.3"
```

4. **避免直接比较浮点数**：由于精度问题，直接比较浮点数是否相等可能会导致问题。应该使用范围或误差值来比较浮点数。

```js
const epsilon = 0.00001;
if (Math.abs(result - expected) < epsilon) {
  // 在误差范围内认为它们相等
}
```

5. **了解浮点数的限制**：理解浮点数的内部表示和限制，有助于避免潜在的精度损失问题。

<br/>

### 实现一个函数将中文数字转成数字

公司：微软

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/343)
可以使用一个对象字典来映射中文数字和阿拉伯数字，然后遍历输入字符串，将每个中文数字转换为对应的阿拉伯数字。以下是一个示例实现：

```javascript
function chineseToNumber(chineseNumber) {
    const chineseNumberDict = {
        一: 1,
        二: 2,
        三: 3,
        四: 4,
        五: 5,
        六: 6,
        七: 7,
        八: 8,
        九: 9,
        零: 0,
    };

    let number = 0;
    let tempNumber = 0;

    for (let i = 0; i < chineseNumber.length; i++) {
        const char = chineseNumber[i];
        const charNumber = chineseNumberDict[char];

        if (charNumber !== undefined) {
            if (charNumber < 10) {
                tempNumber = charNumber;
            } else {
                number += tempNumber * charNumber;
                tempNumber = 0;
            }
        } else {
            // 非中文数字字符，直接累加
            number += tempNumber;
            tempNumber = 0;
        }
    }

    // 处理最后一个数字
    number += tempNumber;

    return number;
}

// 示例用法
const chineseNumber = "一百二十三"; // 输入中文数字字符串
const arabicNumber = chineseToNumber(chineseNumber); // 输出阿拉伯数字
console.log(arabicNumber); // 输出 123
```

请注意，这个函数只支持处理基本的中文数字（一至九，十，百，千）。如果需要支持更多的中文数字，需要扩展 `chineseNumberDict` 对象。这个函数假定输入的中文数字字符串是符合语法的，不包含错别字或非法字符。

<br/>

### 节流

公司：微软

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/342)
节流（Throttling）是一种用于限制函数执行频率的技术，通常用于处理事件处理、网络请求等情况。它确保在一定时间内函数不会被连续调用，从而减轻服务器或客户端的负担，提高性能，减少不必要的资源浪费。

节流的基本思想是设置一个时间间隔，如果在该时间间隔内触发了多次函数调用，只有第一次调用会立即执行，之后的调用将被忽略，直到时间间隔过去后才能再次触发。

以下是一个常见的实现节流的JavaScript函数：

```js
function throttle(func, delay) {
  let lastTime = 0;
  return function () {
    const now = Date.now();
    if (now - lastTime >= delay) {
      func.apply(this, arguments);
      lastTime = now;
    }
  };
}
```

这个`throttle`函数接受两个参数：

1. `func`：要节流的函数。
2. `delay`：时间间隔，表示两次函数调用之间需要等待的时间。

使用节流函数的示例：

```js
function doSomething() {
  console.log('Doing something');
}

const throttledFunc = throttle(doSomething, 1000);

// 在1000毫秒内多次调用
throttledFunc(); // 执行
throttledFunc(); // 忽略
throttledFunc(); // 忽略

// 1000毫秒后再次调用
setTimeout(() => {
  throttledFunc(); // 执行
}, 1000);
```

在这个示例中，`doSomething`函数在1000毫秒内只会被执行一次。如果在短时间内多次调用`throttledFunc`，其中大部分调用都会被忽略。

<br/>

### 如何实现 5 秒自动刷新一次页面(具体都有什么方法 reload 之类的)

公司：易车

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/338)
在前端，你可以使用 `setTimeout` 函数或者 `setInterval` 函数来实现定时刷新页面的效果。另外，在 `window.location` 对象上的 `reload` 方法也可以用于刷新页面。以下是具体的方法：

#### 使用 `setTimeout` 函数：

```javascript
setTimeout(function() {
    window.location.reload();
}, 5000); // 5000毫秒，即5秒钟后刷新页面
```

这个代码会在页面加载后等待5秒钟，然后刷新页面。

#### 使用 `setInterval` 函数：

```javascript
setInterval(function() {
    window.location.reload();
}, 5000); // 每隔5000毫秒（5秒）刷新页面一次
```

这个代码会在页面加载后，每隔5秒钟刷新一次页面。

#### 使用 `window.location.reload()` 方法：

```javascript
setTimeout(function() {
    window.location.reload();
}, 5000);
```

这个代码也是在页面加载后等待5秒钟，然后刷新页面。

请注意，在实际项目中，自动刷新页面可能会影响用户体验，因此需要谨慎使用。用户在阅读页面内容时，如果页面频繁刷新可能会导致用户的操作被中断。通常情况下，最好的做法是在用户需要时提供手动刷新的选项，而不是自动刷新整个页面。

<br/>

### 都了解哪些 ES6、ES7 的新特性，箭头函数可以被 new 吗

公司：易车、脉脉、虎扑、喜马拉雅、百分点、海风教育、58

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/337)
ES6（ECMAScript 2015）和之后的版本引入了许多新特性，其中包括ES7（ECMAScript 2016）和ES8（ECMAScript 2017）等。以下是一些ES6、ES7以及之后版本中引入的一些新特性：

#### ES6 新特性：

1. **let 和 const 声明**：引入了块级作用域的变量声明方式，`let`用于声明变量，`const`用于声明常量。

2. **箭头函数**：提供了一种更简洁的函数声明方式。

    ```js
    const sum = (a, b) => a + b;
    ```

3. **模板字符串**：允许使用`${}`语法嵌入变量和表达式到字符串中。

    ```js
    const name = 'World';
    console.log(`Hello, ${name}!`);
    ```

4. **解构赋值**：允许从数组或对象中提取值并赋给变量。

    ```js
    const person = { name: 'Alice', age: 30 };
    const { name, age } = person;
    ```

5. **默认参数**：函数参数可以有默认值。

    ```js
    function greet(name = 'World') {
      console.log(`Hello, ${name}!`);
    }
    ```

6. **类和继承**：引入了类和基于类的面向对象编程。

    ```js
    class Animal {
      constructor(name) {
        this.name = name;
      }
      speak() {
        console.log(`${this.name} makes a sound.`);
      }
    }
    ```

#### ES7 新特性：

1. **包含**：Array.prototype.includes方法用于检测数组中是否包含特定元素。

    ```js
    const array = [1, 2, 3];
    console.log(array.includes(2)); // true
    ```

2. **指数操作符**：引入了指数运算符（`**`）。

    ```js
    console.log(2 ** 3); // 8
    ```

#### 关于箭头函数和new的问题：

箭头函数不能被用作构造函数，因此不能使用`new`关键字调用箭头函数。箭头函数没有自己的`this`绑定，它的`this`值由包含它的非箭头函数确定。

由于箭头函数没有`prototype`属性，因此不能被用作构造函数。尝试使用`new`关键字调用箭头函数会导致运行时错误。例如：

```js
const MyConstructor = () => {
  this.value = 42;
};

const obj = new MyConstructor(); // TypeError: MyConstructor is not a constructor
```

因此，箭头函数通常用于非常简单的函数表达式，而不是用于需要作为构造函数使用的场景。对于构造函数，应该使用传统的函数声明或函数表达式。

<br/>

### 说一下 JavaScript 继承都有哪些方法

公司：易车、脉脉、微医、海康威视

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/336)
在JavaScript中，实现继承的方式有多种。以下是常见的JavaScript继承方法：

#### 1. 原型链继承：

```javascript
function Parent() {
  this.property = 'value';
}

Parent.prototype.method = function() {
  // 方法定义
};

function Child() {
  // 子类构造函数
}

Child.prototype = new Parent();
Child.prototype.constructor = Child;
```

原型链继承是通过将子类的原型对象指向父类的实例来实现的。但是这种方法有个缺点，即子类实例共享了父类实例的属性，可能导致意外的属性修改。

#### 2. 构造函数继承（借用构造函数）：

```javascript
function Parent() {
  this.property = 'value';
}

function Child() {
  Parent.call(this);
  // 子类构造函数
}
```

构造函数继承通过在子类构造函数中调用父类构造函数来实现继承。这种方式可以避免共享属性的问题，但是无法继承父类原型链上的方法。

#### 3. 组合继承：

```javascript
function Parent() {
  this.property = 'value';
}

Parent.prototype.method = function() {
  // 方法定义
};

function Child() {
  Parent.call(this);
  // 子类构造函数
}

Child.prototype = new Parent();
Child.prototype.constructor = Child;
```

组合继承结合了原型链继承和构造函数继承，既继承了父类构造函数的属性，又继承了父类原型链上的方法。但是它调用了两次父类构造函数，可能会造成一些性能上的浪费。

#### 4. 原型式继承：

```javascript
function createObject(o) {
  function F() {}
  F.prototype = o;
  return new F();
}

var obj = {
  property: 'value'
};

var child = createObject(obj);
```

原型式继承是通过创建一个临时的构造函数，将传入的对象作为这个构造函数的原型，然后返回一个新的实例对象。这种方式可以简单地实现对象间的继承。

#### 5. 寄生式继承：

```javascript
function createObject(o) {
  var clone = Object.create(o);
  clone.method = function() {
    // 自定义方法
  };
  return clone;
}

var obj = {
  property: 'value'
};

var child = createObject(obj);
```

寄生式继承是在原型式继承的基础上，为新对象添加额外的方法或属性。这种方式常常用于为对象创建一个封装的工厂函数。

#### 6. 寄生组合式继承（推荐方式）：

```javascript
function Parent() {
  this.property = 'value';
}

Parent.prototype.method = function() {
  // 方法定义
};

function Child() {
  Parent.call(this);
  // 子类构造函数
}

Child.prototype = Object.create(Parent.prototype);
Child.prototype.constructor = Child;
```

寄生组合式继承是组合继承的一种改进版。它通过使用 `Object.create()` 方法创建了一个临时的构造函数，该构造函数的原型链指向了父类的原型，然后再将这个临时的构造函数赋值给子类的原型。这种方式继承了父类构造函数的属性，也继承了父类原型链上的方法，同时避免了调用两次父类构造函数。这是一种推荐的继承方式。

<br/>

### 已知函数 A，要求构造⼀个函数 B 继承 A

```js
function A(name) {
  this.name = name;
}
A.prototype.getName = function () {
  console.log(this.name);
};
```

公司：新东方

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/333)
要构造一个函数B继承函数A，可以使用原型链继承的方式。以下是一种实现方式：

```js
function B(name, age) {
  // 调用父类构造函数A，并传入name参数
  A.call(this, name);
  this.age = age;
}

// 创建一个新的对象，将A的原型赋值给B的原型
B.prototype = Object.create(A.prototype);

// 修复B的构造函数指向
B.prototype.constructor = B;

// 添加B自己的方法
B.prototype.getAge = function () {
  console.log(this.age);
};

// 示例用法
const b = new B('John', 25);
b.getName(); // 输出：John
b.getAge(); // 输出：25
```

在上述代码中，我们定义了一个函数B，它接受name和age作为参数。在B的构造函数中，我们使用`A.call(this, name)`调用了A的构造函数，以便在B的实例中设置name属性。

然后，我们使用`Object.create(A.prototype)`创建了一个新的对象，并将A的原型赋值给B的原型。这样，B的实例就可以继承A的原型上的方法，比如`getName`。

最后，我们修复了B的构造函数指向，将其指向B本身。这是因为在之前的操作中，B的原型对象被替换为了A的原型对象，导致构造函数指向错误。

现在，我们可以创建B的实例，并调用继承自A的方法`getName`，以及B自己的方法`getAge`。

这样，函数B就成功继承了函数A。

<br/>

### 数组和对象转换为字符串结果

```js
var arry = [];
var obj = {};
// arry,obj 转成字符串的结果是什么？
```

公司：新东方

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/332)
在JavaScript中，可以使用`JSON.stringify()`方法将数组和对象转换为字符串。让我们看看数组和对象分别转换为字符串的结果：

#### 数组转换为字符串：

```javascript
var arry = [1, 2, 3];
var arryString = JSON.stringify(arry);
console.log(arryString); // 输出: "[1,2,3]"
```

当你将一个数组转换为字符串时，`JSON.stringify()`方法会将数组的元素转换为字符串，并且数组的字符串表示形式会被包裹在方括号中。

#### 对象转换为字符串：

```javascript
var obj = { key: 'value', num: 42 };
var objString = JSON.stringify(obj);
console.log(objString); // 输出: "{"key":"value","num":42}"
```

当你将一个对象转换为字符串时，`JSON.stringify()`方法会将对象的键值对转换为字符串，并且对象的字符串表示形式会被包裹在花括号中。

需要注意的是，`JSON.stringify()`方法只能转换包含有效 JSON 数据的对象或数组。如果对象中包含函数、循环引用等特殊情况，`JSON.stringify()`方法可能无法正确处理。

<br/>

### 请写出以下代码的打印结果

```js
var a = {
  name: "A",
  fn() {
    console.log(this.name);
  },
};
a.fn();
a.fn.call({ name: "B" });
var fn1 = a.fn;
fn1();
// 写出打印结果
```

公司：新东方

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/331)
好的，让我们逐行来分析这段代码，并写出每一行的打印结果：

```js
var a = {
  name: "A",
  fn() {
    console.log(this.name);
  },
};
```

这段代码定义了一个对象`a`，其中包含一个名为`fn`的方法，这个方法会打印对象`a`的`name`属性。`a`的`name`属性被设置为字符串"A"。

```js
a.fn();
```

这一行调用了`a`的`fn`方法，由于是通过`a`来调用的，`this`指向的是`a`，因此会打印出`"A"`。

```js
a.fn.call({ name: "B" });
```

这一行通过`call`方法改变了`fn`函数内部的`this`指向，将其指向了一个新的对象`{ name: "B" }`。所以会打印出`"B"`。

```js
var fn1 = a.fn;
```

这一行将`a`的`fn`方法赋值给了变量`fn1`。

```js
fn1();
```

这里调用了`fn1`，由于它是作为一个独立的函数来调用的，而不是作为对象的方法，所以`this`指向全局对象（在浏览器环境下通常是`window`对象）。如果在浏览器中执行，且没有其他对`name`的定义，会导致一个`ReferenceError`，因为全局对象并没有`name`属性。

综上所述，整段代码的打印结果是：

```
A
B
TypeError: Cannot read property 'name' of undefined
```

第三行会产生一个错误，因为全局对象并没有`name`属性。

<br/>

### 请写出以下代码的打印结果

```js
let int = 1;
setTimeout(function () {
  console.log(int);
  int = 2;
  new Promise((resolve, reject) => {
    resolve();
  }).then(function () {
    console.log(int);
    int = 7;
  });
  console.log(int);
});
int = 3;
console.log(int);
new Promise((resolve, reject) => {
  console.log(int);
  return resolve((int = 4));
}).then(function (res) {
  console.log(int);
  int = 5;
  setTimeout(function () {
    console.log(int);
    int = 8;
  }); 
  return false;
});
console.log(int);
// 写出打印结果
```

公司：新东方

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/330)

1. `let int = 1;` 定义了一个变量 `int` 并赋值为 1。
2. `int = 3;` 修改了变量 `int` 的值为 3。
3. 执行第一个 `setTimeout`，它是异步的，所以它的回调函数会在主线程执行完后执行。这个回调函数中包含了一些异步操作。
4. 执行第二个 `new Promise`，它是同步的，所以其中的回调函数会立即执行。
5. `setTimeout` 的回调函数中有一个内部的 `Promise`，它也是异步的，所以它的 `then` 方法中的回调函数也会在主线程执行完后执行。

根据以上分析，这段代码的打印结果是：

```
3
1
4
3
2
7
5
8
```

解释：

1. `console.log(int);` 打印 3，因为此时 `int` 的值为 3。
2. `console.log(int);` 打印 1，因为在第一个 `setTimeout` 中，`int` 的值为 1。
3. `console.log(int);` 打印 4，因为在第二个 `Promise` 的回调函数中，`int` 的值被修改为 4。
4. `console.log(int);` 打印 3，因为在第二个 `Promise` 的回调函数中，并没有修改 `int` 的值，所以仍然是 3。
5. `console.log(int);` 打印 2，因为在第一个 `setTimeout` 的回调函数中，`int` 的值被修改为 2。
6. `console.log(int);` 打印 7，因为在第一个 `setTimeout` 的回调函数中，`int` 的值被修改为 7。
7. `console.log(int);` 打印 5，因为在第二个 `Promise` 的 `then` 方法的回调函数中，`int` 的值被修改为 5。
8. `console.log(int);` 打印 8，因为在第二个 `setTimeout` 的回调函数中，`int` 的值被修改为 8。

<br/>

### 要求⽤不同⽅式对 A 进⾏改造实现 A.name 发⽣变化时⽴即执⾏ A.getName

```js
/*
	已知对象A = {name: 'sfd', getName: function(){console.log(this.name)}},
	现要求⽤不同⽅式对A进⾏改造实现A.name发⽣变化时⽴即执⾏A.getName
*/
```

公司：新东方

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/329)
要实现当`A.name`发生变化时立即执行`A.getName`，你可以使用属性的`setter`方法来监听`name`属性的变化。这可以通过`Object.defineProperty`方法来实现。下面是一个示例：

```js
var A = {
  _name: 'sfd', // 使用下划线前缀约定为私有属性
  get name() {
    return this._name;
  },
  set name(newName) {
    this._name = newName;
    this.getName();
  },
  getName: function() {
    console.log(this.name);
  },
};

A.name = 'New Name'; // 这会触发 getName 方法并打印 "New Name"
```

在上面的代码中，我们使用了`_name`作为`name`属性的内部存储。`name`属性被定义为一个拥有`getter`和`setter`的属性，当`name`属性被设置时，`setter`方法会被触发，它首先更新内部的`_name`属性，然后调用`this.getName()`来执行`getName`方法，从而实现了在`name`属性发生变化时立即执行`A.getName`的要求。

你可以通过将`A.name`设置为新的值来测试这段代码，它会立即执行`A.getName`方法并打印新的`name

<br/>

### 修改以下代码，使得最后⼀⾏代码能够输出数字 0-9（最好能给多种答案）

```js
var arrys = [];
for (var i = 0; i < 10; i++) {
  arrys.push(function () {
    return i;
  });
}
arrys.forEach(function (fn) {
  console.log(fn());
}); //本⾏不能修改
```

公司：新东方

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/328)
在原始代码中，使用 `var` 声明的变量 `i` 具有函数作用域，在循环结束后，`i` 的值变为 10。所以，每个函数都返回 10。为了得到期望的结果（返回0到9），可以使用闭包来解决。以下是几种修改方案：

#### 1. 使用 IIFE（立即调用的函数表达式）：

```javascript
var arrys = [];
for (var i = 0; i < 10; i++) {
  (function (i) {
    arrys.push(function () {
      return i;
    });
  })(i);
}
arrys.forEach(function (fn) {
  console.log(fn());
});
```

在每次循环迭代时，通过传入 `i` 的副本到 IIFE 中，确保了每个函数捕获到了正确的值。

#### 2. 使用 `let` 关键字：

```javascript
var arrys = [];
for (let i = 0; i < 10; i++) {
  arrys.push(function () {
    return i;
  });
}
arrys.forEach(function (fn) {
  console.log(fn());
});
```

使用 `let` 关键字声明的变量具有块级作用域，每次循环迭代都会创建一个新的 `i`。

#### 3. 使用 `Array.from()`：

```javascript
var arrys = Array.from({ length: 10 }, (_, i) => () => i);
arrys.forEach(function (fn) {
  console.log(fn());
});
```

使用 `Array.from()` 创建一个包含 10 个 `undefined` 元素的数组，然后使用箭头函数和闭包，确保每个函数都返回正确的值。

以上这些方法都能够在不修改最后一行代码的情况下输出数字 0 到 9。

<br/>

### 请给出识别 Email 的正则表达式

公司：头条

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/325)
当涉及到识别电子邮件地址时，可以使用以下正则表达式：

```regex
/^[\w.-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/ 
```

让我们逐步解释这个正则表达式的各个部分：

- `^`：表示匹配字符串的开头。
- `[\w.-]+`：匹配一个或多个字母、数字、下划线、点号或破折号。这部分匹配了电子邮件地址中的用户名部分。
- `@`：匹配电子邮件地址中的@符号。
- `[a-zA-Z0-9.-]+`：匹配一个或多个字母、数字、点号或破折号。这部分匹配了电子邮件地址中的域名部分的名称。
- `\.`：匹配一个点号。这是为了匹配电子邮件地址中域名部分的点号。
- `[a-zA-Z]{2,}`：匹配两个或更多字母。这部分匹配了电子邮件地址中域名部分的顶级域名，如com、net等。
- `$`：表示匹配字符串的结尾。

综合起来，这个正则表达式可以用来识别符合一般电子邮件地址格式的字符串。但请注意，这只是一个简单的正则表达式，无法涵盖所有可能的电子邮件地址格式。实际上，电子邮件地址的规范非常复杂，因此在实际应用中，可能需要更复杂的正则表达式或其他验证方法来确保准确性。

<br/>

### 设计 AutoComplete 组件(又叫搜索组件、自动补全组件等)时，需要考虑什么问题？

公司：头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/324)
设计一个AutoComplete（自动补全）组件时，需要考虑以下问题，以确保组件的性能、用户体验和功能的完整性：

1. **数据源：** 考虑从何处获取数据，可以是本地数据、远程API或者是用户输入。需要确保数据源的稳定性和及时性。

2. **性能：** 自动补全组件需要在用户输入时快速响应并显示匹配项。需要考虑大数据集的情况下，如何高效地进行搜索和匹配。

3. **匹配算法：** 要选择适当的匹配算法，例如前缀匹配、模糊匹配等，以确保用户输入的准确性和匹配的准确性。

4. **UI/UX设计：** 用户界面应该友好、直观，提供清晰的反馈和指导，例如下拉列表、高亮匹配项、键盘导航等，以增强用户体验。

5. **键盘交互：** 要确保组件可以通过键盘进行导航和选择，例如上下箭头选择、回车确认等，以提供良好的键盘支持。

6. **输入延迟：** 可以考虑在用户输入停顿一段时间后再触发搜索，以减轻服务器负担和提供更好的用户体验。

7. **样式定制：** 要提供足够的样式定制选项，以便开发者根据自身项目的需求进行外观定制。

8. **无障碍性（Accessibility）：** 确保组件对屏幕阅读器等辅助技术友好，提供适当的ARIA属性，以确保残障用户也能方便地使用。

9. **国际化：** 如果应用面向全球用户，需要考虑多语言支持，确保用户可以输入和搜索各种语言的文本。

10. **缓存和优化：** 对于远程数据源，可以考虑实现缓存机制，减少重复请求。另外，可以进行性能优化，例如懒加载等。

11. **事件处理：** 要提供丰富的事件处理机制，例如输入变化事件、选择事件等，以便开发者可以在各种场景下做出相应的响应。

12. **安全性：** 对于从远程数据源获取数据，需要考虑安全性问题，防止XSS攻击等。

13. **测试：** 需要进行各种单元测试、集成测试、用户体验测试等，确保组件的稳定性和性能。

14. **文档和示例：** 需要提供清晰、详细的文档和示例，以便开发者能够快速上手和解决问题。

考虑到以上问题，可以设计一个功能完备、性能高效、易用可靠的AutoComplete组件。

<br/>

### 实现函数接受任意二叉树，求二叉树所有根到叶子路径组成的数字之和

```js
class TreeNode{
  value:number
  left?:TreeNode
  right?:TreeNode
}
function getPathSum(root){
  // your code
}
// 例子，一层二叉树如下定义，路径包括1 —> 2 ,1 -> 3
const node = new TreeNode();
node.value = 1;
node.left = new TreeNode();
node.left.value = 2;
node.right = new TreeNode();
node.right.value = 3;
getPathSum(node); // return 7 = (1+2) + (1+3)
```

公司：头条

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/323)
要实现函数`getPathSum`，计算二叉树所有根到叶子节点路径组成的数字之和，可以使用深度优先搜索（DFS）的方法来遍历二叉树的所有路径，并计算路径上的数字之和。

下面是一个实现示例：

```js
class TreeNode {
  value: number;
  left?: TreeNode;
  right?: TreeNode;
}

function getPathSum(root: TreeNode): number {
  if (!root) {
    return 0;
  }

  let sum = 0;

  function dfs(node: TreeNode, currentSum: number) {
    if (!node.left && !node.right) {
      // 当前节点为叶子节点，将当前路径的数字之和加到总和中
      sum += currentSum * 10 + node.value;
      return;
    }

    if (node.left) {
      dfs(node.left, currentSum * 10 + node.value);
    }

    if (node.right) {
      dfs(node.right, currentSum * 10 + node.value);
    }
  }

  dfs(root, 0);

  return sum;
}

// 例子，一层二叉树如下定义，路径包括1 —> 2 ,1 -> 3
const node = new TreeNode();
node.value = 1;
node.left = new TreeNode();
node.left.value = 2;
node.right = new TreeNode();
node.right.value = 3;

console.log(getPathSum(node)); // 输出 7 = (1+2) + (1+3)
```

在上面的代码中，我们定义了一个内部的深度优先搜索函数`dfs`，它接受当前节点和当前路径的数字之和作为参数。在每次递归调用中，我们将当前节点的值加到当前路径的数字之和中，并检查当前节点是否为叶子节点。如果是叶子节点，则将当前路径的数字之和加到总和中。如果不是叶子节点，则继续递归地遍历左子树和右子树。

最后，我们调用`getPathSum`函数，并传入根节点，它将返回二叉树所有根到叶子节点路径组成的数字之和。在上面的例子中，输出结果为7，表示路径和为(1+2) + (1+3)。

<br/>

### 请写出一下代码的打印结果

```js
function a(obj) {
  obj.a = 2;
  obj = { a: 3 };
  return obj;
}
const obj = { a: 1 };
a(obj);
console.log(obj);
```

公司：滴滴

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/324)
这段代码的执行结果会打印 `{ a: 2 }`。

让我解释一下为什么：

1. `obj` 是一个对象，当它传递给函数 `a` 时，`a` 函数内部的 `obj` 和外部的 `obj` 引用的是同一个对象。所以，在函数内部，`obj.a = 2` 修改了传入对象的属性，使得外部的 `obj` 对象变为 `{ a: 2 }`。

2. 然后，函数内部又创建了一个新的对象 `{ a: 3 }` 并将 `obj` 指向这个新对象。但是这个改变只在函数内部生效，不会影响外部的 `obj`。

3. 所以，当 `console.log(obj)` 执行时，它打印的是外部的 `obj`，即 `{ a: 2 }`。因为在函数内部创建的新对象只在函数内部作用域内有效，对外部没有影响。

<br/>

### Promise 链式调用如何实现

公司：滴滴

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/319)
在 JavaScript 中，Promise 链式调用是一种处理异步操作的方式，它允许你按顺序执行一系列异步操作，并在每个操作完成后继续执行下一个操作。这提供了一种更清晰和可维护的方式来处理异步任务。Promise 链式调用可以通过返回新的 Promise 对象来实现。

下面是如何实现 Promise 链式调用的步骤：

1. 创建一个初始的 Promise 对象，通常称为根 Promise，用于启动链式调用。

2. 在根 Promise 上使用 `.then()` 方法附加一个处理成功情况的回调函数。这个回调函数将在根 Promise 成功时执行，并接收根 Promise 的解决值作为参数。

3. 在这个回调函数内部，执行异步操作，然后返回一个新的 Promise 对象，通常是通过 `return` 语句返回。

4. 在新的 Promise 对象上可以继续使用 `.then()` 方法附加下一个处理成功情况的回调函数，这样可以形成链式调用。

5. 如果需要处理错误情况，可以使用 `.catch()` 方法附加一个处理错误的回调函数。

下面是一个示例，演示如何实现一个简单的 Promise 链式调用：

```js
function asyncOperation1() {
  return new Promise((resolve, reject) => {
    setTimeout(() => {
      resolve("Operation 1 done");
    }, 1000);
  });
}

function asyncOperation2() {
  return new Promise((resolve, reject) => {
    setTimeout(() => {
      resolve("Operation 2 done");
    }, 1000);
  });
}

asyncOperation1()
  .then((result) => {
    console.log(result);
    return asyncOperation2();
  })
  .then((result) => {
    console.log(result);
  })
  .catch((error) => {
    console.error(error);
  });
```

在上面的示例中，我们首先调用 `asyncOperation1()`，它返回一个 Promise 对象，然后使用 `.then()` 方法附加处理成功情况的回调函数。在这个回调函数中，我们打印操作1的结果，并返回 `asyncOperation2()` 的调用结果，这会启动第二个异步操作。接着，我们使用 `.then()` 方法附加另一个处理成功情况的回调函数，打印操作2的结果。如果发生错误，我们可以使用 `.catch()` 方法附加一个错误处理函数。

<br/>

### 说一下对`BigInt`的理解，在什么场景下会使用

公司：滴滴、高德

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/318)
`BigInt` 是 JavaScript 中的一个新数据类型，它用来表示任意精度的整数。在 JavaScript 中，普通的数字（Number）有一个上限，即 `Number.MAX_SAFE_INTEGER`，当超出这个范围时，数字就会失去精度。而 `BigInt` 则没有这个限制，可以表示非常大的整数，直到内存耗尽。

在什么场景下会使用 `BigInt` 呢？

#### 1. 大整数计算

当需要进行大整数的精确计算时，例如在密码学、加密算法或者处理大数据时，`BigInt` 可以确保计算的精度，而不会失去精度。

```javascript
const bigNum = BigInt("1234567890123456789012345678901234567890");
const result = bigNum ** 1000;
console.log(result);
```

#### 2. 处理大数据量

在处理需要高精度整数计算的大数据量时，例如在科学计算、金融领域或者大型计算任务中，`BigInt` 可以确保精度，避免计算结果的溢出。

#### 3. 处理日期和时间

在处理日期和时间的差值时，`BigInt` 可以确保计算的精度，尤其是在需要精确到毫秒或更小时间单位的场景下。

```javascript
const startTime = BigInt(Date.now());
// 执行一些耗时操作
const endTime = BigInt(Date.now());
const elapsedTime = endTime - startTime;
console.log(`耗时：${elapsedTime} 毫秒`);
```

#### 4. 处理大型数值问题

在处理具有极大数值的问题时，例如在数学领域的一些计算中，`BigInt` 可以确保精度，避免因为超出 Number 类型的范围而导致计算错误。

需要注意的是，`BigInt` 和 `Number` 是两种不同的数据类型，它们之间的运算是不允许的。例如，你不能将一个 `BigInt` 和一个 `Number` 相加，需要确保参与运算的数据类型是一致的。当然，你可以将 `BigInt` 转换为 `Number` 进行运算。

<br/>

### null 是不是一个对象，如果是，如何判断一个对象是 null，不使用 JavaScript 提供的 api 如何进行判断

公司：滴滴

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/317)
在 JavaScript 中，`null` 是一个特殊的原始值，表示一个空对象引用。尽管 `null` 是一个对象类型，但它不是一个对象。因此，严格来说，`null` 不是一个对象。

如果你想判断一个对象是否为 `null`，可以使用以下方法：

1. 使用严格相等运算符 `===` 进行比较：
   ```js
   if (obj === null) {
     // 对象是 null
   }
   ```

   这种方法是最常用的，因为它可以准确地判断一个对象是否为 `null`。严格相等运算符 `===` 不会进行类型转换，只有在两个操作数的类型相同且值相等时才返回 `true`。

2. 使用类型运算符 `typeof` 进行判断：
   ```js
   if (typeof obj === "object" && obj === null) {
     // 对象是 null
   }
   ```

   这种方法首先使用 `typeof` 运算符检查对象的类型是否为 `"object"`，然后再判断对象是否为 `null`。需要注意的是，`typeof null` 返回 `"object"`，这是一个历史遗留问题。

如果你不想使用 JavaScript 提供的 API，可以使用以下方法进行判断：

1. 使用对象的 `toString` 方法：
   ```js
   if (Object.prototype.toString.call(obj) === "[object Null]") {
     // 对象是 null
   }
   ```

   这种方法通过调用对象的 `toString` 方法，并使用 `call` 方法将其上下文设置为 `Object.prototype`，然后比较返回的字符串是否为 `"[object Null]"`。

2. 使用对象的 `valueOf` 方法：
   ```js
   if (obj && obj.valueOf() === null) {
     // 对象是 null
   }
   ```

   这种方法首先检查对象是否存在（不是 `null` 或 `undefined`），然后调用对象的 `valueOf` 方法，并比较返回的值是否为 `null`。

<br/>

### 说一下对于堆栈的理解

公司：滴滴、高德

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/)
在计算机科学中，堆栈（Stack）是一种常见的数据结构，它是一系列元素的集合，其中的元素按照“后进先出”（Last In, First Out，LIFO）的原则进行添加和删除。

#### 特性：

1. **后进先出（LIFO）：** 最后被添加进堆栈的元素是第一个被移除的。这就意味着在堆栈中，最新的元素总是在堆栈的顶部，而最旧的元素在底部。

2. **只能在堆栈的顶部添加或删除元素：** 只能在堆栈的顶部进行插入（称为“推入”，Push）和删除（称为“弹出”，Pop）操作。其他位置的元素无法直接访问或修改。

#### 堆栈的基本操作：

1. **Push（推入）：** 将元素添加到堆栈的顶部。
2. **Pop（弹出）：** 从堆栈的顶部移除元素。
3. **Peek（查看栈顶元素）：** 获取堆栈顶部的元素，但不将其移除。
4. **IsEmpty（判空）：** 检查堆栈是否为空。
5. **Size（大小）：** 获取堆栈中元素的个数。

#### 应用场景：

1. **函数调用和递归：** 堆栈被用于跟踪函数的调用和返回。每次函数被调用时，相关的信息（例如函数参数、局部变量等）被推入堆栈。当函数返回时，这些信息被弹出，恢复到调用函数的状态。

2. **表达式求值：** 堆栈可以用于计算表达式，特别是中缀表达式转换为后缀表达式，然后利用堆栈求值。

3. **浏览器的前进和后退功能：** 浏览器使用堆栈来存储用户的浏览历史，以便用户可以随时返回到之前浏览的页面。

4. **Undo（撤销）功能：** 许多应用程序使用堆栈来实现撤销操作。每次用户执行一个操作时，相关的信息被推入堆栈，用户点击“撤销”时，相关信息被弹出，恢复到之前的状态。

<br/>

### `[] == ![]`为什么 

公司：高德

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/313)

首先，让我们看一下 `[]` 是一个空数组，而 `![]` 是对空数组的逻辑非运算，它将空数组转换为布尔值。在 JavaScript 中，空数组会被视为"真值"，所以 `![]` 的结果是 `false`。

现在，表达式变成了 `[] == false`。

接下来，JavaScript 进行了类型转换，尝试将 `[]` 和 `false` 转换为相同的类型，以便进行比较。在比较之前，它会将 `false` 转换为数字类型。在 JavaScript 中，`false` 被转换为数字时会变成 `0`。

现在，表达式变成了 `[] == 0`。

接下来，JavaScript 尝试将空数组 `[]` 转换为数字。空数组在转换为数字时会变成 `0`。因此，最终的表达式是 `0 == 0`。

现在，JavaScript执行比较操作。因为 `0` 等于 `0`，所以整个表达式 `[] == ![]` 的结果是 `true`。

<br/>

### 如何把真实 dom 转变为虚拟 dom，代码实现一下 

公司：高德

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/310)
将真实 DOM 转换为虚拟 DOM 是前端开发中常见的操作，它可以提高性能和开发效率。下面是一个简单的代码示例，展示了如何将真实 DOM 转换为虚拟 DOM。

首先，我们需要定义一个虚拟 DOM 的数据结构，可以使用一个 JavaScript 对象来表示，包含标签名、属性、子节点等信息。例如：

```javascript
class VNode {
  constructor(tag, props, children) {
    this.tag = tag;
    this.props = props;
    this.children = children;
  }
}
```

接下来，我们可以编写一个函数来将真实 DOM 转换为虚拟 DOM。这个函数可以递归地遍历真实 DOM 的节点，并根据节点类型创建对应的虚拟 DOM 节点。例如：

```javascript
function createVNodeFromRealNode(node) {
  if (node.nodeType === Node.TEXT_NODE) {
    // 文本节点
    return new VNode(undefined, undefined, node.nodeValue);
  } else if (node.nodeType === Node.ELEMENT_NODE) {
    // 元素节点
    const tagName = node.tagName.toLowerCase();
    const props = {};
    const children = [];

    // 处理属性
    for (const attr of node.attributes) {
      props[attr.name] = attr.value;
    }

    // 处理子节点
    for (const childNode of node.childNodes) {
      const childVNode = createVNodeFromRealNode(childNode);
      children.push(childVNode);
    }

    return new VNode(tagName, props, children);
  } else {
    // 其他节点类型，如注释节点等
    return null;
  }
}
```

这个函数会根据传入的真实 DOM 节点类型进行不同的处理。如果是文本节点，将其值作为虚拟 DOM 的内容；如果是元素节点，将其标签名、属性和子节点转换为虚拟 DOM 的对应属性。

使用这个函数，我们可以将一个真实的 DOM 节点转换为虚拟 DOM 节点。例如：

```javascript
const realNode = document.getElementById("myElement");
const virtualNode = createVNodeFromRealNode(realNode);
console.log(virtualNode);
```

<br/>

### 说一下错误监控的实现，错误监控的正确使用方式，日志如何分等级

公司：高德

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/309)
错误监控（Error Monitoring）是在应用程序中捕获、记录和分析错误的一种技术，以便开发人员可以在生产环境中迅速发现、定位和解决问题。以下是错误监控的实现、正确使用方式以及日志分级的相关信息：

#### 1. 错误监控的实现：

错误监控通常通过前端错误监控工具（例如Sentry、Bugsnag、Rollbar等）或自定义的日志系统来实现。这些工具可以捕获JavaScript错误、网络请求错误、API错误等，并将错误信息发送到后端服务器进行分析和记录。

#### 2. 错误监控的正确使用方式：

##### a. 引入错误监控工具：

```javascript
// 使用Sentry作为错误监控工具的例子
import * as Sentry from '@sentry/browser';

Sentry.init({
  dsn: 'YOUR_SENTRY_DSN',
  // 配置其他参数
});
```

##### b. 捕获和发送错误：

```javascript
try {
  // 可能引发错误的代码
} catch (error) {
  Sentry.captureException(error);
}
```

##### c. 记录自定义错误信息：

```javascript
Sentry.captureMessage('Custom error message');
```

##### d. 日志分级：

错误监控工具通常支持日志分级，常见的分级有：

- **Error（错误）：** 致命错误，会导致应用程序无法正常运行。
- **Warning（警告）：** 警告信息，表示存在问题但应用程序仍然可以正常运行。
- **Info（信息）：** 提供一般信息，例如用户操作成功完成等。
- **Debug（调试）：** 调试信息，用于开发和调试过程中的详细信息。

#### 3. 日志如何分等级：

在日志中引入等级（Level）的概念，可以根据日志的重要性和紧急性进行分类。常见的日志等级有：Error、Warning、Info、Debug。分级的好处在于，可以根据具体需求灵活地记录和处理不同级别的日志信息。

##### 示例（基于JavaScript的日志分级）：

```javascript
function log(message, level = 'info') {
  switch (level.toLowerCase()) {
    case 'error':
      console.error(`[Error] ${message}`);
      // 发送错误监控
      Sentry.captureException(new Error(message));
      break;
    case 'warning':
      console.warn(`[Warning] ${message}`);
      break;
    case 'info':
      console.log(`[Info] ${message}`);
      break;
    case 'debug':
      console.debug(`[Debug] ${message}`);
      break;
    default:
      console.log(message);
      break;
  }
}

// 使用
log('Something happened', 'info'); // Info级别日志
log('Unexpected error occurred', 'error'); // Error级别日志
```

<br/>

### 请写出以下代码执行结果

```js
var a = { x: 1 };
var b = a;
a.x = a = { n: 1 };
console.log(a); // ?
console.log(b); // ?
```

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/303)
这段代码中涉及了 JavaScript 中变量引用和赋值的概念，所以让我们逐步分析它。

1. 首先，我们创建一个对象 `a`，其中包含一个属性 `x`，并将其初始化为 `1`。
2. 然后，我们创建一个变量 `b`，并将其指向 `a`，即 `b` 和 `a` 都引用同一个对象。

此时，内存中的结构如下：
```
a ---> { x: 1 }
b -----|
```

3. 接下来，我们执行 `a.x = a = { n: 1 };` 这一行代码。这行代码可以分解为两个步骤：

   - `a.x = { n: 1 };`：首先，将对象 `a` 的属性 `x` 设置为一个新的对象 `{ n: 1 }`。此时，`a` 的内容发生变化，但 `b` 仍然指向旧的对象。
   - `a = { n: 1 };`：接着，将变量 `a` 重新赋值为一个新的对象 `{ n: 1 }`。现在，变量 `a` 引用了一个新的对象。

此时，内存中的结构如下：
```
a ---> { n: 1 }
b ---> { x: 1 }
```

4. 最后，我们打印变量 `a` 和 `b` 的值。

```js
console.log(a); // 输出: { n: 1 }
console.log(b); // 输出: { x: 1 }
```

因为 `b` 最初指向的是旧的对象，所以 `b` 仍然引用旧的对象 `{ x: 1 }`，而 `a` 已经被重新赋值为新的对象 `{ n: 1 }`，因此 `a` 输出的是新的对象。

<br/>

### 请写出以下代码执行结果

```js
Function.prototype.a = () = >{alert(1)}
Object.prototype.b = () = >{alert(2)}
function A(){};
const a = new A();
a.a();
a.b();
// 写出执行结果
```

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/302)
在这段代码中，给`Function.prototype`和`Object.prototype`分别添加了方法`a`和`b`。然后创建了一个构造函数`A`的实例`a`，接着尝试调用`a.a()`和`a.b()`。

在这里，`a.a()` 会执行，但 `a.b()` 不会执行，因为`a`是通过`A`构造函数创建的实例，它的原型链上并没有`b`这个方法。

所以，代码的执行结果为：

1. 弹出 `1`（因为`a.a()`会调用`Function.prototype`上的`a`方法）。
2. `a.b()` 会抛出错误，因为`a`的原型链上并没有`b`方法。

<br/>

### 请写出以下代码执行结果

```js
let a = 0;
console.log(a);
console.log(b);
let b = 0;
console.log(c);
function c() {}
// 写出执行结果
```

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/301)
这段代码中涉及到变量提升（hoisting）和函数声明提升的概念，让我们逐步分析它。

1. 首先，我们声明了一个变量 `a` 并将其初始化为 `0`。
2. 紧接着，我们尝试打印变量 `a`，这将输出 `0`。

3. 接下来，我们尝试打印变量 `b`，但在这一行之前并没有声明变量 `b`，因此这将导致一个 `ReferenceError`，代码无法继续执行。

4. 然后，我们声明了一个函数 `c`，这是一个函数声明，函数声明也会被提升到当前作用域的顶部。所以，即使在函数声明之前尝试打印 `c`，也不会导致错误。

此时，变量和函数声明的状态如下：

```js
Variable a: 0
Variable b: undefined
Function c: function c() {}
```

5. 最后，我们尝试打印变量 `c`，这将输出整个函数的源代码。所以，`console.log(c)` 将输出:

```js
function c() {}
```

总结：

- 变量 `a` 被正确初始化为 `0`，因此 `console.log(a)` 输出 `0`。
- 变量 `b` 尝试在声明之前打印，会导致 `ReferenceError`。
- 函数 `c` 被声明并提升到了作用域的顶部，因此 `console.log(c)` 输出整个函数的源代码。

<br/>

### 请写出以下代码执行结果

```js
var x = 10;
function a(y) {
  var x = 20;
  return b(y);
}
function b(y) {
  return x + y;
}
a(20);
// 写出执行结果
```

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/300)
在这段代码中，首先声明了一个全局变量 `x`，值为 10。然后定义了两个函数 `a` 和 `b`。函数 `a` 接受一个参数 `y`，在函数内部声明了一个局部变量 `x`，值为 20。函数 `a` 返回调用 `b(y)` 的结果，而函数 `b` 接受一个参数 `y`，并且返回全局变量 `x` 与参数 `y` 的和。

最后，调用 `a(20)`，其中 `a` 内部的 `b(y)` 调用的是全局变量 `x`，而不是函数 `a` 内部的局部变量 `x`。

因此，`a(20)` 的返回值为 `10 + 20 = 30`。但是，由于没有对 `a(20)` 的返回值进行处理，它不会被打印出来或者赋值给其他变量。所以，虽然函数被调用了，但没有输出或者其他影响。

<br/>

### 请写出以下代码执行结果

```js
console.log(1);
setTimeout(() => {
  console.log(2);
});
process.nextTick(() => {
  console.log(3);
});
setImmediate(() => {
  console.log(4);
});
new Promise((resolve) => {
  console.log(5);
  resolve();
  console.log(6);
}).then(() => {
  console.log(7);
});
Promise.resolve().then(() => {
  console.log(8);
  process.nextTick(() => {
    console.log(9);
  });
});
// 写出执行结果
```

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/299)
在Node.js环境中，这段代码的执行顺序如下：

1. `console.log(1);`：立即执行，打印 `1`。

2. `process.nextTick(() => { console.log(3); });`：由于`process.nextTick`的回调会在当前事件循环的末尾执行，所以此时它的回调被安排在最前面执行。打印 `3`。

3. `new Promise((resolve) => { console.log(5); resolve(); console.log(6); }).then(() => { console.log(7); });`：创建Promise并立即执行，打印 `5`，然后执行`resolve()`，然后打印 `6`。之后在下一个微任务阶段（microtask）执行`.then(() => { console.log(7); });`，打印 `7`。

4. `Promise.resolve().then(() => { console.log(8); process.nextTick(() => { console.log(9); }); });`：创建Promise并立即执行，执行`.then(() => { console.log(8); process.nextTick(() => { console.log(9); }); });`，打印 `8`。然后在当前微任务阶段执行`process.nextTick(() => { console.log(9); });`，打印 `9`。

5. `setTimeout(() => { console.log(2); });`：由于`setTimeout`的回调函数会在下一个事件循环执行，所以它会在当前事件循环的所有任务执行完毕后（包括微任务）被执行。打印 `2`。

6. `setImmediate(() => { console.log(4); });`：`setImmediate`的回调函数也会在下一个事件循环执行，但是它的执行时机比`setTimeout`要早，所以会在`setTimeout`之前执行。打印 `4`。

所以，最终的输出顺序是：

```
1
5
6
3
8
9
7
4
2
```

<br/>

### 请写出以下代码执行结果

```js
[1, 2, 3, 4, 5].map(parselnt);
// 写出执行结果
```

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/298)
在这段代码中，`map` 函数会遍历数组 `[1, 2, 3, 4, 5]` 中的每一个元素，然后对每个元素调用 `parseInt` 函数。但是需要注意的是，`parseInt` 函数的第一个参数是要被转换的字符串，而 `map` 的回调函数传递给 `parseInt` 的参数包括三个：当前元素、当前元素的索引、原数组本身。

所以，实际上 `parseInt` 函数的参数在执行时是这样的：

1. `parseInt("1", 0, [1, 2, 3, 4, 5])`，返回 `1`。
2. `parseInt("2", 1, [1, 2, 3, 4, 5])`，返回 `NaN`（因为基数为 1 时，字符串 "2" 不是有效的数字）。
3. `parseInt("3", 2, [1, 2, 3, 4, 5])`，返回 `3`。
4. `parseInt("4", 3, [1, 2, 3, 4, 5])`，返回 `NaN`（因为基数为 3 时，字符串 "4" 不是有效的数字）。
5. `parseInt("5", 4, [1, 2, 3, 4, 5])`，返回 `NaN`（因为基数为 4 时，字符串 "5" 不是有效的数字）。

所以，`map` 函数的返回值是 `[1, NaN, 3, NaN, NaN]`。

<br/>

### 请写出以下代码执行结果

```js
typeof typeof typeof [];
// 写出执行结果
```

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/297)
这段代码会返回字符串 `"string"`。

让我解释一下为什么：

1. `[]` 是一个空数组，它是对象的一种，所以 `typeof []` 返回字符串 `"object"`。
2. 然后，`typeof "object"` 返回字符串 `"string"`，因为字符串是 "object" 类型的。

<br/>


### 说一下什么是死锁

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/295)
死锁是指在并发系统中，两个或多个进程（或线程）因为彼此持有对方所需的资源而无法继续执行的状态。在死锁状态下，进程无法向前推进，系统也无法正常运行。

死锁通常发生在多个进程（或线程）同时竞争有限的资源时，每个进程都在等待其他进程释放资源，导致所有进程都无法继续执行。死锁的发生通常需要满足以下四个必要条件：

1. 互斥条件（Mutual Exclusion）：至少有一个资源只能同时被一个进程（或线程）占用，即一次只能有一个进程访问该资源。

2. 占有和等待条件（Hold and Wait）：进程（或线程）在持有至少一个资源的同时，还在等待获取其他进程（或线程）占有的资源。

3. 不可抢占条件（No Preemption）：已经分配给一个进程（或线程）的资源不能被强制性地抢占，只能由持有资源的进程主动释放。

4. 循环等待条件（Circular Wait）：存在一个进程（或线程）的资源申请序列，使得每个进程（或线程）都在等待下一个进程（或线程）所占有的资源。

当这四个条件同时满足时，就可能发生死锁。死锁的发生会导致系统停滞，无法继续执行，需要通过一些死锁处理机制来解决，例如死锁检测、死锁避免、死锁预防和死锁解除等方法。

为了避免死锁的发生，可以采取一些措施，如合理规划资源的分配顺序、避免进程（或线程）同时持有多个资源、引入资源预分配策略、引入资源剥夺策略等。这些措施可以帮助系统有效地避免或减少死锁的发生，提高系统的并发性和可靠性。

<br/>

### 实现以下代码

```js
function add() {
  // your code
}
function one() {
  // your code
}
function two() {
  // your code
}
console.log(add(one(two()))); //3
console.log(add(two(one()))); //3
```

公司：快手

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/294)
你想要实现的代码似乎是一个函数式编程示例，其中有三个函数：`add`、`one` 和 `two`。这些函数可以通过嵌套的方式来实现，以使 `console.log` 语句能够输出正确的结果。

以下是实现这些函数的代码：

```js
function add(x) {
  return function (y) {
    return x + y;
  };
}

function one(x) {
  return x(1);
}

function two(x) {
  return x(2);
}

console.log(add(one(two()))); // 3
console.log(add(two(one()))); // 3
```

这里的 `add` 函数返回一个接受一个参数 `x` 的匿名函数，该匿名函数返回另一个函数，该函数接受参数 `y` 并返回 `x + y` 的结果。这样，你可以嵌套调用 `add(one(two()))` 和 `add(two(one()))`，分别传递函数的返回值，最终得到正确的结果。

<br/>

### 请实现一个 cacheRequest 方法，保证发出多次同一个 ajax 请求时都能拿到数据，而实际上只发出一次请求

公司：快手

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/293)
你可以使用一个缓存对象（Cache Object）来保存已经发出请求的结果，然后在每次请求前先检查缓存中是否已有该请求的结果。如果有，则直接返回缓存的结果，如果没有，则发出请求并将结果缓存起来。以下是一个示例的实现：

```javascript
// 创建一个缓存对象
const cache = {};

// 定义 cacheRequest 方法
function cacheRequest(url) {
  // 检查缓存中是否有该请求的结果
  if (cache[url]) {
    // 如果有缓存，直接返回缓存的结果
    return Promise.resolve(cache[url]);
  } else {
    // 如果没有缓存，发出请求并将结果缓存起来
    return fetch(url)
      .then(response => response.json())
      .then(data => {
        cache[url] = data; // 将结果存入缓存对象
        return data; // 返回结果
      })
      .catch(error => {
        throw error; // 抛出错误
      });
  }
}

// 示例用法
cacheRequest('https://api.example.com/data')
  .then(data => console.log(data))
  .catch(error => console.error(error));

// 在第二次调用时，会直接返回缓存的结果，而不会再发出请求
cacheRequest('https://api.example.com/data')
  .then(data => console.log(data))
  .catch(error => console.error(error));
```

在这个示例中，`cacheRequest` 方法接受一个 URL 作为参数。它首先检查缓存对象 `cache` 中是否已有该 URL 的结果。如果已经有缓存，则直接返回缓存的结果；如果没有缓存，则发出请求，获取数据，并将数据存入缓存对象。这样，就能保证多次请求同一个 URL 时只发出一次实际的请求，而后续请求会直接使用缓存的数据。

<br/>

### 实现一个函数柯里化

公司：快手

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/292)
柯里化（Currying）是一种将多参数函数转换为一系列接受单个参数的函数的技术。这种转换使得函数更加灵活和可组合。下面是一个详细的 JavaScript 实现：

```js
function curry(func) {
  return function curried(...args) {
    if (args.length >= func.length) {
      return func(...args);
    } else {
      return function (...moreArgs) {
        return curried(...args, ...moreArgs);
      };
    }
  };
}
```

这个 `curry` 函数接受一个函数 `func` 作为参数，并返回一个新的函数 `curried`。`curried` 函数负责收集参数，直到参数的数量足够执行原始函数 `func`。

使用这个 `curry` 函数，你可以将任何多参数函数转换为柯里化函数。例如，我们可以使用它来创建一个加法函数：

```js
function add(x, y, z) {
  return x + y + z;
}

// 使用柯里化函数
const curriedAdd = curry(add);

console.log(curriedAdd(2)(3)(4)); // 输出 9
console.log(curriedAdd(2, 3)(4)); // 输出 9
console.log(curriedAdd(2)(3, 4)); // 输出 9
```

在上面的例子中，我们首先使用 `curry` 函数将 `add` 函数转换为柯里化函数 `curriedAdd`。然后，我们可以通过连续调用 `curriedAdd` 来传递参数，每次只传递一个参数。最终，我们得到了加法的结果。

柯里化函数的优点是它们更加灵活和可组合。你可以部分应用函数，只传递一部分参数，并在后续调用中添加更多参数。这种灵活性使得函数可以更好地适应不同的使用场景。

<br/>

### 说一下对原型链的理解，画一个经典的原型链图示

公司：脉脉、兑吧、快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/279)
原型链是 JavaScript 中的一个重要概念，它是实现继承和属性查找的机制。每个对象都有一个指向其原型对象（prototype）的链接，当在一个对象上访问属性或方法时，如果该对象本身没有这个属性或方法，JavaScript 引擎会沿着原型链向上查找，直到找到属性或方法为止。

下面是一个经典的原型链示意图：

```
+-----------------+        +-----------------+
|    Object       |        |    Function     |
+-----------------+        +-----------------+
         ^                           ^
         |                           |
         |                           |
         |                           |
         |                           |
         v                           v
+-----------------+        +-----------------+
|   CustomObject  |        | CustomFunction  |
+-----------------+        +-----------------+
         ^                           ^
         |                           |
         |                           |
         |                           |
         |                           |
         v                           v
+-----------------+        +-----------------+
|    myObject     |        |   myFunction    |
+-----------------+        +-----------------+
```

在这个示意图中，`Object` 和 `Function` 是 JavaScript 中的内置对象，它们分别是所有对象和函数对象的原型。`CustomObject` 和 `CustomFunction` 是自定义对象和自定义函数对象，它们的原型分别指向 `Object` 和 `Function`。

在原型链中，每个对象都有一个 `__proto__` 属性，指向它的原型对象。当我们访问一个对象的属性或方法时，如果该对象本身没有该属性或方法，JavaScript 引擎会沿着 `__proto__` 链向上查找，直到找到属性或方法或者 `__proto__` 为 `null`（即原型链的顶端）为止。

例如，如果我们在 `myObject` 中访问一个属性，JavaScript 引擎会按照以下顺序查找：

1. 查找 `myObject` 自身是否有该属性。
2. 如果没有，在 `myObject.__proto__`（即 `CustomObject.prototype`）中查找。
3. 如果还没有，在 `CustomObject.prototype.__proto__`（即 `Object.prototype`）中查找。
4. 如果还没有，在 `Object.prototype.__proto__`（即 `null`）中查找，如果找到，返回该属性或方法；如果没有找到，返回 `undefined`。

这样的查找过程构成了一个链式结构，就是原型链。

<br/>

### 说一下 ajax/axios/fetch 的区别

公司：脉脉

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/277)
`ajax`、`axios` 和 `fetch` 都是用于在前端发起网络请求的工具，它们在使用和功能上有一些区别：

#### 1. Ajax（XMLHttpRequest）：

- **特点：**
  - 原生的JavaScript技术，基于XMLHttpRequest对象。
  - 支持各种请求类型（GET、POST等）和数据格式（JSON、XML等）。
  - 可以实现异步请求，通过回调函数处理响应。
  - 相对底层，需要手动处理请求、响应、错误等。

- **示例：**
  
  ```javascript
  var xhr = new XMLHttpRequest();
  xhr.open("GET", "https://api.example.com/data", true);
  xhr.onreadystatechange = function () {
    if (xhr.readyState === 4 && xhr.status === 200) {
      var data = JSON.parse(xhr.responseText);
      console.log(data);
    }
  };
  xhr.send();
  ```

#### 2. Axios：

- **特点：**
  - 基于Promise的HTTP客户端，可以在浏览器和Node.js中使用。
  - 提供丰富的API，支持请求和响应拦截、自动转换JSON等。
  - 更容易使用和配置，支持异步请求和并发请求。

- **示例：**

  ```javascript
  axios.get("https://api.example.com/data")
    .then(function (response) {
      console.log(response.data);
    })
    .catch(function (error) {
      console.error(error);
    });
  ```

#### 3. Fetch：

- **特点：**
  - 基于Promise的现代API，是XMLHttpRequest的替代品。
  - 内置在浏览器中，不需要额外的库或polyfill。
  - 更简洁的API，支持请求和响应拦截，更灵活的数据处理。

- **示例：**

  ```javascript
  fetch("https://api.example.com/data")
    .then(function(response) {
      return response.json();
    })
    .then(function(data) {
      console.log(data);
    })
    .catch(function(error) {
      console.error(error);
    });
  ```

#### 区别总结：

- **语法和易用性：**
  - `ajax` 是相对底层，需要手动处理很多细节。
  - `axios` 提供了更丰富和易用的API，支持Promise，使用更方便。
  - `fetch` 是现代的API，基于Promise，语法简洁，更加现代化。

- **兼容性：**
  - `ajax` 兼容性较好，支持绝大部分浏览器。
  - `axios` 兼容性较好，支持绝大部分浏览器，包括IE。
  - `fetch` 兼容性较好，但是在IE浏览器中需要polyfill。

- **功能和扩展性：**
  - `axios` 和 `fetch` 支持请求和响应拦截，更容易扩展功能。
  - `fetch` 内置在浏览器中，不需要额外的库或polyfill。

选择使用哪个工具取决于项目的需求和个人喜好。如果需要兼容性好、功能丰富的请求库，可以选择使用 `axios`。如果项目环境支持现代浏览器且不需要考虑IE的兼容性，可以考虑使用 `fetch`。

<br/>

### 用 Promise 封装一个 ajax

公司：脉脉

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/276)
你可以使用Promise来封装一个Ajax请求，这样可以更好地处理异步操作。下面是一个详细的示例，使用JavaScript来封装一个基本的Ajax请求：

```js
function ajax(url, method, data) {
  return new Promise(function(resolve, reject) {
    var xhr = new XMLHttpRequest();
    xhr.open(method, url, true);

    xhr.onload = function() {
      if (xhr.status >= 200 && xhr.status < 300) {
        resolve(xhr.responseText);
      } else {
        reject(new Error(xhr.statusText));
      }
    };

    xhr.onerror = function() {
      reject(new Error('Network Error'));
    };

    if (method === 'POST') {
      xhr.setRequestHeader('Content-Type', 'application/json');
      xhr.send(JSON.stringify(data));
    } else {
      xhr.send();
    }
  });
}

// 使用示例
ajax('https://api.example.com/data', 'GET')
  .then(function(response) {
    console.log('GET Request Successful:', response);
  })
  .catch(function(error) {
    console.error('Error:', error);
  });

// 如果需要发送POST请求
var postData = { key: 'value' };
ajax('https://api.example.com/postData', 'POST', postData)
  .then(function(response) {
    console.log('POST Request Successful:', response);
  })
  .catch(function(error) {
    console.error('Error:', error);
  });
```

在上述示例中，`ajax` 函数接受三个参数：`url` 表示请求的URL，`method` 表示请求的HTTP方法（GET或POST），`data` 是要发送的数据（仅在POST请求时使用）。

这个函数返回一个Promise对象，通过使用XMLHttpRequest来执行Ajax请求。当请求成功时，Promise将调用 `resolve` 函数，并传递响应文本。如果出现错误，将调用 `reject` 函数，并传递一个错误对象。

你可以使用`.then()`来处理成功的响应，使用`.catch()`来处理错误情况。这样可以更好地处理Ajax请求的异步性质，使代码更具可读性和可维护性。

<br/>

### 描述 DOM 事件捕获的具体流程

公司：自如

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/272)
DOM 事件捕获是指当一个事件在DOM树中被触发时，从根节点开始，逐级向下传播直到目标元素，然后再从目标元素逐级向上冒泡到根节点的过程。事件捕获的具体流程如下：

1. **事件触发：** 当用户在页面上进行操作（比如点击、鼠标移动等）时，浏览器会在相应的DOM元素上触发相应的事件。

2. **捕获阶段开始：** 事件从文档根节点（`<html>`）开始向下传播，按照DOM树的结构逐级往下。

3. **捕获阶段中的事件处理：** 在捕获阶段，如果在某个节点上绑定了相应事件的捕获阶段的处理函数（使用`addEventListener(event, handler, true)`绑定），那么这些处理函数会在相应的阶段被触发，按照DOM结构的顺序执行。捕获阶段不包括目标元素自身。

4. **目标元素的事件处理：** 事件到达目标元素，触发目标元素上绑定的事件处理函数。如果在目标元素上绑定了事件的处理函数，它会在这个阶段被执行。

5. **冒泡阶段开始：** 事件从目标元素开始冒泡，按照DOM树的相反顺序（由目标元素向上）逐级往上冒泡。

6. **冒泡阶段中的事件处理：** 在冒泡阶段，如果在某个节点上绑定了相应事件的冒泡阶段的处理函数（使用`addEventListener(event, handler, false)`绑定），那么这些处理函数会在相应的阶段被触发，按照DOM结构的相反顺序执行。冒泡阶段不包括目标元素自身。

7. **冒泡到根节点：** 事件一直冒泡到文档根节点（`<html>`）。

8. **默认行为和事件冒泡：** 在事件冒泡的过程中，如果某个处理函数调用了`event.preventDefault()`，则该事件的默认行为会被取消。如果事件处理函数没有调用`event.preventDefault()`，事件将继续冒泡到文档根节点。

通过事件捕获和冒泡，可以在DOM结构中的多个层级上响应相同的事件，也可以控制事件的传播和影响事件的默认行为。

<br/>

### 请实现`$on,$emit`

公司：自如

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/269)
`$on` 和 `$emit` 是事件订阅与发布模式的两个关键方法。在JavaScript中，你可以使用对象来模拟一个简单的事件系统。以下是一个基本实现：

```javascript
function EventBus() {
  this.events = {};
}

EventBus.prototype.$on = function(eventName, callback) {
  if (!this.events[eventName]) {
    this.events[eventName] = [];
  }
  this.events[eventName].push(callback);
};

EventBus.prototype.$emit = function(eventName, data) {
  if (this.events[eventName]) {
    this.events[eventName].forEach(function(callback) {
      callback(data);
    });
  }
};

// 示例用法
var eventBus = new EventBus();

// 订阅事件
eventBus.$on('message', function(data) {
  console.log('Received message:', data);
});

// 发布事件
eventBus.$emit('message', 'Hello, EventBus!');
```

在这个例子中，`EventBus` 是一个构造函数，它创建了一个简单的事件系统。`$on` 方法用于订阅事件，它接受一个事件名称和一个回调函数。`$emit` 方法用于发布事件，它接受一个事件名称和要传递的数据。当调用 `$emit` 方法时，会触发所有订阅该事件的回调函数，并且将数据传递给这些回调函数。

<br/>

### 实现 bind 方法，不能使用 call、apply、bind

公司：自如、腾讯应用宝、快手

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/268)
实现一个不依赖于原生 `call`、`apply` 或 `bind` 的 `bind` 方法，可以考虑使用闭包（closure）来创建一个新函数，其中包含了传入的函数和上下文。以下是一个示例实现：

```javascript
function customBind(func, context) {
  return function() {
    return func.apply(context, arguments);
  };
}

// 示例用法
function greet(name) {
  console.log(`Hello, ${name}! This is ${this.message}.`);
}

const obj = {
  message: 'a custom context'
};

const boundGreet = customBind(greet, obj);
boundGreet('Alice'); // 输出：Hello, Alice! This is a custom context.
```

在这个实现中，`customBind` 函数接受两个参数：要绑定的函数 `func` 和绑定的上下文 `context`。它返回一个新的函数，该函数在调用时会使用 `apply` 方法将传入的参数和指定的上下文传递给原始函数 `func`。

<br/>

### 手写实现 sleep 函数

公司：自如

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/267)
在JavaScript中，由于单线程的异步特性，通常不使用传统意义上的“sleep”函数，而是使用`setTimeout`或者`async/await`来实现类似的延时效果。下面是两种实现方式：

#### 使用 setTimeout 实现 sleep 函数：

```javascript
function sleep(ms) {
  return new Promise(resolve => setTimeout(resolve, ms));
}

async function example() {
  console.log('Start');
  await sleep(2000); // 等待2秒
  console.log('End');
}

example();
```

在上面的代码中，`sleep` 函数返回一个Promise对象，该Promise对象在指定的毫秒数后自动解决（resolve）。使用`await`关键字可以等待Promise对象的解决，从而实现延时效果。

#### 使用 Promise 实现 sleep 函数：

```javascript
function sleep(ms) {
  return new Promise(resolve => {
    setTimeout(() => {
      resolve();
    }, ms);
  });
}

async function example() {
  console.log('Start');
  await sleep(2000); // 等待2秒
  console.log('End');
}

example();
```

在这个版本的代码中，`sleep` 函数返回一个新的Promise对象，在指定的毫秒数后解决。`example` 函数使用 `await` 等待 `sleep` 函数的解决，实现了延时效果。

<br/>

### 请写出原生 js 如何设置元素高度

公司：自如

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/264)
在原生JavaScript中，你可以使用`style`属性来设置元素的高度。以下是几种设置元素高度的方法：

#### 1. 使用`style.height`属性：

```javascript
// 设置元素高度为200像素
var element = document.getElementById("myElement");
element.style.height = "200px";
```

#### 2. 使用`setAttribute`方法：

```javascript
// 设置元素高度为200像素
var element = document.getElementById("myElement");
element.setAttribute("style", "height: 200px;");
```

#### 3. 使用`style.setProperty`方法：

```javascript
// 设置元素高度为200像素
var element = document.getElementById("myElement");
element.style.setProperty("height", "200px");
```

<br/>

### 用原生 js 实现自定义事件

公司：自如

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/258)
在 JavaScript 中，你可以使用`CustomEvent`对象来创建自定义事件。以下是一个简单的例子：

```javascript
// 创建一个新的自定义事件
var event = new CustomEvent('customEventName', {
  detail: { key: 'value' } // 传递的数据
});

// 获取目标元素
var targetElement = document.getElementById('targetElement');

// 添加事件监听器，监听自定义事件
targetElement.addEventListener('customEventName', function(event) {
  console.log('Custom event triggered with data:', event.detail);
});

// 触发自定义事件
targetElement.dispatchEvent(event);
```

在这个例子中，我们使用`CustomEvent`构造函数创建了一个名为`customEventName`的自定义事件，并传递了一个`detail`属性，其中包含了传递的数据（这里是一个键值对）。然后，我们使用`addEventListener`方法在目标元素上添加了一个事件监听器，监听自定义事件。最后，使用`dispatchEvent`方法触发了自定义事件。

<br/>

### 如何识别出字符串中的回车并进行换行？

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/257)
在JavaScript中，你可以使用正则表达式来识别字符串中的回车符并进行换行操作。下面是一种常见的方法，使用`replace()`函数和正则表达式：

```javascript
var stringWithCarriageReturn = "Hello\nWorld! This is a text with a line break.";

// 使用正则表达式识别回车符并替换为换行符
var stringWithLineBreak = stringWithCarriageReturn.replace(/\n/g, '<br>');

console.log(stringWithLineBreak);
```

在上面的代码中，`\n`是回车符的转义符，`/g`是正则表达式中的全局标志，表示全局匹配。`replace()`函数将回车符`\n`替换为HTML换行符`<br>`，这样字符串中的每个回车符都会被替换为换行。

<br/>

### 输入一个日期 返回几秒前、几小时前、几天前、几月前

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/255)
为了实现将给定日期转换为“几秒前”、“几小时前”、“几天前”或“几月前”的格式，你可以使用 JavaScript 的 Date 对象来处理日期和时间，并进行一些计算。以下是一个基本的实现方法：

```javascript
function formatTimeAgo(dateString) {
  const pastDate = new Date(dateString);
  const currentDate = new Date();
  const timeDifference = Math.abs(currentDate - pastDate);
  
  const seconds = Math.floor(timeDifference / 1000);
  if (seconds < 60) {
    return seconds + '秒前';
  }

  const minutes = Math.floor(seconds / 60);
  if (minutes < 60) {
    return minutes + '分钟前';
  }

  const hours = Math.floor(minutes / 60);
  if (hours < 24) {
    return hours + '小时前';
  }

  const days = Math.floor(hours / 24);
  if (days < 30) {
    return days + '天前';
  }

  const months = Math.floor(days / 30);
  return months + '月前';
}

// 示例用法
const dateString = '2023-01-15T12:00:00Z'; // 输入日期字符串
const timeAgo = formatTimeAgo(dateString);
console.log(timeAgo); // 输出类似于 "几天前" 的格式
```

在这个实现中，`formatTimeAgo` 函数接受一个日期字符串（例如 `'2023-01-15T12:00:00Z'`），并将其转换为“几秒前”、“几分钟前”、“几小时前”或“几天前”的格式，具体格式取决于与当前时间的差距。请注意，这个实现方法假设所有月份都是30天，这是一个简化的做法，实际上月份的天数是不固定的。你可以根据需要进一步优化这个方法。

<br/>

### 将 153812.7 转化为 153,812.7

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/244)
要将数字 153812.7 转化为带有逗号的格式（例如 153,812.7），你可以使用 JavaScript 的 `toLocaleString()` 方法，该方法用于将数字格式化为本地化的字符串表示形式。以下是具体的示例代码：

```javascript
const number = 153812.7;
const formattedNumber = number.toLocaleString('en-US');
console.log(formattedNumber); // 输出：153,812.7
```

在这个例子中，`toLocaleString()` 方法使用 `'en-US'` 作为参数，表示使用美国英语环境的本地化规则，将数字格式化为带有逗号的字符串。你可以根据需要修改参数，选择不同的地区和语言环境。

<br/>

### 数组有哪些方法 讲讲区别跟使用场景

公司：掌门一对一

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/410)
JavaScript 中的数组有很多内置方法，每个方法都有自己的特性和用途。下面是一些常用的数组方法，以及它们的区别和使用场景：

#### 1. **`push()`和`pop()`：**

- **`push()`** 方法用于在数组末尾添加一个或多个元素，并返回新数组的长度。
  ```javascript
  const arr = [1, 2, 3];
  arr.push(4);
  // arr 变为 [1, 2, 3, 4]
  ```

- **`pop()`** 方法用于移除数组末尾的元素，并返回被移除的元素。
  ```javascript
  const arr = [1, 2, 3];
  const removedElement = arr.pop();
  // removedElement 是 3，arr 变为 [1, 2]
  ```

#### 2. **`unshift()`和`shift()`：**

- **`unshift()`** 方法用于在数组的开头添加一个或多个元素，并返回新数组的长度。
  ```javascript
  const arr = [2, 3];
  arr.unshift(1);
  // arr 变为 [1, 2, 3]
  ```

- **`shift()`** 方法用于移除数组的第一个元素，并返回被移除的元素。
  ```javascript
  const arr = [1, 2, 3];
  const removedElement = arr.shift();
  // removedElement 是 1，arr 变为 [2, 3]
  ```

#### 3. **`concat()`：**

- **`concat()`** 方法用于连接两个或多个数组，并返回一个新数组。
  ```javascript
  const arr1 = [1, 2];
  const arr2 = [3, 4];
  const newArr = arr1.concat(arr2);
  // newArr 是 [1, 2, 3, 4]
  ```

#### 4. **`join()`：**

- **`join()`** 方法用于将数组中的所有元素转化为字符串，并将它们连接起来。
  ```javascript
  const arr = [1, 2, 3];
  const str = arr.join('-');
  // str 是 "1-2-3"
  ```

#### 5. **`slice()`：**

- **`slice(start, end)`** 方法返回一个新数组，包含从原数组中指定开始到结束（不包括结束）的元素。
  ```javascript
  const arr = [1, 2, 3, 4, 5];
  const slicedArr = arr.slice(1, 4);
  // slicedArr 是 [2, 3, 4]
  ```

#### 6. **`splice()`：**

- **`splice(start, deleteCount, ...items)`** 方法用于在指定位置删除/替换若干元素，并且可以在该位置插入新的元素，返回被删除的元素组成的数组。
  ```javascript
  const arr = [1, 2, 3, 4, 5];
  const removedElements = arr.splice(1, 2, 6, 7);
  // removedElements 是 [2, 3]，arr 变为 [1, 6, 7, 4, 5]
  ```

#### 7. **`forEach()`：**

- **`forEach(callback(currentValue, index, array))`** 方法用于遍历数组的每个元素，执行提供的回调函数。
  ```javascript
  const arr = [1, 2, 3];
  arr.forEach(function(item, index) {
    console.log(item, index);
  });
  // 输出：1 0，2 1，3 2
  ```

#### 8. **`map()`：**

- **`map(callback(currentValue, index, array))`** 方法用于遍历数组的每个元素，执行提供的回调函数，并返回一个新数组，新数组的每个元素是回调函数的返回值。
  ```javascript
  const arr = [1, 2, 3];
  const mappedArr = arr.map(function(item) {
    return item * 2;
  });
  // mappedArr 是 [2, 4, 6]
  ```

#### 9. **`filter()`：**

- **`filter(callback(currentValue, index, array))`** 方法用于遍历数组的每个元素，执行提供的回调函数，并返回一个新数组，新数组只包含满足回调函数条件的元素。
  ```javascript
  const arr = [1, 2, 3, 4, 5];
  const filteredArr = arr.filter(function(item) {
    return item > 2;
  });
  // filteredArr 是 [3, 4, 5]
  ```

#### 10. **`reduce()`：**

- **`reduce(callback(accumulator, currentValue, index, array), initialValue)`** 方法用于累积数组中的所有元素，返回一个单一的值。
  ```javascript
  const arr = [1, 2, 3, 4, 5];
  const sum = arr.reduce(function(accumulator, item) {
    return accumulator + item;
  }, 0);
  // sum 是 15
  ```

#### 11. **`every()` 和 `some()`：**

- **`every(callback(currentValue, index, array))`** 方法用于检查数组中的所有元素是否都符合条件。
- **`some(callback(currentValue, index, array))`** 方法用于检查数组中是否有至少一个元素符合条件。
  ```javascript
  const arr = [1, 2, 3, 4, 5];
  const all

<br/>

### 讲一下函数式编程

公司：掌门一对一

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/408)
函数式编程（Functional Programming）是一种编程范式，它将计算视为数学函数的求值，并避免改变状态和可变数据。在函数式编程中，函数是一等公民，可以作为参数传递给其他函数，也可以作为返回值返回。函数式编程强调使用纯函数（Pure Functions），即不依赖外部状态，不改变状态，对于相同的输入始终产生相同的输出。以下是函数式编程的一些关键概念和特性：

#### 1. **纯函数（Pure Functions）：**
纯函数是指在相同的输入下，总是返回相同的输出，并且没有副作用（没有改变外部状态的行为）。纯函数不依赖于外部状态，只依赖于输入参数，这种特性使得它们更容易被理解和测试。

```javascript
// 纯函数示例
function add(a, b) {
  return a + b;
}
```

#### 2. **不可变性（Immutability）：**
函数式编程鼓励使用不可变数据（Immutable Data），即数据一旦创建就不能被修改。在JavaScript中，可以使用const和Object.freeze等机制来实现不可变性。

```javascript
const array = [1, 2, 3];
// 不可变性示例
const newArray = [...array, 4]; // 创建了一个新的数组，array不被修改
```

#### 3. **高阶函数（Higher-Order Functions）：**
高阶函数是指能够接受一个或多个函数作为参数，或者返回一个函数的函数。它们可以用来组合函数、抽象控制流程、创建可复用的函数等。

```javascript
// 高阶函数示例
function multiplyBy(factor) {
  return function(number) {
    return number * factor;
  };
}

const double = multiplyBy(2);
console.log(double(3)); // 输出 6
```

#### 4. **函数组合（Function Composition）：**
函数组合是将多个函数组合成一个函数的过程。在函数式编程中，函数通常被视为数据转换的管道，每个函数负责一个特定的转换操作。

```javascript
// 函数组合示例
const add = x => x + 2;
const multiply = x => x * 3;

const composedFunction = x => multiply(add(x));
console.log(composedFunction(3)); // 输出 15
```

#### 5. **递归（Recursion）：**
函数式编程通常使用递归来解决问题，因为它可以替代循环，并且适用于处理递归数据结构。

```javascript
// 递归示例：计算阶乘
function factorial(n) {
  if (n === 0) {
    return 1;
  }
  return n * factorial(n - 1);
}
console.log(factorial(5)); // 输出 120
```

#### 6. **柯里化（Currying）：**
柯里化是将一个接受多个参数的函数转变为一系列接受单一参数的函数的过程。柯里化可以帮助我们创建更灵活的函数。

```javascript
// 柯里化示例
function add(a) {
  return function(b) {
    return a + b;
  };
}

const add2 = add(2);
console.log(add2(3)); // 输出 5
```

函数式编程的优势在于它能够提高代码的可读性、可维护性，以及方便进行单元测试。函数式编程也有助于处理并发、异步编程和复杂的数据转换。在JavaScript中，函数式编程的特性和方法被广泛应用于现代前端开发中。

<br/>

### promise 跟 async await 的区别，使用场景 

公司：网易、虎扑、沪江

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/407)
**Promise 和 Async/Await 的区别：**

1. **语法：**
   - **Promise：** Promise 是 JavaScript 提供的一种异步编程的解决方案，它使用 `.then()` 和 `.catch()` 方法处理异步操作。
   - **Async/Await：** Async/Await 是基于 Promise 的语法糖，它提供了一种更直观、更易读的方式来处理异步操作。Async 函数返回一个 Promise 对象。

2. **可读性：**
   - **Promise：** Promise 链式调用时，可能会导致嵌套过多，代码难以维护。
   - **Async/Await：** Async 函数的写法更接近同步代码，使得异步操作更易读，更易理解。

3. **错误处理：**
   - **Promise：** Promise 使用 `.catch()` 方法来处理错误。
   - **Async/Await：** 可以使用 `try/catch` 块来处理错误，使得错误处理更加直观。

4. **并发：**
   - **Promise：** 使用 `Promise.all()` 来并发执行多个异步操作。
   - **Async/Await：** 使用 `Promise.all()` 结合 Async/Await 来并发执行多个异步操作。

**使用场景：**

- **Promise：**
  - 当需要处理多个并发的异步操作，且不需要等待前一个操作完成就可以开始下一个操作时，可以使用 Promise。
  - 当需要更细致地控制异步操作的状态和流程时，可以使用 Promise。
  
```javascript
// 使用 Promise 处理异步操作
function fetchData() {
  return new Promise((resolve, reject) => {
    // 异步操作...
    if (success) {
      resolve(data);
    } else {
      reject(error);
    }
  });
}
```

- **Async/Await：**
  - 当需要处理多个异步操作，且下一个操作依赖于前一个操作的结果时，可以使用 Async/Await，它使得异步代码更易读。
  - 当需要更清晰地处理异步操作的错误时，可以使用 Async/Await，它支持使用 `try/catch` 捕获错误。

```javascript
// 使用 Async/Await 处理异步操作
async function fetchData() {
  try {
    const result1 = await asyncOperation1();
    const result2 = await asyncOperation2(result1);
    return result2;
  } catch (error) {
    console.error(error);
    throw error;
  }
}
```

总的来说，Async/Await 提供了更加直观、易读的异步编程语法，特别适用于处理多个异步操作依赖关系明确的场景。而 Promise 依然是处理异步操作的基础，特别适用于并发执行多个异步操作的场景。在实际项目中，根据具体需求选择合适的异步编程方式。

<br/>

### async、await 如何进行错误捕获

公司：虎扑

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/406)
在 Async/Await 中，错误的捕获通常使用 `try/catch` 语句。当使用 `await` 关键字调用一个返回 Promise 的异步函数时，如果该 Promise 被 reject，`await` 会抛出一个错误，可以通过 `try/catch` 来捕获这个错误。

以下是一个使用 Async/Await 进行错误捕获的示例：

```javascript
async function fetchData() {
  try {
    const result = await asyncOperation(); // 调用异步操作，如果 Promise 被 reject，这里会抛出错误
    console.log(result); // 成功时处理返回的数据
  } catch (error) {
    console.error(error); // 捕获错误并处理
  }
}

function asyncOperation() {
  return new Promise((resolve, reject) => {
    // 模拟异步操作
    setTimeout(() => {
      const success = Math.random() < 0.5; // 模拟成功和失败的情况
      if (success) {
        resolve('Data received successfully'); // 成功时，将数据传递给 resolve
      } else {
        reject('Error: Data request failed'); // 失败时，将错误信息传递给 reject
      }
    }, 1000);
  });
}

fetchData();
```

在上面的例子中，`fetchData` 函数使用 `await` 关键字调用 `asyncOperation` 函数。如果 `asyncOperation` 返回的 Promise 被 reject（模拟失败的情况），`await` 会抛出一个错误，然后被 `catch` 语句捕获，错误信息会被打印到控制台。

使用 `try/catch` 来捕获错误是 Async/Await 中处理异步错误的推荐方式，它使得异步代码的错误处理更加直观和清晰。

<br/>

### weak-Set、weak-Map 和 Set、Map 区别

公司：虎扑

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/399)
`WeakSet`、`WeakMap`、`Set` 和 `Map` 是 JavaScript 中的四种数据结构，它们在用途和特性上有一些区别：

#### 1. **Set 和 WeakSet：**

- **Set：** 是一个值的集合，每个值在 Set 中必须是唯一的。Set 中的值可以是任意数据类型，包括基本类型和对象引用。

  ```javascript
  const set = new Set();
  set.add(1);
  set.add(2);
  set.add(1); // 不会重复添加，Set 中的值必须是唯一的
  ```

- **WeakSet：** 是一种特殊的 Set，它只能存储对象引用，并且这些对象引用都是弱引用。WeakSet 中的对象是弱引用，不会阻止对象被垃圾回收。

  ```javascript
  const weakSet = new WeakSet();
  const obj = { key: 'value' };
  weakSet.add(obj);
  ```

#### 2. **Map 和 WeakMap：**

- **Map：** 是一种键值对的集合，可以用任意数据类型作为键。Map 中的键是唯一的，一个键只能对应一个值。

  ```javascript
  const map = new Map();
  map.set('key1', 'value1');
  map.set('key2', 'value2');
  ```

- **WeakMap：** 是一种特殊的 Map，它只能将对象作为键，并且这些对象键是弱引用，不会阻止对象被垃圾回收。

  ```javascript
  const weakMap = new WeakMap();
  const key = { id: 1 };
  weakMap.set(key, 'value');
  ```

#### 主要区别：

1. **弱引用：**
   - **WeakSet 和 WeakMap：** 只能存储对象引用，并且这些对象是弱引用，不会阻止对象被垃圾回收。如果一个对象在程序的其他地方没有被引用，它将被垃圾回收，此时它也会从 WeakSet 和 WeakMap 中移除。
   - **Set 和 Map：** 存储的对象不是弱引用，对象被 Set 或 Map 引用后，即使在程序的其他地方没有引用，它也不会被垃圾回收。

2. **遍历和迭代：**
   - **WeakSet 和 WeakMap：** 没有提供遍历和迭代的方法，因为无法获取其中的所有项。
   - **Set 和 Map：** 提供了遍历和迭代的方法，可以轻松获取其中的所有项。

3. **性能优化：**
   - **WeakSet 和 WeakMap：** 使用弱引用的特性，可以在特定场景下实现性能优化，比如存储临时数据或缓存。
   - **Set 和 Map：** 通常用于普通的数据存储，提供了更多的操作和功能。

选择使用哪种数据结构取决于你的需求。如果需要存储临时数据或需要弱引用的特性，可以使用 `WeakSet` 或 `WeakMap`。如果需要普通的键值对集合，并且需要遍历和迭代，可以使用 `Set` 或 `Map`。

<br/>

### valueOf 与 toString 的区别

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/395)
在 JavaScript 中，`valueOf()` 和 `toString()` 是 Object 基类中的两个方法，它们的作用是为了提供对象在字符串或数值上下文中的表现形式。它们的区别在于返回值的类型和优先级。

#### 1. **valueOf() 方法：**

- `valueOf()` 方法用于返回对象的原始值（primitive value），即对象的基本数据类型的值。`valueOf()` 的返回值可以是任何基本数据类型，包括数字、字符串和布尔值。

- 如果在某个表达式中需要对象的原始值，JavaScript 会首先调用 `valueOf()` 方法。如果 `valueOf()` 方法返回的不是原始值，JavaScript 再尝试调用 `toString()` 方法。

```javascript
const obj = {
  valueOf: function() {
    return 42;
  }
};

console.log(obj.valueOf()); // 输出 42
console.log(Number(obj));  // 输出 42，JavaScript 调用 valueOf() 方法
```

#### 2. **toString() 方法：**

- `toString()` 方法用于返回对象的字符串表示。大部分对象都继承了 Object 基类的 `toString()` 方法，返回的是对象的类型和内部标识。

- 如果需要将对象转换为字符串，JavaScript 会调用对象的 `toString()` 方法。如果对象没有自定义的 `toString()` 方法，它会使用 Object 基类中的 `toString()` 方法。

```javascript
const obj = {
  toString: function() {
    return "Hello, World!";
  }
};

console.log(obj.toString());  // 输出 "Hello, World!"
console.log(String(obj));    // 输出 "Hello, World!"，JavaScript 调用 toString() 方法
```

#### 区别和优先级：

1. 如果对象同时定义了 `valueOf()` 和 `toString()` 方法，JavaScript 会优先调用 `valueOf()` 方法。如果 `valueOf()` 返回的不是原始值，则再调用 `toString()` 方法。
  
2. 如果对象只定义了 `toString()` 方法，或者 `valueOf()` 方法返回的不是原始值，JavaScript 将调用 `toString()` 方法。

3. 如果对象没有定义 `valueOf()` 和 `toString()` 方法，JavaScript 会使用内置的 `Object.prototype.toString()` 方法，返回一个格式为 "[object Object]" 的字符串。

<br/>

### 怎么判断是一个空对象

公司：菜鸟网络

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/392)
在 JavaScript 中，有几种方法可以判断一个对象是否为空对象（即没有任何自身属性的对象）：

#### 1. **方法一：使用 Object.keys() 方法**

```javascript
function isEmptyObject(obj) {
  return Object.keys(obj).length === 0;
}

const emptyObject = {};
const nonEmptyObject = { key: 'value' };

console.log(isEmptyObject(emptyObject)); // 输出 true
console.log(isEmptyObject(nonEmptyObject)); // 输出 false
```

#### 2. **方法二：使用 for...in 循环**

```javascript
function isEmptyObject(obj) {
  for (let key in obj) {
    if (obj.hasOwnProperty(key)) {
      return false;
    }
  }
  return true;
}

const emptyObject = {};
const nonEmptyObject = { key: 'value' };

console.log(isEmptyObject(emptyObject)); // 输出 true
console.log(isEmptyObject(nonEmptyObject)); // 输出 false
```

#### 3. **方法三：使用 Object.entries() 方法**

```javascript
function isEmptyObject(obj) {
  return Object.entries(obj).length === 0;
}

const emptyObject = {};
const nonEmptyObject = { key: 'value' };

console.log(isEmptyObject(emptyObject)); // 输出 true
console.log(isEmptyObject(nonEmptyObject)); // 输出 false
```

#### 4. **方法四：使用 JSON.stringify() 方法**

```javascript
function isEmptyObject(obj) {
  return JSON.stringify(obj) === '{}';
}

const emptyObject = {};
const nonEmptyObject = { key: 'value' };

console.log(isEmptyObject(emptyObject)); // 输出 true
console.log(isEmptyObject(nonEmptyObject)); // 输出 false
```

以上方法中，`Object.keys()` 和 `for...in` 循环只遍历对象的可枚举属性，而 `Object.entries()` 遍历所有属性，包括不可枚举属性。`JSON.stringify()` 方法将对象转换为 JSON 字符串，然后比较字符串是否为 "{}"。

<br/>

### 请写出下面代码的执行结果

```js
setTimeout(() => {
  console.log(0);
}, 0);
new Promise((res) => setTimeout(res, 0)).then(() => {
  console.log(1);
  setTimeout(() => {
    console.log(2);
  }, 0);
  new Promise((r = r())).then(() => {
    console.log(3);
  });
});
setTimeout(() => {
  console.log(4);
}, 0);
new Promise((res) => res()).then(() => {
  console.log(5);
});
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/391)
这段代码会输出以下内容：

```
1
5
0
2
4
```

让我们逐步解释为什么会有这样的输出：

1. **第一个 `setTimeout`：**
   - 使用了 `setTimeout(() => { console.log(0); }, 0);`，所以会被放入事件队列，等待执行。
  
2. **第一个 `Promise` 和 `then`：**
   - `new Promise((res) => setTimeout(res, 0)).then(() => { console.log(1); ...`，这个 Promise 会立即执行，并将 `then` 中的内容放入微任务队列，即 `console.log(1); ...`。
   - 在 `then` 中，又有一个 `setTimeout(() => { console.log(2); }, 0);`，它会被放入事件队列，但由于在微任务中，所以会在当前任务结束之后立即执行。
   - 然后有一个新的 `Promise((r = r())).then(() => { console.log(3); });`，这个 Promise 会立即执行，但由于 `r()` 是未定义的函数，会抛出错误（TypeError），但是由于没有处理错误，整个程序会终止执行。

3. **第二个 `setTimeout`：**
   - `setTimeout(() => { console.log(4); }, 0);` 会被放入事件队列，等待执行。
   
4. **第二个 `Promise` 和 `then`：**
   - `new Promise((res) => res()).then(() => { console.log(5); });`，这个 Promise 会立即执行，将 `then` 中的内容放入微任务队列，即 `console.log(5);`。

按照事件队列和微任务队列的执行顺序，最终输出的结果是 `1 5 0 2 4`。

<br/>

### 请写出下面代码的执行结果

```js
function Foo() {
  getName = function () {
    alert(1);
  };
  return this;
}
getName();
Foo.getName = function () {
  alert(2);
};
Foo.prototype.getName = function () {
  alert(3);
};
getName = function () {
  alert(4);
};

// 请写出下面的输出结果
getName();
Foo.getName();
new Foo().getName();
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/390)
当调用 `getName();` 时，由于在此之前 `getName` 已经被重新赋值为一个新的函数表达式，它的值是 `undefined`，而不是一个函数。因此，调用 `undefined` 会抛出错误。在浏览器环境中，通常会得到类似 "TypeError: getName is not a function" 的错误消息。

因此，实际输出结果是：

```
Uncaught TypeError: getName is not a function
```

在这个错误被抛出后，后续的代码 `Foo.getName();` 和 `new Foo().getName();` 将不会执行。

<br/>

### 请只用数组方法和 Math.random()在一条语句的情况下，实现生成给定位数的随机数组，例如生成 10 位随机数组[1.1,102.1,2,3,8,4,90,123,11,123],数组内数字随机生成。

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/387)
你可以使用 `Array.from()` 方法和 `Math.random()` 函数来生成给定位数的随机数组。以下是一个示例代码：

```javascript
const randomArray = Array.from({ length: 10 }, () => Math.random() * 100);
console.log(randomArray);
```

在这个例子中，`Array.from()` 方法会创建一个新数组，数组的长度由第一个参数指定（这里是 10）。第二个参数是一个回调函数，该回调函数会在新数组的每个元素上调用，用于生成随机数。`Math.random() * 100` 会生成 0 到 100 之间的随机数。

这将输出一个包含 10 个随机数字的数组，例如：

```
[ 12.345, 56.789, 23.456, 78.901, 9.876, 45.678, 34.567, 89.012, 67.890, 1.234 ]
```

<br/>

### 实现一个 setter 方法

```js
let setter = function (conten, key, value) {
  // your code
};
let n = {
  a: {
    b: {
      c: { d: 1 },
      bx: { y: 1 },
    },
    ax: { y: 1 },
  },
};
// 修改值
setter(n, "a.b.c.d", 3);
console.log(n.a.b.c.d); //3
setter(n, "a.b.bx", 1);
console.log(n.b.bx); //1
```

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/386)
要实现一个 setter 方法，你可以按照指定的路径（例如 "a.b.c.d"）将值设置到嵌套对象的特定属性上。以下是一个实现：

```js
let setter = function (content, key, value) {
  let keys = key.split(".");
  let temp = content;
  for (let i = 0; i < keys.length - 1; i++) {
    temp = temp[keys[i]];
  }
  temp[keys[keys.length - 1]] = value;
};

let n = {
  a: {
    b: {
      c: { d: 1 },
      bx: { y: 1 },
    },
    ax: { y: 1 },
  },
};

// 修改值
setter(n, "a.b.c.d", 3);
console.log(n.a.b.c.d); // 输出 3

setter(n, "a.b.bx", 1);
console.log(n.a.b.bx); // 输出 { y: 1 }
```

在这个实现中，`setter` 函数接受三个参数：`content` 是包含嵌套属性的对象，`key` 是属性的路径，`value` 是要设置的新值。函数首先将路径分割成单个键（使用 `split(".")`），然后遍历对象的嵌套属性，直到找到目标属性。最后，将新值设置到目标属性上。

<br/>

### setTimeout 与 setInterval 区别

公司：腾讯应用宝

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/384)
`setTimeout` 和 `setInterval` 是 JavaScript 中的两个定时器函数，它们的主要区别在于触发时机和使用方式。

#### `setTimeout`：

1. **触发时机：** `setTimeout` 函数用于在指定的延迟时间之后执行一次指定的代码。它只执行一次。

2. **使用方式：** `setTimeout` 接受两个参数：要执行的函数（或要执行的代码块）和延迟的毫秒数。例如：

    ```javascript
    setTimeout(function() {
      console.log('This will be logged after 1000 milliseconds.');
    }, 1000);
    ```

#### `setInterval`：

1. **触发时机：** `setInterval` 函数用于在指定的时间间隔内，重复执行指定的代码。它会一直重复执行，直到被清除（使用 `clearInterval` 函数）或页面被关闭。

2. **使用方式：** `setInterval` 同样接受两个参数：要执行的函数（或要执行的代码块）和时间间隔的毫秒数。例如：

    ```javascript
    setInterval(function() {
      console.log('This will be logged every 1000 milliseconds.');
    }, 1000);
    ```

#### 区别总结：

- `setTimeout` 只执行一次，而 `setInterval` 会在每个时间间隔内重复执行。
- `setInterval` 的执行次数没有限制，直到被清除。
- 如果你希望在一段时间后执行某个操作，使用 `setTimeout`；如果你希望定期执行某个操作，使用 `setInterval`。

<br/>

### 项目中如何应用数据结构

公司：挖财

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/382)
在项目中，数据结构通常用于解决特定的问题或者优化特定的操作。以下是一些常见的项目中应用数据结构的场景：

#### 1. **搜索和排序算法：**
   - 数据结构如二叉搜索树、哈希表等可用于实现高效的搜索和排序算法，提高数据的检索速度。

#### 2. **缓存：**
   - 使用数据结构如哈希表或LRU（Least Recently Used）缓存策略，将频繁访问的数据存储在内存中，提高数据访问速度。

#### 3. **图算法：**
   - 图数据结构和相关算法用于解决网络分析、社交网络分析等问题。例如，查找两个用户之间的最短路径。

#### 4. **队列和栈：**
   - 队列和栈可用于任务调度、事件处理等。例如，使用队列管理异步任务的执行顺序，或者使用栈实现撤销/恢复功能。

#### 5. **树和图：**
   - 树和图数据结构常用于模拟组织结构、文件系统等。例如，使用树结构表示文件系统的层级关系。

#### 6. **并查集：**
   - 并查集是解决元素分组问题的数据结构，可用于社交网络中的好友关系分组。

#### 7. **堆：**
   - 堆可以用于优先级队列、任务调度等场景。例如，在任务调度系统中，使用堆来维护任务的执行顺序。

#### 8. **Trie 树：**
   - Trie 树常用于字符串搜索、自动完成等。例如，搜索引擎中的搜索建议功能。

#### 9. **哈希表：**
   - 哈希表常用于高效查找、插入和删除操作。例如，在数据库中使用哈希表来存储索引，提高查询速度。

#### 10. **链表：**
   - 链表可以用于实现队列、栈等数据结构。例如，使用链表实现 LRU 缓存策略。

<br/>

### 闭包的核心是什么

公司：寺库

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/378)
闭包的核心概念是函数与其周围状态（词法环境）的引用捆绑在一起。在JavaScript中，函数在被定义时就能记住其所在的词法环境，即使在定义的地方之外被调用，也能访问到它所在词法环境的变量。这种机制使得函数拥有记住和访问其外部作用域变量的能力，即便这些外部作用域在函数执行时已经不再存在。

闭包有两个主要的组成部分：
1. **函数（嵌套函数）：** 在另一个函数内部定义的函数。
2. **词法环境（Lexical Environment）：** 包含了在该函数被定义时可访问的所有局部变量、外部函数的参数，以及全局变量的引用。

当内部函数（嵌套函数）引用了外部函数的变量时，闭包就形成了。这个内部函数持有对外部函数局部变量的引用，即使外部函数已经执行完毕，这些变量依然存在于内部函数的词法环境中。这种引用机制保留了外部函数的状态，使得外部函数的局部变量在内部函数中依然可用。

闭包在JavaScript中有广泛的应用，例如用于模块化开发、私有变量的实现、异步编程中的回调函数，等等。

<br/>

### 写出代码输出结果

```js
var fullname = "Test1";
var obj = {
  fullname: "Test2",
  prop: {
    fullname: "Test3",
    getFullname: function () {
      return this.fullname;
    },
  },
};
console.log(obj.prop.getFullname());
var test = obj.prop.getFullname;
console.log(test());
```

公司：心娱、安居客

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/376)
在给定的代码中，`this.fullname` 的值取决于函数 `getFullname` 被调用的方式。如果它被作为对象的方法调用（作为 `obj.prop.getFullname()`），那么 `this` 指向 `obj.prop`，因此输出结果为 `"Test3"`。但是，当它被作为普通函数调用（`test()`），`this` 指向全局对象（在浏览器环境中通常是 `window` 对象），因此输出结果为 `"Test1"`。

所以，代码的输出结果是：

```
Test3
Test1
```

<br/>

### 实现一个功能，发送请求 5s 时间后，如果没有数据返回，中断请求,提示错误

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/375)
你可以使用 JavaScript 的 `fetch` 函数和 `setTimeout` 函数来实现这个功能。以下是一个示例代码：

```javascript
function fetchData() {
  return new Promise((resolve, reject) => {
    fetch('https://api.example.com/data')
      .then(response => {
        if (response.ok) {
          resolve(response.json());
        } else {
          reject('Error: ' + response.status);
        }
      })
      .catch(error => reject('Error: ' + error));
  });
}

let timeoutId = setTimeout(() => {
  console.log('Request timed out');
  clearTimeout(timeoutId); // 中断请求
}, 5000); // 5秒后中断请求

fetchData()
  .then(data => {
    clearTimeout(timeoutId); // 请求成功时清除定时器
    console.log('Data received:', data);
  })
  .catch(error => {
    clearTimeout(timeoutId); // 请求失败时清除定时器
    console.error(error);
  });
```

在这个示例中，`fetchData` 函数返回一个 Promise，该 Promise 在请求成功时解析为服务器返回的数据，失败时拒绝为一个错误信息。`setTimeout` 函数被用来设置一个 5 秒的定时器，如果在这段时间内请求没有完成，会触发中断请求并输出错误信息。如果请求成功，会在 `then` 中清除定时器，如果请求失败，会在 `catch` 中清除定时器。

<br/>

### 什么是作用域链

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/374)
作用域链是指在 JavaScript 中，每个函数都有一个与之相关联的作用域链，用于查找变量和函数的定义。当在一个函数中访问一个变量或调用一个函数时，JavaScript 引擎会按照作用域链的顺序从内向外查找，直到找到对应的变量或函数，或者抵达全局作用域（即全局对象，通常是 `window` 对象）为止。

作用域链的构建规则如下：

1. **每个函数都有自己的作用域链：** 当函数被创建时，它的作用域链中会包含当前函数的活动对象（包括参数、局部变量等）。

2. **函数嵌套时的作用域链：** 如果一个函数被嵌套在另一个函数内部，它的作用域链会包括它自身的活动对象以及包含它的外部函数的活动对象。

3. **词法作用域（Lexical Scope）：** JavaScript 中的作用域链是由代码中函数的嵌套关系静态决定的，而不是运行时动态决定的。这种静态作用域链的特性称为词法作用域。

例如，考虑以下代码：

```javascript
function outer() {
  var outerVar = "I am outer variable";

  function inner() {
    var innerVar = "I am inner variable";
    console.log(innerVar); // 访问内部函数的变量
    console.log(outerVar); // 访问外部函数的变量
  }

  return inner;
}

var innerFn = outer();
innerFn();
```

在这个例子中，`inner` 函数的作用域链包括自身的活动对象和外部函数 `outer` 的活动对象，因此它可以访问到 `outerVar` 和 `innerVar` 变量。当调用 `innerFn()` 时，它会按照作用域链的顺序找到这些变量并输出它们的值。

<br/>

### 介绍事件冒泡、事件代理、事件捕获，以及它们的关系

公司：腾讯应用宝、安居客

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/373)
在 JavaScript 中，事件冒泡（event bubbling）、事件捕获（event capturing）和事件代理（event delegation）是涉及到事件传播和处理的三个概念。

#### 1. **事件冒泡（Event Bubbling）：**
事件冒泡是指当一个事件被触发时，它会从事件的目标元素开始，然后逐级向上（冒泡）传播到文档根节点。这意味着如果你在子元素上触发了一个事件，它的父元素也会接收到这个事件。大多数事件都会冒泡，例如点击事件、鼠标事件等。

#### 2. **事件捕获（Event Capturing）：**
事件捕获与事件冒泡相反，它是指事件从文档根节点开始，逐级向下（捕获）传播到事件的目标元素。在事件捕获阶段，事件会最先被最顶层的元素（通常是文档根节点）捕获，然后逐级向下，直到事件的目标元素。

#### 3. **事件代理（Event Delegation）：**
事件代理是一种利用事件冒泡的机制，将事件处理器绑定到父元素而不是子元素的技术。当子元素触发事件时，事件会冒泡到父元素，然后可以通过判断事件的目标来执行相应的处理逻辑。事件代理的优势在于，当有大量的子元素需要绑定相同类型的事件时，可以将事件处理逻辑统一放在父元素上，减少事件处理器的数量，提高性能和代码的可维护性。

#### 关系和应用场景：
- **事件代理与事件冒泡关系：** 事件代理是基于事件冒泡机制的，通过事件冒泡，父元素可以捕获到子元素上触发的事件，从而实现事件代理。
- **事件捕获与事件代理关系：** 事件代理可以利用事件捕获阶段，在父元素上捕获到事件，然后根据事件的目标元素来执行相应的处理逻辑。
- **事件冒泡与事件捕获关系：** 事件冒泡和事件捕获是事件传播的两个阶段，它们可以用来捕获和处理事件。

事件代理通常在以下情况下被使用：
- 大量的子元素需要绑定相同类型的事件。
- 动态添加的元素需要绑定事件，而这些元素在事件绑定时可能还不存在于文档中。

利用事件代理，你可以将事件处理程序绑定到父元素，从而减少事件处理程序的数量，提高性能，同时也方便了对动态和未来新增元素的事件管理。

<br/>

### for..of 和 for...in 是否可以直接遍历对象，为什么

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/372)
`for...of` 和 `for...in` 是 JavaScript 中两种不同的循环语法，它们分别用于遍历可迭代对象（如数组、字符串、Map、Set 等）和遍历对象的属性。它们在遍历对象上的行为是不同的。

#### 1. **`for...of` 循环：**
`for...of` 语句用于遍历可迭代对象的元素。它可以遍历数组、字符串、Map、Set、类数组对象等可迭代对象。但是，`for...of` 不能直接用于普通对象（plain objects）的遍历。例如：

```javascript
const arr = [1, 2, 3];
for (const element of arr) {
  console.log(element); // 输出 1, 2, 3
}

const obj = { a: 1, b: 2, c: 3 };
for (const key of obj) {
  console.log(key); // TypeError: obj is not iterable
}
```

#### 2. **`for...in` 循环：**
`for...in` 语句用于遍历对象的可枚举属性（包括自身的属性和从原型链继承的属性）。它可以用于普通对象的遍历。但是，要注意 `for...in` 会遍历对象的所有可枚举属性，包括原型链上的属性，可能导致意外的属性被遍历。例如：

```javascript
const obj = { a: 1, b: 2, c: 3 };
for (const key in obj) {
  console.log(key); // 输出 a, b, c
}
```

总结来说，`for...of` 适用于遍历可迭代对象的元素，而 `for...in` 适用于遍历对象的属性。通常，如果你需要遍历对象的属性，推荐使用 `Object.keys()`, `Object.values()`, 或 `Object.entries()` 方法，它们会返回一个可迭代对象，可以用 `for...of` 进行遍历。如果需要遍历数组等可迭代对象的元素，使用 `for...of`。遍历普通对象的属性时，慎用 `for...in`，或者在使用时加上属性的检查，确保不会遍历到原型链上的属性。

<br/>

### 在 map 中和 for 中调用异步函数的区别

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/371)
在 JavaScript 中，当你在 `map` 中或 `for` 循环中调用异步函数时，你需要注意异步操作的执行顺序和作用域闭包的问题。

#### 1. **在 `map` 中调用异步函数：**
当你在 `map` 中调用异步函数时，异步函数是并行执行的，即它们会同时开始执行，不会等待前一个异步函数完成。这可能导致异步操作的执行顺序不同于你在代码中的调用顺序。例如：

```javascript
const array = [1, 2, 3];

const asyncFunction = async (item) => {
  return new Promise(resolve => {
    setTimeout(() => {
      console.log(item);
      resolve();
    }, 1000);
  });
};

const asyncOperations = array.map(item => asyncFunction(item));

// 异步函数是并行执行的，不会等待前一个完成
// 输出的顺序可能是 3, 2, 1，也可能是其他顺序
Promise.all(asyncOperations).then(() => {
  console.log('All operations completed');
});
```

在这个例子中，`map` 函数会同时调用三次 `asyncFunction`，并行执行，不会等待前一个异步函数完成。

#### 2. **在 `for` 循环中调用异步函数：**
与 `map` 不同，在 `for` 循环中调用异步函数时，每次循环会等待前一个异步操作完成，再进行下一次循环。这是因为 `for` 循环是同步的，它会按照顺序执行。例如：

```javascript
const array = [1, 2, 3];

const asyncFunction = async (item) => {
  return new Promise(resolve => {
    setTimeout(() => {
      console.log(item);
      resolve();
    }, 1000);
  });
};

async function processArray() {
  for (const item of array) {
    await asyncFunction(item);
  }
  console.log('All operations completed');
}

processArray();
```

在这个例子中，`for` 循环中的异步函数会按照顺序执行，输出的顺序是 1, 2, 3，然后输出 `'All operations completed'`。

总的来说，`map` 中的异步操作是并行执行的，而在 `for` 循环中的异步操作是按顺序执行的。

<br/>

### gennerator yield 的作用

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/370)
Generator 函数是 ECMAScript 6 引入的一种特殊类型的函数，它可以产生一个迭代器对象。在 Generator 函数内部，可以使用 `yield` 关键字来产生一个值，这个值会成为迭代器的返回值，同时，Generator 函数的执行会被暂停，直到下一次调用迭代器的 `next()` 方法。这使得 Generator 函数非常适合处理需要分阶段执行的任务，例如异步操作。

主要作用和特点如下：

#### 1. **暂停和恢复执行：**
Generator 函数中的 `yield` 语句可以暂停函数的执行，并返回一个值给调用者。每次调用 Generator 函数的 `next()` 方法时，函数会从上一次的 `yield` 语句处恢复执行，直到遇到下一个 `yield` 语句或函数结束。这种能够暂停和恢复执行的特性使得 Generator 函数在异步编程中非常实用。

#### 2. **异步编程：**
Generator 函数可以很方便地用于处理异步操作，例如在执行异步操作时暂停 Generator 函数的执行，待异步操作完成后，再通过调用 `next()` 方法恢复 Generator 函数的执行。

```javascript
function* asyncTask() {
  let result = yield fetch('https://api.example.com/data');
  console.log(result);
}

const task = asyncTask();
const promise = task.next().value;

promise.then(response => response.json())
  .then(data => task.next(data));
```

在这个例子中，`yield` 语句暂停了 Generator 函数的执行，等待异步操作（fetch 请求）完成。当异步操作完成后，通过调用 `next(data)` 恢复了 Generator 函数的执行。

#### 3. **生成无限序列：**
Generator 函数可以生成无限长度的序列，因为它可以在每次迭代中产生一个值，而不需要一开始就生成所有的值。这使得 Generator 函数在处理大量数据时非常高效。

```javascript
function* infiniteSequence() {
  let i = 0;
  while (true) {
    yield i++;
  }
}

const iterator = infiniteSequence();
console.log(iterator.next().value); // 输出 0
console.log(iterator.next().value); // 输出 1
console.log(iterator.next().value); // 输出 2
// ...
```

在这个例子中，`infiniteSequence` 是一个 Generator 函数，它可以生成无限递增的序列。

总的来说，Generator 函数的 `yield` 关键字允许你在函数内部产生多个值，并且每次产生一个值时可以暂停函数执行，然后在需要时恢复执行，使得异步编程更加清晰和易于理解。

<br/>

### promise 的状态有哪些

公司：微医

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/369)
Promise 的状态有三种：

1. **Pending（进行中）：** 初始状态，表示操作正在进行中，既不是成功（Fulfilled）也不是失败（Rejected）。

2. **Fulfilled（已成功）：** 表示操作成功完成，Promise 对象的状态从 Pending 变为 Fulfilled。当异步操作成功时，Promise 的状态变为 Fulfilled，并且会调用 `.then()` 方法绑定的回调函数。

3. **Rejected（已失败）：** 表示操作失败，Promise 对象的状态从 Pending 变为 Rejected。当异步操作失败时，Promise 的状态变为 Rejected，并且会调用 `.catch()` 方法绑定的错误处理函数或者 `.then(null, onRejected)` 来处理错误。

这三种状态是 Promise 的核心概念。在 Promise 对象的生命周期中，它从 Pending 状态开始，可以转移到 Fulfilled 或 Rejected 状态，一旦转移到了其中一种状态，就不可再改变。一旦状态发生改变，Promise 对象就进入了终态（settled），意味着它已经被解决了，可以安全地进行后续处理。

例如：

```javascript
const promise = new Promise((resolve, reject) => {
  // 异步操作成功
  resolve("Success"); // Promise 进入 Fulfilled 状态

  // 异步操作失败
  // reject("Error"); // Promise 进入 Rejected 状态
});

promise.then(
  result => {
    console.log("Fulfilled:", result);
  },
  error => {
    console.log("Rejected:", error);
  }
);
```

在上面的例子中，Promise 最终的状态由 `resolve` 和 `reject` 函数的调用决定。如果调用 `resolve("Success")`，Promise 进入 Fulfilled 状态，输出 `"Fulfilled: Success"`。如果调用 `reject("Error")`，Promise 进入 Rejected 状态，输出 `"Rejected: Error"`。

<br/>

### 在 ES6 中有哪些解决异步的方法

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/368)
在 ECMAScript 6（ES6）中，引入了一些新的语法和API来处理异步操作，使得异步编程更加方便和清晰。以下是ES6中主要用于解决异步操作的方法：

#### 1. **Promise：**
Promise 是 ES6 中引入的一种处理异步操作的对象。它可以表示一个异步操作的最终完成（或失败）以及其结果值。Promise 对象有三种状态（Pending、Fulfilled、Rejected），并且提供了 `.then()`、`.catch()`、`.finally()` 等方法，使得异步操作的处理更加简单和可读。

```javascript
const promise = new Promise((resolve, reject) => {
  // 异步操作成功
  resolve("Success");

  // 异步操作失败
  // reject("Error");
});

promise.then(
  result => {
    console.log("Fulfilled:", result);
  },
  error => {
    console.log("Rejected:", error);
  }
);
```

#### 2. **Async/Await：**
Async/Await 是 ES8（ES2017）引入的语法糖，基于 Promise 实现的，用于更方便地处理异步操作。通过 `async` 关键字定义的函数返回一个 Promise，可以使用 `await` 关键字在函数内部等待 Promise 的解决（resolve）或拒绝（reject）。

```javascript
async function fetchData() {
  try {
    let response = await fetch('https://api.example.com/data');
    let data = await response.json();
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

fetchData();
```

#### 3. **Generators（生成器）：**
Generator 函数是 ES6 中引入的一种特殊类型的函数，它可以被暂停和恢复执行，使得异步操作可以以同步的方式编写。通过 `yield` 关键字可以在 Generator 函数内部暂停执行，并通过迭代器的 `.next()` 方法恢复执行。

```javascript
function* fetchData() {
  try {
    let response = yield fetch('https://api.example.com/data');
    let data = yield response.json();
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

const generator = fetchData();
const promise = generator.next().value;

promise.then(response => generator.next(response).value)
       .then(data => generator.next(data));
```

<br/>

### es6 类继承中 super 的作用

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/367)
在 ES6 的类继承中，`super` 关键字有两个主要的作用：

#### 1. **调用父类构造函数（在子类的构造函数中使用）：**
在子类的构造函数中，`super()` 用于调用父类的构造函数，创建并初始化父类的实例。这是确保子类继承了父类的属性和方法的关键步骤。如果子类中使用了构造函数，它必须在 `constructor` 方法中的第一行使用 `super()`。

```javascript
class Parent {
  constructor(name) {
    this.name = name;
  }
}

class Child extends Parent {
  constructor(name, age) {
    super(name); // 调用父类构造函数，传入 name 参数
    this.age = age;
  }
}

const child = new Child('Alice', 10);
console.log(child.name); // 输出 "Alice"
console.log(child.age); // 输出 10
```

#### 2. **调用父类的方法（在子类的方法中使用）：**
`super` 也可以用于调用父类的方法。在子类的方法中，通过 `super.methodName()` 的方式可以调用父类的方法，这样子类就能够重写父类的方法，同时在子类的方法中使用父类的实现。

```javascript
class Parent {
  sayHello() {
    console.log('Hello from Parent class');
  }
}

class Child extends Parent {
  sayHello() {
    super.sayHello(); // 调用父类的 sayHello 方法
    console.log('Hello from Child class');
  }
}

const child = new Child();
child.sayHello();
// 输出：
// "Hello from Parent class"
// "Hello from Child class"
```

在上述例子中，`super.sayHello()` 调用了父类的 `sayHello` 方法，然后子类的 `sayHello` 方法添加了额外的输出。

总之，`super` 在子类中用于在构造函数中调用父类的构造函数并传递参数，以及在子类的方法中调用父类的同名方法。

<br/>

### cros 的简单请求和复杂请求的区别

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/366)
CORS（Cross-Origin Resource Sharing，跨源资源共享）是一种用于在浏览器和服务器之间进行跨源 HTTP 请求的机制。CORS 规定了在进行跨域请求时，服务器需要发送一些特定的 HTTP 头信息，告诉浏览器是否允许该请求。CORS 请求分为简单请求和复杂请求两种类型。

#### 简单请求（Simple Request）：

一个请求被认为是简单请求，需要同时满足以下条件：

1. 请求方法只能是 `GET`、`HEAD` 或 `POST`。
2. 请求头只能包含以下字段：`Accept`、`Accept-Language`、`Content-Language`、`Content-Type`（仅限于 `application/x-www-form-urlencoded`、`multipart/form-data` 和 `text/plain`）。
3. 请求中的任何 `XMLHttpRequest` 对象的 `Upload` 对象均没有注册任何事件监听器，也没有调用 `XMLHttpRequestUpload` 对象的任何属性或方法。
4. 请求中没有使用 ReadableStream 对象。

对于简单请求，浏览器会自动在请求头中添加 `Origin` 字段，服务器进行判断后可以决定是否允许该请求。

#### 复杂请求（Preflighted Request）：

一个请求被认为是复杂请求，需要满足以下条件中的任意一项：

1. 使用了非简单请求的方法，例如 `PUT`、`DELETE`。
2. 使用了自定义请求头，例如 `X-Requested-With`。
3. 请求中的 `Content-Type` 不属于以下三种类型：`application/x-www-form-urlencoded`、`multipart/form-data`、`text/plain`。

对于复杂请求，浏览器会首先发送一个预检请求（Preflight Request），使用 `OPTIONS` 方法，包含一个 `Access-Control-Request-Method` 头信息，询问服务器是否允许这个实际请求。只有在服务器返回允许的情况下，浏览器才会发送实际请求。

要使服务器支持跨域请求，需要在响应头中添加 `Access-Control-Allow-Origin` 字段，指定允许访问的源，以及其他一些 CORS 相关的头信息。

总结来说，简单请求满足一定的条件，浏览器会自动处理跨域请求。而复杂请求则需要在实际请求之前进行预检（Preflight），确保服务器允许该请求才会真正发送实际请求。

<br/>

### addEventListener 的第三个参数的作用

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/592)
`addEventListener` 方法用于向指定元素添加事件监听器。它的语法是：

```javascript
element.addEventListener(event, function, useCapture);
```

- `event`：表示事件的名称，比如 `"click"`、`"mouseover"` 等。
- `function`：表示要调用的函数，即事件触发时执行的回调函数。
- `useCapture`（可选参数）：一个布尔值，用于指定事件是在捕获阶段（true）还是冒泡阶段（false）执行，默认为 false。

当 `useCapture` 参数为 `true` 时，事件会在捕获阶段被处理；当为 `false` 或省略时，事件会在冒泡阶段被处理。

#### 捕获阶段和冒泡阶段：

- **捕获阶段（Capture Phase）：** 事件从根节点向目标节点传播的过程中，先进入捕获阶段，逐级往下传播直到达到事件的目标元素。捕获阶段的目的是为了预先处理事件，例如在外层元素上监听到事件并在事件冒泡到目标元素之前执行某些操作。

- **冒泡阶段（Bubbling Phase）：** 事件从目标节点开始，逐级向上冒泡，直到传播到根节点。冒泡阶段的目的是为了在事件到达目标元素后继续传播，从而允许在目标元素上监听并处理事件。

#### `useCapture` 的作用：

当 `useCapture` 参数为 `true` 时，事件监听器会在捕获阶段触发。这意味着事件会从根节点向目标节点传播，而事件监听器会在目标元素之前的父级元素上被触发。这通常用于在事件到达目标元素之前进行预处理，或者在事件到达目标元素之前拦截事件。

当 `useCapture` 参数为 `false`（默认值）时，事件监听器会在冒泡阶段触发，即事件从目标节点向根节点传播，事件监听器会在目标元素的父级元素上被触发。

使用 `useCapture` 参数可以更精确地控制事件的处理顺序，以及在事件到达目标元素之前或之后执行特定的操作。

<br/>

### 获取 id 为 netease 节点下所有的 checkbox 子元素(不用框架，注意兼容)

公司：网易

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/590)
你可以使用 `document.getElementById()` 方法获取 id 为 "netease" 的元素，然后使用 `querySelectorAll()` 方法来获取该元素下所有的 checkbox 子元素。以下是一个示例代码：

```javascript
// 获取 id 为 "netease" 的元素
var neteaseElement = document.getElementById("netease");

// 获取 neteaseElement 下所有的 checkbox 子元素
var checkboxes = neteaseElement.querySelectorAll("input[type='checkbox']");

// checkboxes 是一个 NodeList，可以遍历它来获取每个 checkbox 元素
checkboxes.forEach(function(checkbox) {
    console.log(checkbox); // 输出每个 checkbox 元素
});
```

在上面的代码中，`querySelectorAll("input[type='checkbox']")` 用于选择 neteaseElement 下所有类型为 checkbox 的子元素。然后通过 `forEach()` 方法遍历 NodeList，输出每个 checkbox 元素。

<br/>

### 使用原型链如何实现继承

公司：腾讯应用宝、安居客

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/589)
在 JavaScript 中，你可以使用原型链来实现继承。每个对象都有一个指向其原型（prototype）对象的内部链接，通过这个链接，一个对象可以访问另一个对象的属性和方法。通过修改原型链，你可以实现对象之间的继承关系。

以下是使用原型链实现继承的基本步骤：

1. **创建父类（基类）的构造函数：**
   ```javascript
   function Parent(name) {
     this.name = name;
   }
   ```

2. **在父类的原型上定义方法：**
   ```javascript
   Parent.prototype.sayHello = function() {
     console.log("Hello, " + this.name);
   };
   ```

3. **创建子类（派生类）的构造函数：**
   ```javascript
   function Child(name, age) {
     Parent.call(this, name); // 调用父类的构造函数，继承属性
     this.age = age;
   }
   ```

4. **将子类的原型指向父类的实例：**
   ```javascript
   Child.prototype = Object.create(Parent.prototype);
   Child.prototype.constructor = Child; // 修复构造函数的指向
   ```

在这个例子中，`Child.prototype` 指向一个新的对象，该对象的原型是 `Parent.prototype`，这样就建立了子类 `Child` 与父类 `Parent` 之间的原型链关系。这样，子类 `Child` 就能够继承父类 `Parent` 的属性和方法。

现在，你可以创建子类的实例，并调用继承自父类的方法：

```javascript
var childObj = new Child("Alice", 10);
childObj.sayHello(); // 输出 "Hello, Alice"
```

<br/>

### 如何获取一个对象的深度

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/588)
要获取一个对象的深度，你可以使用递归的方法遍历对象的属性。以下是一个实现的示例函数：

```javascript
function getObjectDepth(obj) {
    let maxDepth = 0;

    function calculateDepth(obj, depth) {
        for (let key in obj) {
            if (obj.hasOwnProperty(key) && typeof obj[key] === 'object') {
                maxDepth = Math.max(maxDepth, depth);
                calculateDepth(obj[key], depth + 1);
            }
        }
    }

    calculateDepth(obj, 1);
    return maxDepth;
}

// 示例对象
const exampleObject = {
    a: 1,
    b: {
        c: 2,
        d: {
            e: 3
        }
    }
};

const depth = getObjectDepth(exampleObject);
console.log("对象的深度为：" + depth);
```

在上面的代码中，`getObjectDepth` 函数接收一个对象作为参数。`calculateDepth` 函数是一个递归函数，用于遍历对象的属性，并计算对象的深度。递归过程中，每次递归深度加 1，直到遍历到最深层的属性。最后，`getObjectDepth` 返回计算出的最大深度。

在示例中，`exampleObject` 包含了三层深度的属性（`a`、`b`、`c`、`d`、`e`），因此输出结果为："对象的深度为：3"。

<br/>

### reduce 函数的功能，如何实现的，动手实现一下

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/587)
`reduce()` 是 JavaScript 中的数组方法，用于累加数组的各个元素，将数组缩减为单个值。它接受一个回调函数作为参数，该函数可以接受四个参数：累加器（accumulator）、当前元素（current element）、当前索引（current index）、原数组（source array）。回调函数返回的值将作为下一次调用回调函数时的累加器的值。`reduce()` 方法的语法如下：

```javascript
array.reduce(callback(accumulator, currentValue, currentIndex, array), initialValue)
```

- `accumulator`：累加器，初始值为 `initialValue`，或者是第一次调用时数组的第一个元素。
- `currentValue`：当前元素，遍历数组时的当前元素。
- `currentIndex`：当前元素的索引。
- `array`：原数组。

以下是一个实现累加数组元素的 `reduce()` 方法的例子：

```javascript
const numbers = [1, 2, 3, 4, 5];

// 使用 reduce 方法求和
const sum = numbers.reduce(function(accumulator, currentValue) {
    return accumulator + currentValue;
}, 0); // 初始值为 0

console.log(sum); // 输出 15，即数组元素的和
```

在上述例子中，`reduce()` 方法将数组 `numbers` 中的元素累加起来，初始值为 0。回调函数接受两个参数：`accumulator` 和 `currentValue`，分别代表累加器和当前元素。回调函数返回的结果将被作为下一次回调函数的 `accumulator` 参数。在这个例子中，初始值为 0，然后依次累加数组的元素，得到最终的和为 15。

如果你想手动实现一个 `reduce()` 函数，可以这样写：

```javascript
function customReduce(array, callback, initialValue) {
    let accumulator = initialValue !== undefined ? initialValue : array[0];
    let startIndex = initialValue !== undefined ? 0 : 1;

    for (let i = startIndex; i < array.length; i++) {
        accumulator = callback(accumulator, array[i], i, array);
    }

    return accumulator;
}

const numbers = [1, 2, 3, 4, 5];

const sum = customReduce(numbers, function(accumulator, currentValue) {
    return accumulator + currentValue;
}, 0);

console.log(sum); // 输出 15，即数组元素的和
```

<br/>

### 说一下 splice 和 slice 的功能用法

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/586)
`splice()` 和 `slice()` 是 JavaScript 中数组的两个方法，它们具有不同的功能和用法：

#### `splice()`

`splice()` 方法用于在数组中插入、删除或替换元素，并返回被删除的元素。它的语法如下：

```javascript
array.splice(start, deleteCount, item1, item2, ...);
```

- `start`：指定开始修改的位置的索引。
- `deleteCount`：要删除的元素数量。如果为 0，则不删除元素。
- `item1, item2, ...`：要插入到数组中的元素，从 `start` 索引位置开始插入。

##### 插入元素：

```javascript
let array = [1, 2, 3, 4, 5];
array.splice(2, 0, 6); // 在索引 2 处插入元素 6
console.log(array); // 输出 [1, 2, 6, 3, 4, 5]
```

##### 删除元素：

```javascript
let array = [1, 2, 3, 4, 5];
array.splice(2, 2); // 从索引 2 处开始删除 2 个元素
console.log(array); // 输出 [1, 2, 5]
```

##### 替换元素：

```javascript
let array = [1, 2, 3, 4, 5];
array.splice(2, 1, 6); // 从索引 2 处开始删除 1 个元素，并插入元素 6
console.log(array); // 输出 [1, 2, 6, 4, 5]
```

#### `slice()`

`slice()` 方法用于从数组中提取部分元素，创建一个新数组，并返回新数组。它的语法如下：

```javascript
array.slice(start, end);
```

- `start`：提取起始位置的索引（包含在内）。
- `end`：提取结束位置的索引（不包含在内）。如果省略 `end` 参数，`slice()` 会提取从 `start` 到数组末尾的所有元素。

##### 提取部分元素：

```javascript
let array = [1, 2, 3, 4, 5];
let newArray = array.slice(1, 4); // 提取索引 1 到 3（不包含 4）的元素
console.log(newArray); // 输出 [2, 3, 4]
```

##### 复制整个数组：

```javascript
let array = [1, 2, 3, 4, 5];
let newArray = array.slice(); // 复制整个数组
console.log(newArray); // 输出 [1, 2, 3, 4, 5]
```

总结来说，`splice()` 主要用于修改原数组（插入、删除、替换元素），而 `slice()` 用于创建新的数组，包含了原数组的部分或全部元素。

<br/>

### 面向对象的三要素是啥？都是啥意思？

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/585)
面向对象编程（Object-Oriented Programming，OOP）中的三个基本要素是：

1. **封装（Encapsulation）：** 封装是指将数据（属性）和操作数据的方法（行为）封装在一个单元内部，形成类（Class）。通过封装，对象的内部细节对外部是隐藏的，外部只能通过对象的公共接口（方法）来访问和操作对象的状态。封装提供了对象的抽象和数据隐藏，使得对象可以被看作是一个独立的实体，而不需要关心其内部实现细节。

2. **继承（Inheritance）：** 继承是指一个类（子类）可以继承另一个类（父类）的属性和方法。子类可以复用父类的属性和方法，并且可以在此基础上添加新的属性和方法，或者覆盖父类的方法。继承提供了代码的重用性和层次化的组织结构，允许在现有类的基础上定义新的类，使得类与类之间建立了关系，形成类的层次结构。

3. **多态（Polymorphism）：** 多态是指同一个接口（方法）可以有多种不同的实现方式。在面向对象编程中，多态通常表现为父类的引用变量可以引用子类的对象，通过父类的接口调用实际上是子类的实现。多态性提高了代码的灵活性和扩展性，使得代码可以适应不同的实际对象，而无需修改调用的代码。

这三个基本要素使得面向对象编程具有灵活性、可扩展性和易维护性，能够更好地描述现实世界中的事物和关系。

<br/>

### 函数中的 this 有几种

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/584)
在 JavaScript 中，`this` 关键字的值取决于函数的调用方式。以下是 `this` 的几种可能取值：

1. **全局作用域中的 `this`：** 当函数在全局作用域中被调用时，`this` 指向全局对象，在浏览器环境中通常是 `window` 对象。

   ```javascript
   function globalFunction() {
     console.log(this); // 指向全局对象（在浏览器环境中是 window）
   }
   globalFunction();
   ```

2. **对象方法中的 `this`：** 当函数作为对象的方法被调用时，`this` 指向调用该方法的对象。

   ```javascript
   const obj = {
     method: function() {
       console.log(this); // 指向 obj 对象
     }
   };
   obj.method();
   ```

3. **构造函数中的 `this`：** 当函数被用作构造函数（使用 `new` 关键字调用）时，`this` 指向新创建的对象。

   ```javascript
   function Constructor() {
     this.property = 'value';
     console.log(this); // 指向新创建的对象
   }
   const instance = new Constructor();
   ```

4. **事件处理函数中的 `this`：** 当函数作为事件处理函数被调用时，`this` 指向触发事件的 DOM 元素。

   ```html
   <button id="myButton">Click me!</button>
   <script>
     document.getElementById('myButton').addEventListener('click', function() {
       console.log(this); // 指向触发事件的按钮元素
     });
   </script>
   ```

5. **箭头函数中的 `this`：** 箭头函数没有自己的 `this`，它继承了外围作用域中的 `this`。

   ```javascript
   const arrowFunction = () => {
     console.log(this); // 指向定义时的外围作用域中的 this
   };
   arrowFunction();
   ```

需要注意的是，在箭头函数中，`this` 的值是在函数定义时确定的，而不是在函数调用时确定的。其他函数的 `this` 的值是在函数调用时根据调用方式动态确定的。

<br/>

### 如何同时获取 html 中的 h1,h2,h3,h4,h5,h6 中的内容

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/583)
你可以使用 JavaScript 中的 `querySelectorAll` 方法来选择 HTML 中的 `h1` 到 `h6` 元素，并遍历它们以获取其内容。以下是一个示例：

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Header Content</title>
</head>

<body>
    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>

    <script>
        // 获取所有 h1 到 h6 元素
        const headings = document.querySelectorAll('h1, h2, h3, h4, h5, h6');

        // 遍历元素并输出内容
        headings.forEach(function(heading) {
            console.log(heading.textContent);
        });
    </script>
</body>

</html>
```

在这个示例中，`querySelectorAll('h1, h2, h3, h4, h5, h6')` 选择了文档中所有的 `h1` 到 `h6` 元素，然后使用 `forEach` 方法遍历这些元素，打印它们的文本内容。

<br/>

### JavaScript 的执行流程

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/582)
JavaScript 的执行流程通常按照以下步骤进行：

1. **解析（Parsing）：** 首先，浏览器或 Node.js 解析 JavaScript 代码。在解析阶段，代码被转换成抽象语法树（AST），这是一个代表代码结构的树形数据结构。

2. **编译（Compilation）：** 解析后，代码被编译成字节码或机器码，具体取决于 JavaScript 引擎。编译后的代码在执行时更快，因为它不需要每次都被解析和编译。

3. **执行上下文创建（Execution Context Creation）：** 在代码执行之前，JavaScript 引擎会创建一个全局执行上下文（Global Execution Context）。每当函数被调用时，都会创建一个新的函数执行上下文。执行上下文包含了变量的环境信息、函数的参数、`this` 的值等。

4. **变量提升（Hoisting）：** 在执行上下文创建阶段，JavaScript 引擎会将变量和函数声明提升到当前作用域的顶部。这意味着你可以在声明之前访问这些变量和函数。

5. **代码执行：** JavaScript 引擎按照语句的顺序执行代码。在执行代码时，引擎会根据作用域链（Scope Chain）查找变量和函数的值。

6. **作用域链和闭包：** 当函数被嵌套定义时，内部函数可以访问外部函数的变量，这是因为 JavaScript 中的作用域链。如果内部函数引用了外部函数的变量，就形成了闭包。闭包可以在外部函数执行完成后仍然保持对外部函数作用域的引用，这样就可以访问外部函数的变量。

7. **事件循环（Event Loop）：** 在浏览器环境中，JavaScript 是单线程的，但是通过事件循环，可以处理异步操作，例如定时器、事件监听等。事件循环是 JavaScript 引擎处理异步任务的机制，它允许程序在等待异步操作完成的同时继续执行其他任务。

以上步骤构成了 JavaScript 代码的执行流程。这个流程使得 JavaScript 具有非阻塞的特性，可以处理大量的并发操作，例如处理用户输入、网络请求和定时器等。

<br/>

### Promise.resolve(obj)，obj 有几种可能

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/581)
`Promise.resolve(obj)` 方法返回一个解析后带有给定值的 Promise 对象。在传入不同类型的 `obj` 时，会有不同的处理方式：

1. **如果 `obj` 是一个 Promise 对象：** `Promise.resolve(obj)` 会直接返回 `obj`，不做任何修改。

   ```javascript
   const promise = new Promise((resolve) => {
     resolve("resolved");
   });

   const resolvedPromise = Promise.resolve(promise);
   console.log(resolvedPromise === promise); // 输出 true
   ```

2. **如果 `obj` 是一个 thenable 对象（具有 `.then` 方法的对象）：** `Promise.resolve(obj)` 会将这个对象转换为一个 Promise 对象，并且会执行 `obj` 的 `.then` 方法。

   ```javascript
   const thenable = {
     then(resolve) {
       resolve("resolved");
     }
   };

   const resolvedPromise = Promise.resolve(thenable);
   resolvedPromise.then((value) => {
     console.log(value); // 输出 "resolved"
   });
   ```

3. **如果 `obj` 是其他任意值：** `Promise.resolve(obj)` 会返回一个以 `obj` 为值被解析的 Promise 对象。

   ```javascript
   const value = "resolved";
   const resolvedPromise = Promise.resolve(value);
   resolvedPromise.then((result) => {
     console.log(result); // 输出 "resolved"
   });
   ```

总之，`Promise.resolve(obj)` 的行为会根据传入的 `obj` 的类型进行适当的处理，确保返回一个符合 Promise 规范的 Promise 对象。

<br/>

### 写出代码执行结果

```js
new Promise((resolve, reject) => {
  reject("1");
})
  .catch((e) => {
    console.log(1);
  })
  .then((res) => {
    console.log(2);
  });
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/580)
这段代码会输出:

```
1
2
```

解释：

1. `Promise` 构造函数中的 `reject` 方法会将 `Promise` 对象的状态设置为 `rejected`，并且传递的值为 `"1"`。

2. `.catch()` 方法用于捕获 `Promise` 对象的错误，并且返回一个新的 `Promise` 对象，该对象的状态是 `fulfilled`。在这个例子中，`.catch()` 方法捕获到了错误，因此会输出 `1`。

3. 然后，`.then()` 方法接收到上一个 `.catch()` 返回的 `Promise` 对象，此时该 `Promise` 对象的状态是 `fulfilled`，所以输出 `2`。

<br/>

### nextTick 是在本次循环执行，还是在下次，setTimeout(() => {}, 0)呢？

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/579)
在Node.js中，`process.nextTick`方法是在本次事件循环的末尾触发，它会在当前事件循环结束之后、下一个事件循环开始之前执行。这意味着，`process.nextTick`的回调函数会在当前事件循环的所有I/O操作完成之后、事件队列被清空之前被执行。

相比之下，`setTimeout(() => {}, 0)`会将回调函数放入事件队列，并在下一个事件循环中被执行。所以，`process.nextTick`比`setTimeout(() => {}, 0)`更早执行，因为它在本次事件循环末尾触发，而不需要等到下一次事件循环。

<br/>

### 使用正则去掉 Dom 中的内联样式

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/570)
你可以使用正则表达式结合JavaScript的replace方法来去掉DOM中的内联样式。以下是一个示例代码：

```javascript
// 获取包含内联样式的HTML字符串
const htmlString = '<div style="color: red;">This is a red text.</div>';

// 使用正则表达式去掉内联样式
const cleanHtmlString = htmlString.replace(/style="[^"]*"/g, '');

// 输出去掉内联样式的HTML字符串
console.log(cleanHtmlString);
```

在这个例子中，`/style="[^"]*"/g`是一个正则表达式，它匹配所有形式的内联样式。`replace()` 方法将匹配到的内联样式替换为空字符串，从而去掉了内联样式。

请注意，这种方法只适用于简单的内联样式，如果内联样式包含更复杂的结构（例如嵌套的引号），就需要更复杂的正则表达式或者更高级的解析方法。在处理复杂HTML结构时，更推荐使用DOM操作库（如jQuery）或者解析器（如DOMParser）来处理。

<br/>

### 写一个匹配 ip 地址的正则

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/569)
匹配IPv4地址的正则表达式通常如下：

```javascript
const ipv4Regex = /^(25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\.(
                   25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\.(
                   25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\.(
                   25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)$/;
```

这个正则表达式匹配IPv4地址，范围是`0.0.0.0`到`255.255.255.255`。

如果你需要匹配IPv6地址，正则表达式会更为复杂。IPv6地址的正则表达式通常如下：

```javascript
const ipv6Regex = /^([0-9a-fA-F]{1,4}:){7,7}[0-9a-fA-F]{1,4}$|^([0-9a-fA-F]{1,4}:){1,7}:$|^([0-9a-fA-F]{1,4}:){1,6}:[0-9a-fA-F]{1,4}$|^([0-9a-fA-F]{1,4}:){1,5}(:[0-9a-fA-F]{1,4}){1,2}$|^([0-9a-fA-F]{1,4}:){1,4}(:[0-9a-fA-F]{1,4}){1,3}$|^([0-9a-fA-F]{1,4}:){1,3}(:[0-9a-fA-F]{1,4}){1,4}$|^([0-9a-fA-F]{1,4}:){1,2}(:[0-9a-fA-F]{1,4}){1,5}$|^[0-9a-fA-F]{1,4}:((:[0-9a-fA-F]{1,4}){1,6})$/;
```

<br/>

### 写一个匹配 Html 标签的正则

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/568)
匹配HTML标签的正则表达式可以是相对简单的，用于匹配基本的开始和结束标签。以下是一个匹配HTML标签的基本正则表达式：

```javascript
const htmlTagsRegex = /<[^>]*>/g;
```

这个正则表达式可以匹配简单的HTML标签，例如`<div>`, `<span>`, `<p>`等。但请注意，这个正则表达式并不处理HTML的各种特殊情况，比如属性、嵌套标签等。

<br/>

### IOC 是啥，应用场景是啥？

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/563)
IOC（Inversion of Control，控制反转）是一种设计原则，它指的是将程序中对象的控制权从程序自身转移至外部容器或者框架，实现了程序的松耦合和可维护性。

在IOC中，对象的创建、组装和管理等工作不再由应用程序自己来完成，而是由外部容器来负责。这种控制的转移通常通过依赖注入（Dependency Injection）来实现。依赖注入是IOC的一种具体实现方式，它通过将依赖关系从类内部移出到类的外部，从而实现了对象之间的解耦。

应用场景：

1. **依赖注入（Dependency Injection）：** 依赖注入是IOC的一种具体实现方式。在依赖注入中，对象不再负责创建和管理它所依赖的对象，而是由外部容器来负责。这样做的好处是，对象之间的依赖关系变得松散，更容易进行单元测试，也更容易替换和升级组件。

2. **插件系统：** 在插件系统中，应用程序提供了一些插槽（接口），插件的实现可以通过IOC容器被动态加载和替换。这样，应用程序的功能可以根据需要进行扩展和定制，而不需要修改应用程序的源代码。

3. **AOP（Aspect-Oriented Programming）：** AOP是一种编程范式，它允许在不修改源代码的情况下，将横切关注点（例如日志、安全性、事务管理等）模块化。IOC容器可以用来管理和组装这些横切关注点，实现AOP。

4. **单元测试：** 在单元测试中，通过IOC容器可以注入模拟对象，使得测试更加容易，同时也避免了对真实对象的依赖。

<br/>

### 写出代码执行的打印结果

```js
function a(obj) {
  obj.a = 2;
  obj = { a: 3 };
  return obj;
}
const obj = { a: 1 };
a(obj);
console.log(obj);
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/561)
这段代码会输出：

```
{ a: 2 }
```

解释：

1. `obj` 是一个对象，传递给函数 `a(obj)`。

2. 在函数内部，`obj.a` 被修改为 `2`。

3. 然后，`obj` 被重新赋值为 `{ a: 3 }`，但这个重新赋值不影响外部传入的 `obj` 对象。这个赋值操作会改变函数内部 `obj` 变量的指向，但不会影响外部传入的对象。所以，函数内部的 `obj` 指向了一个新的对象 `{ a: 3 }`，但外部传入的 `obj` 仍然指向 `{ a: 2 }`。

4. 最后，`console.log(obj)` 打印的是函数外部的 `obj` 对象，它的属性 `a` 被函数内部修改为 `2`，所以输出 `{ a: 2 }`。

<br/>

### 实现函数

```js
d1,,,
d2,,,
d3,,,

把上边的字符串输出1，2，3的和 //6
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/560)
你可以使用正则表达式将字符串中的数字提取出来，并计算它们的和。以下是一个实现函数的例子：

```js
function calculateSum(input) {
  // 使用正则表达式匹配字符串中的数字
  const regex = /(\d+)/g;
  const matches = input.match(regex);

  // 计算数字的和
  if (matches) {
    const sum = matches.reduce((acc, num) => acc + parseInt(num, 10), 0);
    return sum;
  } else {
    return 0;
  }
}

const input = "d1,,,d2,,,d3,,,";
const sum = calculateSum(input);
console.log(sum); // 输出 6
```

在这个例子中，正则表达式 `(\d+)` 用来匹配字符串中的数字。`input.match(regex)` 返回一个包含所有匹配项的数组。然后，使用 `reduce` 函数将匹配到的数字相加，得到它们的和。

<br/>

### 怎么实现 this 对象的深拷贝

公司：阿里

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/539)
在 JavaScript 中，实现`this`对象的深拷贝（deep clone）可以通过递归方式来实现。以下是一个基本的深拷贝函数示例：

```javascript
function deepClone(obj) {
  if (obj === null || typeof obj !== "object") {
    return obj;
  }

  if (obj instanceof Date) {
    return new Date(obj);
  }

  if (obj instanceof RegExp) {
    return new RegExp(obj);
  }

  if (obj instanceof Array) {
    const newArray = [];
    for (let i = 0; i < obj.length; i++) {
      newArray[i] = deepClone(obj[i]);
    }
    return newArray;
  }

  const newObj = {};
  for (let key in obj) {
    if (obj.hasOwnProperty(key)) {
      newObj[key] = deepClone(obj[key]);
    }
  }

  return newObj;
}

// 示例用法
const originalObject = {
  a: 1,
  b: {
    c: 2,
    d: [3, 4],
  },
};

const clonedObject = deepClone(originalObject);
console.log(clonedObject);
```

在这个深拷贝函数中，它会递归地复制对象的属性。但请注意，这个简单的实现并不处理循环引用（对象属性相互引用的情况）。在实际应用中，可能需要考虑循环引用的情况并进行适当的处理。

此外，对于特殊类型的对象（如日期对象和正则表达式对象），需要单独处理以确保正确的复制。在示例中，我对日期对象和正则表达式对象进行了特殊处理。

<br/>

### 使用 canvas 绘图时如何组织成通用组件

公司：宝宝树

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/538)
在使用Canvas绘图时，可以将绘图逻辑封装为通用组件，使得代码更具可维护性和复用性。以下是一些组织Canvas绘图通用组件的方法：

#### 1. **面向对象的方式**

可以创建一个Canvas绘图类，封装Canvas绘图的方法，例如：

```javascript
class CanvasDrawer {
  constructor(canvas) {
    this.canvas = canvas;
    this.context = canvas.getContext('2d');
  }

  drawRect(x, y, width, height, color) {
    this.context.fillStyle = color;
    this.context.fillRect(x, y, width, height);
  }

  // 其他绘图方法...

  clearCanvas() {
    this.context.clearRect(0, 0, this.canvas.width, this.canvas.height);
  }
}

// 使用示例
const canvas = document.getElementById('myCanvas');
const drawer = new CanvasDrawer(canvas);
drawer.drawRect(10, 10, 50, 50, 'blue');
```

#### 2. **函数式组件**

可以创建一个函数，接受Canvas的上下文作为参数，封装绘图逻辑，返回一个绘图函数：

```javascript
function createCanvasDrawer(context) {
  return {
    drawRect(x, y, width, height, color) {
      context.fillStyle = color;
      context.fillRect(x, y, width, height);
    },

    // 其他绘图方法...
  };
}

// 使用示例
const canvas = document.getElementById('myCanvas');
const context = canvas.getContext('2d');
const drawer = createCanvasDrawer(context);
drawer.drawRect(10, 10, 50, 50, 'blue');
```

#### 3. **React 组件**

如果你正在使用React，可以创建一个Canvas组件，将Canvas绘图封装在该组件内部：

```javascript
import React, { useEffect, useRef } from 'react';

function CanvasComponent() {
  const canvasRef = useRef(null);

  useEffect(() => {
    const canvas = canvasRef.current;
    const context = canvas.getContext('2d');

    // 绘图逻辑...
    context.fillStyle = 'blue';
    context.fillRect(10, 10, 50, 50);
  }, []); // 空依赖数组确保只在组件挂载时执行一次

  return <canvas ref={canvasRef} width={500} height={500} />;
}
```

<br/>

### 表单可以跨域吗

公司：网易

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/537)
表单提交通常是通过浏览器进行的，而浏览器因为同源策略（Same-Origin Policy）的限制，对于不同源（域、协议、端口号有一个不同）的请求是受限的。

在传统的HTML表单中，如果表单的提交地址与当前页面的域相同，就不会存在跨域问题。例如，如果页面的地址是`http://example.com`，表单的提交地址是`http://example.com/submit`，那么是允许的。

但如果表单的提交地址与当前页面的域不同，就会涉及到跨域问题。这时，浏览器通常会阻止这种跨域请求，以保护用户的安全。如果你确实需要在不同域之间进行表单提交，可以考虑使用以下方法来解决跨域问题：

1. **JSONP（仅支持GET请求）：** 如果你可以控制服务器端，可以将表单提交改为JSONP方式。JSONP 是一种利用 `<script>` 标签可以跨域加载的特性来实现跨域请求的方法。

2. **CORS（Cross-Origin Resource Sharing）：** 如果你有权限修改服务器端的配置，可以在服务器端设置CORS头信息，允许特定域的请求访问资源。这样，浏览器就可以安全地实现跨域请求。

3. **代理（Proxy）：** 在同源策略下，前端可以向同域下的服务器发送请求，然后由服务器转发到目标地址。这样，前端就避免了直接跨域请求的问题。

4. **前端跨域方案：** 在一些特定情况下，前端也可以使用一些技术手段来实现跨域，例如使用JSONP、CORS库，或者使用后端服务器作为中间层进行请求转发。

<br/>

### 搜索请求如何处理？搜索请求中文如何请求？

公司：网易

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/536)
处理搜索请求通常涉及到向服务器发送查询参数，并接收服务器返回的搜索结果。在前端，你可以使用JavaScript发起搜索请求，通常使用AJAX（XMLHttpRequest 或 Fetch API）来实现。

如果搜索请求中包含中文字符，可以使用encodeURIComponent()函数对查询参数进行编码，确保特殊字符正确传递。示例代码如下：

```javascript
const searchTerm = "你好"; // 中文搜索词
const encodedSearchTerm = encodeURIComponent(searchTerm);

// 使用XMLHttpRequest发起GET请求
const xhr = new XMLHttpRequest();
xhr.open("GET", `http://example.com/search?q=${encodedSearchTerm}`, true);
xhr.onreadystatechange = function() {
  if (xhr.readyState === 4 && xhr.status === 200) {
    const response = xhr.responseText;
    // 处理搜索结果
    console.log(response);
  }
};
xhr.send();

// 使用Fetch API发起GET请求
fetch(`http://example.com/search?q=${encodedSearchTerm}`)
  .then(response => response.json()) // 或者 response.text()，根据返回的数据类型选择合适的解析方法
  .then(data => {
    // 处理搜索结果
    console.log(data);
  })
  .catch(error => {
    console.error(error);
  });
```

在这个示例中，`searchTerm` 包含中文字符 "你好"，使用`encodeURIComponent()` 对其进行编码，然后将编码后的字符串作为查询参数附加到搜索请求的URL中。

注意：服务器端也需要正确处理URL参数的解码。在大多数现代服务器端框架中，URL参数通常会被自动解码，因此你无需手动处理解码问题。

<br/>

### 介绍观察者模式

公司：网易、海风教育

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/535)
观察者模式（Observer Pattern）是一种行为设计模式，它定义了对象间一种一对多的依赖关系，当一个对象的状态发生改变时，所有依赖于它的对象都得到通知并被自动更新。在观察者模式中，有两个主要角色：

1. **主题（Subject）：** 主题是被观察的对象，它包含了一系列观察者，提供注册和移除观察者的方法，并在状态变化时通知观察者。
2. **观察者（Observer）：** 观察者是依赖于主题的对象，当主题状态发生变化时，观察者得到通知并执行相应的更新操作。

观察者模式的主要目的是解耦，使得主题和观察者之间的依赖关系变得松散，互相之间不需要知道彼此的具体实现。

以下是观察者模式的基本实现步骤：

1. **定义主题和观察者接口：**
   - 主题接口应该包含注册、移除和通知观察者的方法。
   - 观察者接口应该定义观察者需要执行的操作，通常包括一个更新方法。

   ```javascript
   // 主题接口
   class Subject {
     registerObserver(observer) {}
     removeObserver(observer) {}
     notifyObservers() {}
   }

   // 观察者接口
   class Observer {
     update(data) {}
   }
   ```

2. **实现具体的主题类：**
   - 具体的主题类实现主题接口，包括注册、移除和通知观察者的具体逻辑。

   ```javascript
   class ConcreteSubject extends Subject {
     constructor() {
       super();
       this.observers = [];
     }

     registerObserver(observer) {
       this.observers.push(observer);
     }

     removeObserver(observer) {
       const index = this.observers.indexOf(observer);
       if (index !== -1) {
         this.observers.splice(index, 1);
       }
     }

     notifyObservers(data) {
       for (const observer of this.observers) {
         observer.update(data);
       }
     }
   }
   ```

3. **实现具体的观察者类：**
   - 具体的观察者类实现观察者接口，定义观察者需要执行的具体操作。

   ```javascript
   class ConcreteObserver extends Observer {
     update(data) {
       console.log(`Received data: ${data}`);
     }
   }
   ```

4. **使用观察者模式：**
   - 创建主题对象和观察者对象，进行注册和通知操作。

   ```javascript
   const subject = new ConcreteSubject();
   const observer1 = new ConcreteObserver();
   const observer2 = new ConcreteObserver();

   subject.registerObserver(observer1);
   subject.registerObserver(observer2);

   subject.notifyObservers("New data has arrived!");
   ```

在这个例子中，`ConcreteSubject` 是具体的主题类，它继承了`Subject`接口，并实现了注册、移除和通知观察者的方法。`ConcreteObserver` 是具体的观察者类，它继承了`Observer`接口，并实现了`update`方法，用于接收并处理主题通知的数据。

观察者模式在实现事件处理、UI组件更新、消息传递等场景中广泛应用，它帮助实现了对象间的松耦合，提高了系统的可扩展性和复用性。

<br/>

### 介绍中介者模式

公司：网易

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/534)
中介者模式（Mediator Pattern）是一种行为设计模式，它允许对象之间不直接相互交互，而是通过一个中介者对象进行间接交互。中介者模式促使了对象之间的解耦，使得对象更加独立，易于维护和扩展。在中介者模式中，对象之间不再持有彼此的引用，而是通过中介者进行通信。

以下是中介者模式的主要角色：

1. **中介者（Mediator）：** 中介者是一个接口或抽象类，定义了对象之间交互的通信规则。具体的中介者对象实现了中介者接口，负责协调并处理对象之间的通信。

2. **具体中介者（Concrete Mediator）：** 具体中介者是实现了中介者接口的具体对象，它通常包含了所有参与通信的对象的引用，并负责协调它们的交互。

3. **同事对象（Colleague）：** 同事对象是指参与中介者模式的对象，它们通过中介者进行通信。同事对象知道中介者对象，并将自身的变化通知给中介者，由中介者来处理进一步的交互。

中介者模式通常应用于以下场景：

- 当一组对象之间的通信复杂，导致彼此之间相互依赖，难以维护和扩展时，可以使用中介者模式来简化对象之间的交互。
- 当一个对象的改变需要同时影响其他对象时，可以使用中介者模式，将这些对象的交互逻辑集中到中介者中，避免了彼此之间的直接关联。

以下是一个简单的中介者模式示例：

```javascript
// 中介者接口
class Mediator {
  sendMessage(message, colleague) {}
}

// 具体中介者
class ConcreteMediator extends Mediator {
  constructor(colleague1, colleague2) {
    super();
    this.colleague1 = colleague1;
    this.colleague2 = colleague2;
  }

  sendMessage(message, colleague) {
    if (colleague === this.colleague1) {
      this.colleague2.receiveMessage(message);
    } else {
      this.colleague1.receiveMessage(message);
    }
  }
}

// 同事对象
class Colleague {
  constructor(mediator) {
    this.mediator = mediator;
  }

  sendMessage(message) {
    this.mediator.sendMessage(message, this);
  }

  receiveMessage(message) {
    console.log(`Received message: ${message}`);
  }
}

// 使用中介者模式
const mediator = new ConcreteMediator();
const colleague1 = new Colleague(mediator);
const colleague2 = new Colleague(mediator);

colleague1.sendMessage("Hello from colleague1!"); // 输出：Received message: Hello from colleague1!
colleague2.sendMessage("Hi from colleague2!");     // 输出：Received message: Hi from colleague2!
```

在这个例子中，`ConcreteMediator` 是具体的中介者，负责协调`Colleague`对象之间的通信。`Colleague`对象可以通过`sendMessage`方法发送消息，并且由中介者负责将消息传递给其他的`Colleague`对象。这样，`Colleague`对象之间的通信就通过中介者实现，而不需要直接相互关联。

<br/>

### 观察者和订阅-发布的区别，各自用在哪里

公司：网易、有赞、微医

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/533)
观察者模式和订阅-发布模式（也称为事件模型或消息模型）都是用于处理对象间的通信和事件处理的模式，它们之间的主要区别在于实现方式和命名习惯。以下是它们的区别和使用场景：

#### 观察者模式：

1. **实现方式：**
   - 观察者模式通常包含主题（Subject）和观察者（Observer）两个角色。
   - 主题对象维护一个观察者列表，当主题的状态发生变化时，通知所有的观察者。
   - 观察者对象通过注册到主题上来接收通知，当主题状态变化时，观察者的相应方法会被调用。

2. **命名习惯：**
   - 在观察者模式中，通常使用 `addObserver()`、`removeObserver()` 和 `notifyObservers()` 等方法名来实现观察者的注册、移除和通知。

3. **使用场景：**
   - 观察者模式适用于一个对象的状态改变需要通知其他多个对象的场景，例如事件处理、UI组件更新等。
   - 典型应用包括 JavaScript 中的 DOM 事件处理、自定义事件等。

#### 订阅-发布模式：

1. **实现方式：**
   - 订阅-发布模式通过一个事件通道（Event Channel）来实现。
   - 发布者（Publisher）负责发布事件，订阅者（Subscriber）通过订阅事件来接收通知。

2. **命名习惯：**
   - 在订阅-发布模式中，通常使用 `subscribe()`、`unsubscribe()` 和 `publish()` 等方法名来实现订阅、取消订阅和事件发布。

3. **使用场景：**
   - 订阅-发布模式适用于松散耦合的组件间通信场景，各个组件之间不需要直接关联，而是通过事件来进行通信。
   - 典型应用包括 JavaScript 中的自定义事件、消息系统等。

##### 总结：

- 观察者模式更注重观察者和主题的关系，观察者明确知道主题，而主题也知道观察者。
- 订阅-发布模式更注重事件的发布和订阅，发布者不需要知道订阅者的存在，只需发布事件，订阅者可以选择性地订阅事件。
- 观察者模式通常用于对象间的一对多通信，而订阅-发布模式通常用于解耦松散的组件间通信。选择使用哪种模式取决于具体的需求和设计架构。

<br/>

### 通过什么做到并发请求

公司：网易

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/532)
在前端开发中，实现并发请求通常使用以下几种方法：

1. **Promise 和 Promise.all：** 使用Promise对象可以轻松实现异步操作的并发执行。Promise.all() 方法可以接受一个由 Promise 对象组成的数组，并在所有的 Promise 对象都成功时，返回一个新的 Promise 对象。

   ```javascript
   let promise1 = fetch('url1');
   let promise2 = fetch('url2');
   
   Promise.all([promise1, promise2])
     .then(responses => {
       // 处理 responses[0] 和 responses[1]
     })
     .catch(error => {
       // 处理错误
     });
   ```

2. **async/await：** 使用 async/await 语法糖，可以编写看起来同步的异步代码。await 关键字可以等待 Promise 对象的解决，并将解决后的值返回。

   ```javascript
   async function fetchData() {
     let data1 = await fetch('url1');
     let data2 = await fetch('url2');
     // 处理 data1 和 data2
   }
   
   fetchData().catch(error => {
     // 处理错误
   });
   ```

3. **XMLHttpRequest：** 使用原生的 XMLHttpRequest 对象可以发送多个并发请求。通过创建多个 XMLHttpRequest 对象，可以并发地发送多个请求，然后在回调函数中处理返回的数据。

   ```javascript
   let xhr1 = new XMLHttpRequest();
   let xhr2 = new XMLHttpRequest();
   
   xhr1.open('GET', 'url1', true);
   xhr2.open('GET', 'url2', true);
   
   xhr1.onreadystatechange = function () {
     if (xhr1.readyState === 4 && xhr1.status === 200) {
       // 处理 xhr1.responseText
     }
   };
   
   xhr2.onreadystatechange = function () {
     if (xhr2.readyState === 4 && xhr2.status === 200) {
       // 处理 xhr2.responseText
     }
   };
   
   xhr1.send();
   xhr2.send();
   ```

4. **Fetch API：** 使用 Fetch API 也可以实现并发请求。Fetch API 提供了一种更现代、灵活的方式来处理网络请求。

   ```javascript
   let promise1 = fetch('url1');
   let promise2 = fetch('url2');
   
   Promise.all([promise1, promise2])
     .then(responses => {
       return Promise.all(responses.map(response => response.json()));
     })
     .then(dataArray => {
       // 处理 dataArray[0] 和 dataArray[1]
     })
     .catch(error => {
       // 处理错误
     });
   ```

<br/>

### 介绍 service worker

公司：网易

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/530)
Service Worker 是一种在浏览器背后运行的脚本，它独立于网页，可以用来实现一些在网页关闭后仍然可以执行的任务，例如推送通知、离线缓存、拦截和处理网络请求等。

Service Worker 的主要特性和用途包括：

1. **后台运行：** Service Worker 可以在浏览器后台运行，独立于网页，即使用户关闭了网页，Service Worker 仍然可以继续执行。

2. **网络代理：** Service Worker 可以拦截并处理发出的网络请求。这使得我们可以实现自定义的缓存策略、离线访问、或者动态地从不同来源获取资源。

3. **离线缓存：** Service Worker 可以缓存网页资源，使得用户在离线状态下仍然能够访问应用。这种能力被广泛用于构建离线应用（Progressive Web Apps）。

4. **推送通知：** Service Worker 可以接收服务器端推送的通知消息，并显示给用户。这样，网站可以向用户发送实时的消息，即使用户没有打开网页。

5. **安全性：** Service Worker 运行在 HTTPS 环境中，这样保证了安全性，防止了中间人攻击。

使用 Service Worker 的步骤通常包括：

1. **注册 Service Worker：** 在网页中注册一个 Service Worker 脚本，通常在页面的 JavaScript 文件中完成。注册后，Service Worker 开始在后台运行。

   ```javascript
   if ('serviceWorker' in navigator) {
     navigator.serviceWorker.register('/service-worker.js')
       .then(registration => {
         console.log('Service Worker registered with scope:', registration.scope);
       })
       .catch(error => {
         console.error('Service Worker registration failed:', error);
       });
   }
   ```

2. **Service Worker 脚本：** 在注册时指定的 Service Worker 脚本，通常称为 `service-worker.js`，包含了具体的逻辑，例如拦截请求、处理缓存等。

   ```javascript
   self.addEventListener('fetch', event => {
     // 拦截并处理请求
     event.respondWith(
       caches.match(event.request)
         .then(response => {
           return response || fetch(event.request);
         })
     );
   });
   ```

3. **安装、激活和更新：** Service Worker 在注册后需要安装、激活和更新。这些操作通常在 `service-worker.js` 中进行定义。

   ```javascript
   self.addEventListener('install', event => {
     // 安装阶段，可以缓存资源
   });

   self.addEventListener('activate', event => {
     // 激活阶段，可以清理旧的缓存
   });

   self.addEventListener('fetch', event => {
     // 拦截并处理请求
   });
   ```

总的来说，Service Worker 提供了一个强大的工具，使得 web 应用能够更加智能、快速和具有更好的用户体验。但是，使用 Service Worker 也需要谨慎，因为它可以对网络请求和用户隐私产生影响。

<br/>

### 介绍事件代理以及优缺点，主要解决什么问题

公司：网易、沪江

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/526)
事件代理（Event Delegation）是一种设计模式，通过将事件监听器绑定到一个父元素上，来管理所有子元素的事件。当子元素上的事件被触发时，事件会冒泡到父元素，父元素上的事件监听器会捕获这个事件并执行相应的处理逻辑。

#### 事件代理的优点：

1. **性能优化：** 减少事件监听器的数量，特别是在大量子元素上使用事件代理可以减少内存占用和提高性能。因为只需一个事件监听器，而不是为每个子元素都绑定一个事件监听器。

2. **动态元素处理：** 对于动态添加的子元素，无需重新绑定事件，因为事件监听器是在父元素上，新添加的子元素也会被代理。

3. **代码简洁：** 减少了大量的事件绑定代码，使代码结构更加清晰和简洁。

#### 事件代理的缺点：

1. **事件委托不适合所有事件：** 对于一些需要立即响应的事件（例如鼠标移动事件），事件委托并不适用。因为事件冒泡到父元素需要时间，可能无法满足即时响应的需求。

2. **事件对象的 target 受影响：** 使用事件代理时，事件对象的 `event.target` 属性可能会指向不同的元素，需要在处理事件时进行判断。

#### 主要解决的问题：

1. **动态事件处理：** 在需要动态添加或删除元素的场景下，事件代理可以确保新添加的元素也能够被正确处理。

2. **提高性能：** 当页面上有大量的元素需要绑定事件时，使用事件代理可以减少事件处理函数的数量，提高页面性能。

3. **简化代码：** 使用事件代理可以减少重复的事件绑定代码，使代码更加简洁和易于维护。

综上所述，事件代理是一种高效、灵活且简化代码的事件处理方式，特别适合处理大量动态元素的事件。但是在一些需要即时响应的事件场景中，需要谨慎选择是否使用事件代理。

<br/>

### 介绍下 this 的各种情况

公司：网易、蘑菇街

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/524)
在 JavaScript 中，`this` 关键字的指向在不同的上下文中会有不同的值。`this` 的指向通常取决于函数的调用方式。以下是几种常见的情况：

1. **全局上下文中：** 在全局上下文中，`this` 指向全局对象（在浏览器环境中通常是 `window` 对象）。

   ```javascript
   console.log(this); // 在浏览器中输出 window 对象
   ```

2. **函数内部：** 在普通函数内部，`this` 指向全局对象（在非严格模式下）或者是 `undefined`（在严格模式下）。

   ```javascript
   function exampleFunction() {
     console.log(this);
   }
   
   exampleFunction(); // 在浏览器中输出 window 对象（在非严格模式下）
   ```

3. **对象方法中：** 当函数作为对象的方法被调用时，`this` 指向调用该函数的对象。

   ```javascript
   const obj = {
     name: "example",
     logName: function() {
       console.log(this.name);
     }
   };
   
   obj.logName(); // 输出 "example"
   ```

4. **构造函数中：** 当函数被用作构造函数（使用 `new` 关键字）时，`this` 指向新创建的对象实例。

   ```javascript
   function Person(name) {
     this.name = name;
   }
   
   const person = new Person("John");
   console.log(person.name); // 输出 "John"
   ```

5. **事件处理函数中：** 在事件处理函数中，`this` 通常指向触发事件的元素。

   ```html
   <button id="myButton">Click me</button>
   <script>
     const button = document.getElementById("myButton");
     button.addEventListener("click", function() {
       console.log(this); // 指向触发事件的 button 元素
     });
   </script>
   ```

6. **箭头函数中：** 箭头函数没有自己的 `this`，它会捕获其所在上下文的 `this` 值。

   ```javascript
   function exampleFunction() {
     return () => {
       console.log(this);
     };
   }
   
   const obj = { name: "example" };
   const arrowFunction = exampleFunction.call(obj);
   arrowFunction(); // 输出 obj 对象
   ```

在实际开发中，理解函数调用的上下文非常重要，因为它决定了 `this` 的值。需要根据不同的场景来正确使用 `this`，以避免出现意外的行为。

<br/>

### 前端如何控制管理路由

公司：网易

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/523)
在前端开发中，路由（Route）用于控制用户在应用中的页面跳转和导航。在单页面应用（SPA）中，前端通常通过前端路由来实现页面切换，而不是像传统的多页面应用（MPA）那样由服务器端处理。

前端管理路由的主要方法包括：

1. **使用 History API：** HTML5 提供了 History API，它允许前端应用在不刷新页面的情况下改变浏览器的历史记录，从而实现前端路由。常见的方法有 `pushState()` 和 `replaceState()`。

   ```javascript
   window.history.pushState(state, title, url);
   ```

   例如，Vue Router 和 React Router 等前端框架都是基于 History API 实现的。

2. **前端路由库：** 前端框架和库通常提供了自己的路由管理机制。例如，React 应用通常使用 React Router，Vue 应用使用 Vue Router。这些库提供了高级的路由功能，例如嵌套路由、路由守卫、动态路由等。

   ```javascript
   // React Router 的例子
   import { BrowserRouter as Router, Route } from 'react-router-dom';
   
   ReactDOM.render(
     <Router>
       <Route path="/home" component={Home} />
       <Route path="/about" component={About} />
     </Router>,
     document.getElementById('root')
   );
   ```

3. **手动实现路由：** 如果不想依赖于路由库，也可以手动实现简单的路由系统。通过监听 `popstate` 事件，可以在 URL 发生变化时执行相应的操作。

   ```javascript
   window.addEventListener('popstate', function(event) {
     // 处理 URL 变化
   });
   ```

   这种方法通常用于小型项目或学习目的，对于大型项目来说，推荐使用成熟的前端路由库。

<br/>

### 使用路由时出现问题如何解决

公司：网易

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/522)
当在使用路由时遇到问题时，可以按照以下步骤逐步排查和解决问题：

1. **查看错误信息：** 首先，查看浏览器控制台（Console）中是否有报错信息或警告。错误信息通常会提供有用的线索，帮助你定位问题。

2. **检查路由配置：** 检查路由配置是否正确。确保路由的路径、组件和其他配置项都正确设置。比较常见的问题包括拼写错误、路径配置不匹配等。

3. **检查路由组件：** 如果使用的是路由库（如React Router、Vue Router等），确保路由组件（Route Components）正确导入和使用。组件是否正确渲染、接收到了正确的参数等。

4. **处理异步加载组件问题：** 如果使用了懒加载（Lazy Loading）或异步组件加载方式，请确保懒加载组件的路径和引入方式正确。在使用 import() 进行懒加载时，路径是否正确以及是否返回了正确的 Promise 对象。

5. **查看路由历史记录：** 在浏览器中查看路由历史记录，确保路由的跳转和路径变化符合预期。可以使用浏览器的前进、后退按钮，或者手动输入URL来测试。

6. **检查路由守卫（Route Guards）：** 如果使用了路由守卫，确保守卫函数中的逻辑正确。守卫函数返回 true 或 false 决定是否允许进入或离开某个路由。

7. **检查路由参数和查询参数：** 如果使用了路由参数（Route Parameters）或查询参数（Query Parameters），确保组件能够正确获取和处理这些参数。

8. **清空浏览器缓存：** 有时候，浏览器缓存可能导致路由页面不更新。尝试清除浏览器缓存，或者使用无缓存模式（通常是按下 Ctrl + F5 刷新）。

9. **查阅文档和社区：** 如果以上方法都无法解决问题，查阅相关路由库的官方文档和社区。可能有其他开发者遇到过类似的问题，并提供了解决方法。

10. **使用调试工具：** 如果仍然无法解决，可以使用浏览器的开发者工具进行调试。例如，在 Chrome DevTools 的 Network 标签下，可以查看路由请求的响应和状态。

<br/>

### JavaScript 异步解决方案的发展历程以及优缺点

公司：滴滴、挖财、宝宝树、海康威视

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/515)
JavaScript 异步编程一直是前端开发中的重要话题，随着技术的发展，出现了多种异步解决方案。以下是这些方案的发展历程以及各自的优缺点：

#### 1. **回调函数（Callback）**

- **发展历程：** 最早的异步解决方案就是使用回调函数。通过将函数作为参数传递给异步函数，当异步操作完成时，调用传入的回调函数。
  
- **优点：** 简单，容易理解。
  
- **缺点：** 回调地狱（Callback Hell）：多层嵌套的回调函数难以维护，不易读写，容易造成代码混乱。

#### 2. **Promise**

- **发展历程：** Promise 是一种更为可控和易于组织的异步解决方案，引入了 `resolve` 和 `reject` 的概念，使得异步操作更为清晰。Promise 通过 `.then()` 方法链式调用，解决了回调地狱问题。

- **优点：** 可读性好，结构清晰，可以很好地处理多个异步操作。

- **缺点：** 无法取消 Promise，一旦创建就会立即执行，无法中途加入新的回调函数。

#### 3. **Generator 函数**

- **发展历程：** Generator 函数是 ES6 引入的新特性，它可以通过 `yield` 暂停函数执行，实现异步操作。配合协程（Coroutine）可以实现同步的写法处理异步逻辑。

- **优点：** 可以像同步代码一样写异步逻辑，提供了更好的可读性和可维护性。

- **缺点：** 需要额外的控制流程，较为复杂，需要使用第三方库（如 co.js）来简化使用。

#### 4. **Async/Await**

- **发展历程：** Async/Await 是 ES2017 的标准，它基于 Promise，并提供了更直观的语法，使得异步编程看起来像同步代码一样。使用 `async` 声明异步函数，`await` 暂停异步函数的执行，等待 Promise 解析。

- **优点：** 语法清晰，易读易写，结构简单，可以处理多个异步操作，可以捕获异常。

- **缺点：** 不可以在普通函数中使用，需要包裹在异步函数中。在语法上相对于 Promise 略微复杂。

#### 总结

随着 JavaScript 的发展，异步解决方案也在不断演进。在现代前端开发中，Async/Await 成为了主流的异步编程方式，因为它提供了清晰、简洁、可读性强的语法，避免了回调地狱的问题。但在特定场景下，其他解决方案仍然有它们的用武之地。

<br/>

### 介绍 AST（Abstract Syntax Tree）抽象语法树

公司：滴滴

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/530)
**抽象语法树（Abstract Syntax Tree，简称 AST）** 是在编译器设计和代码分析中非常重要的一种数据结构。它是源代码的抽象语法结构的树状表现形式，用树来表示编程语言的语法结构。

在AST中，每个节点表示源代码中的一个语法结构，例如变量、函数、表达式等。这些节点通过树的形式彼此连接，形成了整个程序的语法结构。AST可以被用来进行代码的分析、转换、优化等操作。

在JavaScript中，AST通常被用于静态代码分析、代码转换、代码压缩和代码格式化等领域。开发者可以使用各种工具和库（如Babel、Esprima等）将源代码解析成AST，然后基于AST进行各种操作。

一个简单的JavaScript函数：

```javascript
function square(num) {
  return num * num;
}
```

对应的AST结构可能如下：

```
Program
  └─ FunctionDeclaration (name: square)
      ├─ Identifier (name: num)
      └─ BlockStatement
          └─ ReturnStatement
              └─ BinaryExpression (operator: *)
                  ├─ Identifier (name: num)
                  └─ Identifier (name: num)
```

在AST中，`Program` 是根节点，表示整个程序。`FunctionDeclaration` 表示函数声明，包含函数的名字（`square`）和参数（`num`），`BlockStatement` 表示函数体的块语句，`ReturnStatement` 表示返回语句，`BinaryExpression` 表示乘法表达式。

通过分析和操作AST，开发者可以实现自定义的代码转换、静态分析等需求。 AST在前端工程化中起到了非常重要的作用，尤其是在构建工具、编译器和代码编辑器中。

<br/>

### 对 async、await 的理解，内部原理是怎样的？

公司：头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/499)
`async` 和 `await` 是 ES2017（也称为ES8）引入的两个关键字，用于简化 JavaScript 中的异步编程。它们的作用是使异步代码看起来和同步代码类似，更容易理解和维护。

#### 对 `async` 的理解：

1. **异步函数声明：** `async` 用于声明一个异步函数，使得该函数内部可以使用 `await`。
2. **返回 Promise：** 异步函数始终返回一个 Promise 对象，不论函数内部是使用 `return` 还是 `throw`。

#### 对 `await` 的理解：

1. **等待 Promise 解决：** `await` 只能在异步函数中使用，用于等待一个 Promise 对象解决，并返回 Promise 结果。
2. **暂停函数执行：** 在遇到 `await` 时，函数执行会暂停，直到 Promise 解决，然后将解决的值作为 `await` 表达式的结果。

#### `async/await` 内部原理：

1. **Generator 函数：** `async` 函数内部实际上是一个 Generator 函数。当遇到 `await` 关键字时，Generator 函数会暂停执行，等待 Promise 解决。Generator 函数内部使用的是生成器迭代器的执行机制。
  
2. **Promise 封装：** 异步函数返回的是一个 Promise 对象。当函数内部返回值是一个原始值（非 Promise），JavaScript 会自动将其封装成一个已解决的 Promise。
  
3. **错误处理：** `async/await` 内部自动处理了异步操作中的错误。可以使用 `try/catch` 块来捕获异步函数中的异常，就像同步代码一样。

下面是一个简单的例子：

```javascript
async function fetchData() {
  try {
    let response = await fetch('https://api.example.com/data');
    let data = await response.json();
    console.log(data);
  } catch (error) {
    console.error('Error:', error);
  }
}
```

在这个例子中，`fetchData` 函数是异步函数，内部使用了 `await` 关键字等待 `fetch` 函数返回的 Promise 解决。如果 Promise 解决，则将数据解析为 JSON。如果发生错误，`catch` 块会捕获异常。

内部实现中，JavaScript 引擎会将 `async/await` 转换为类似 Generator 函数的形式，使用 Promise 和 Generator 结合的方式实现异步操作的暂停和恢复。这使得开发者在处理异步操作时，能够编写出更具可读性和易维护性的代码。

<br/>

### == 和 ===的区别，什么情况下用相等==

公司：头条、安居客

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/496)
`==` 和 `===` 是 JavaScript 中用于比较两个值的运算符，它们之间的主要区别在于比较的严格性。

1. **`==`（相等运算符）：** 用于比较两个值是否相等，但不检查它们的数据类型。在使用 `==` 进行比较时，JavaScript 会自动进行类型转换，尝试使两个值具有相同的数据类型，然后再进行比较。

   示例：`'5' == 5` 会返回 `true`，因为 JavaScript 将字符串 `'5'` 转换为数字 `5`，然后进行比较。

   使用 `==` 的情况：
   - 当需要松散比较，不考虑数据类型，只关心值是否相等时，可以使用 `==`。
   - 在某些情况下，当比较的值具有不同的数据类型，但可以被认为是相等的，例如 `null` 和 `undefined`。

2. **`===`（严格相等运算符）：** 用于比较两个值是否严格相等，包括值和数据类型都必须相同。

   示例：`'5' === 5` 会返回 `false`，因为它们的数据类型不同。

   使用 `===` 的情况：
   - 推荐在大多数情况下使用 `===`，因为它更具严格性，避免了意外的类型转换。
   - 当需要确保比较的值不仅值相等，而且数据类型也相同时，应使用 `===`。
   - 在编写严谨的代码时，使用 `===` 有助于避免潜在的错误和意外的行为。

总之，`===` 是更为严格和可预测的比较方式，推荐在大多数情况下使用，特别是在编写高质量的、不易出错的代码时。而 `==` 在某些特定情况下可能会更方便，但需要谨慎使用，避免不必要的类型转换引起的问题。

<br/>

### bind、call、apply 的区别

公司：头条、挖财、饿了么、心娱

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/495)
`bind`、`call` 和 `apply` 是 JavaScript 中用于改变函数执行上下文（即 `this` 指向）的方法，它们之间的区别主要体现在参数传递和函数执行时机上。

#### 1. **`bind` 方法：**

`bind` 方法创建一个新的函数，当这个新函数被调用时，它的 `this` 值会被指定为传递给 `bind` 的第一个参数，不会立即执行函数，而是返回一个绑定了指定 `this` 值的新函数。

```javascript
const obj = { value: 42 };

function getValue() {
  console.log(this.value);
}

const boundGetValue = getValue.bind(obj);
boundGetValue(); // 输出 42
```

#### 2. **`call` 方法：**

`call` 方法调用一个函数，将一个对象绑定为函数的 `this` 值，并立即执行该函数。额外的参数会作为函数的参数传递进去。

```javascript
const obj = { value: 42 };

function getValue(prefix) {
  console.log(prefix + this.value);
}

getValue.call(obj, 'Value is: '); // 输出 "Value is: 42"
```

#### 3. **`apply` 方法：**

`apply` 方法与 `call` 类似，也是调用一个函数，将一个对象绑定为函数的 `this` 值，但参数以数组形式传递。

```javascript
const obj = { value: 42 };

function getValue(prefix, suffix) {
  console.log(prefix + this.value + suffix);
}

getValue.apply(obj, ['Value is: ', '!']); // 输出 "Value is: 42!"
```

#### 主要区别总结：

- **参数传递：**
  - `bind` 方法允许你传递参数并返回一个函数，该函数可以稍后被调用。
  - `call` 和 `apply` 方法立即调用函数，允许你传递参数列表。
- **返回值：**
  - `bind` 返回一个新函数，不会立即执行。
  - `call` 和 `apply` 立即执行函数。
- **使用场景：**
  - 使用 `bind` 当你想在稍后的时间点调用函数，并保持特定的 `this` 值。
  - 使用 `call` 和 `apply` 当你想立即调用函数，并传递特定的 `this` 值和参数。

<br/>

### 介绍下原型链

公司：头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/494)
JavaScript 中的原型链是一种对象间继承关系的机制，它允许一个对象继承另一个对象的属性和方法。在 JavaScript 中，几乎所有的对象都是从另一个对象继承而来的，这种继承关系是通过原型链来实现的。

#### 基本概念：

1. **每个对象都有一个原型（prototype）：** 对象的原型是一个指向另一个对象的引用，它定义了该对象的属性和方法。
   
2. **构造函数和实例对象：** 在 JavaScript 中，可以使用构造函数创建对象。构造函数是一个普通的 JavaScript 函数，通过 `new` 关键字调用构造函数时，会创建一个新的对象实例，并将该对象的原型指向构造函数的 `prototype` 属性。

#### 原型链的形成：

1. **每个函数都是一个对象：** 在 JavaScript 中，函数也是对象，每个函数都有一个 `prototype` 属性，该属性指向一个对象。这个对象就是该函数的原型。

2. **实例对象的原型：** 当使用构造函数创建对象实例时，该实例对象的原型指向构造函数的 `prototype` 对象。

3. **原型的继承：** 如果一个对象在其原型链上找不到某个属性或方法，它会沿着原型链向上查找，直到找到为止。这样的机制就是原型链的基本原理。

#### 示例：

```javascript
function Animal(name) {
  this.name = name;
}

// Animal 的原型上有一个 eat 方法
Animal.prototype.eat = function() {
  console.log(this.name + ' is eating.');
};

function Dog(name, breed) {
  Animal.call(this, name); // 调用 Animal 构造函数，继承属性
  this.breed = breed;
}

// 设置 Dog 的原型为 Animal 的实例，建立原型链
Dog.prototype = Object.create(Animal.prototype);
Dog.prototype.constructor = Dog; // 修复构造函数指向

const dog1 = new Dog('Buddy', 'Golden Retriever');
dog1.eat(); // 输出 "Buddy is eating."
```

在这个例子中，`Dog` 构造函数继承了 `Animal` 构造函数的属性和方法。`Dog.prototype` 对象是 `Animal.prototype` 对象的一个实例，形成了原型链。通过原型链，`dog1` 实例对象可以访问 `Animal` 构造函数的 `eat` 方法。

原型链使得 JavaScript 中的对象可以共享属性和方法，提高了代码的重用性和可维护性。

<br/>

### 介绍暂时性死区

公司：有赞

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/488)
暂时性死区（Temporal Dead Zone，简称 TDZ）是指在代码块中，使用 `let` 和 `const` 声明的变量，在声明语句之前无法被访问。这意味着在变量声明语句之前的区域，如果尝试访问这些变量，就会抛出错误。这种行为是为了在代码中更早地发现潜在的错误，增加代码的可靠性。

让我们来看一个示例来理解暂时性死区：

```javascript
console.log(a); // ReferenceError: Cannot access 'a' before initialization
let a = 10;
```

在上面的例子中，`console.log(a)` 的语句在 `a` 变量的声明语句之前，但由于 `a` 是用 `let` 声明的，它在声明之前无法被访问，所以会抛出 `ReferenceError` 错误。这就是暂时性死区的概念。

暂时性死区主要应用于 `let` 和 `const` 声明的变量，它们在声明语句执行之前不可被访问。相比之下，使用 `var` 声明的变量不具备暂时性死区，它们在声明之前可以被访问，但值为 `undefined`。这种行为是 JavaScript 引擎设计上的差异，`let` 和 `const` 的引入增加了代码的可靠性，避免了一些潜在的错误。

<br/>

### ES6 中的 map 和原生的对象有什么区别

公司：有赞

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/487)
ES6 中的 `Map` 和原生的 JavaScript 对象之间有几个主要区别：

1. **键的类型：**
   - `Map` 的键可以是任意数据类型，包括基本数据类型（如字符串、数字）和对象、函数等引用类型。
   - JavaScript 对象的键必须是字符串或 Symbol 类型。

2. **键值对数量：**
   - `Map` 的大小可以通过 `size` 属性获取，它可以存储任意数量的键值对。
   - JavaScript 对象没有直接提供获取键值对数量的方法，但可以通过手动迭代属性来计算。

3. **键值对的顺序：**
   - `Map` 会按照键值对插入的顺序保持顺序。
   - JavaScript 对象的属性在规范之前是没有顺序保证的，但现代 JavaScript 引擎实现了属性的插入顺序。

4. **迭代：**
   - `Map` 对象提供了内置的迭代方法，比如 `forEach`、`keys`、`values` 和 `entries`，能够更方便地遍历键值对。
   - JavaScript 对象的遍历通常需要通过 `for...in` 循环或 `Object.keys`、`Object.values` 等方法，相对来说稍显繁琐。

5. **内存占用：**
   - `Map` 对象的内存占用通常比普通对象稍多，因为它需要存储额外的信息来维护键值对的顺序。
   - JavaScript 对象在某些引擎中可能会有一些内部优化，对于包含少量键值对的对象，内存占用可能会比 `Map` 小。

选择使用 `Map` 还是普通对象取决于具体的需求。如果需要存储任意数据类型的键和值，并且需要维持插入顺序，或者需要频繁地进行键值对的增删改查操作，那么使用 `Map` 是一个好的选择。如果只需要字符串或 Symbol 类型作为键，并且不需要保持插入顺序，那么普通对象可能更加简洁和高效。

<br/>

### 对纯函数的理解

公司：有赞

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/483)
纯函数是指在函数的执行过程中，不依赖于程序执行期间外部状态（外部状态包括但不限于全局变量、数据库、文件系统等），也不会改变外部状态。纯函数具有以下两个主要特点：

1. **相同的输入始终产生相同的输出：** 纯函数的输出结果只由输入参数决定，相同的输入参数将始终产生相同的输出。这意味着函数的执行不受外部环境的影响，只依赖于输入。

2. **没有副作用：** 纯函数不会产生副作用，即它不会改变外部状态或引起其他不可控制的行为。例如，纯函数不会修改全局变量、不会修改传入的参数，也不会产生 I/O 操作。

#### 优势和特点：

- **可测试性：** 由于纯函数的输出完全由输入决定，所以很容易进行单元测试。给定相同的输入，纯函数的输出是确定的，因此可以方便地编写测试用例。

- **可缓存性：** 纯函数的结果可以被缓存，因为相同的输入总是产生相同的输出。这种特性在函数式编程中常用于优化，避免重复计算。

- **可组合性：** 纯函数可以方便地组合成更复杂的函数，因为它们不依赖于外部状态，所以可以将它们无限制地组合在一起。

- **可追溯性：** 纯函数的输出结果可以追溯到输入，这种属性使得代码更容易理解和调试。

- **并行执行：** 由于纯函数没有副作用，可以放心地并行执行，提高程序的性能。

<br/>

### 介绍 JSX

公司：有赞

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/482)
JSX（JavaScript XML）是一种在JavaScript中嵌入XML（或类XML）语法的语法扩展。它通常与React一起使用，用于描述React元素的结构。

JSX 的主要特点包括：

1. **语法糖：** JSX 提供了一种更加直观和易读的语法，允许开发者在JavaScript代码中嵌入HTML结构，使得构建UI更加直观和自然。

   ```jsx
   const element = <h1>Hello, JSX!</h1>;
   ```

2. **表达式插入：** 在 JSX 中，可以使用大括号 `{}` 插入JavaScript表达式。这使得你可以在 JSX 中动态地渲染数据。

   ```jsx
   const name = "World";
   const element = <h1>Hello, {name}!</h1>;
   ```

3. **组件：** JSX 可以用来表示React组件。你可以用标签语法表示自定义组件。

   ```jsx
   function Welcome(props) {
     return <h1>Hello, {props.name}</h1>;
   }

   const element = <Welcome name="World" />;
   ```

4. **属性：** 在 JSX 中，你可以使用属性来设置元素的特性，就像在HTML中一样。

   ```jsx
   const element = <div className="container">Hello, JSX!</div>;
   ```

5. **嵌套：** JSX 元素可以嵌套。

   ```jsx
   const element = (
     <div>
       <h1>Hello, JSX!</h1>
       <p>This is a paragraph.</p>
     </div>
   );
   ```

6. **防止注入攻击：** JSX 可以帮助防止注入攻击，因为它默认会转义任何嵌入其中的值。

   ```jsx
   const userInput = '<script>alert("XSS Attack!");</script>';
   const element = <p>{userInput}</p>;
   // 最终渲染出的HTML： <p>&lt;script&gt;alert("XSS Attack!");&lt;/script&gt;</p>
   ```

需要注意的是，JSX 本身并不是React的一部分。它是一种由Babel等工具编译时转换为JavaScript的语法。在使用React时，通常需要一个构建工具（比如Webpack）来将JSX转换为可执行的JavaScript代码。

<br/>

### 如何设计一个 localStorage，保证数据的时效性

公司：有赞

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/477)
设计一个带有时效性的本地存储（例如类似于`localStorage`的功能），你可以使用以下策略：

1. **加入时间戳（TTL）：** 将数据存储为一个对象，包括实际数据和时间戳。在每次访问数据时，检查当前时间和数据的时间戳，如果数据超过一定时效性（比如30分钟），则认为数据已过期，不再返回给应用。

   ```javascript
   const storedData = {
     data: { /* your actual data */ },
     timestamp: new Date().getTime() // 当前时间戳
   };

   // 在读取数据时，检查时间戳
   function getDataFromStorage() {
     if (storedData.timestamp + 30 * 60 * 1000 < new Date().getTime()) {
       // 数据已过期，返回 null 或者执行重新获取数据的操作
       return null;
     }
     return storedData.data;
   }
   ```

2. **定期清理：** 定期检查存储中的数据，并清理掉已过期的数据。

   ```javascript
   function clearExpiredData() {
     // 遍历存储中的数据，清理过期数据
   }

   // 定时执行清理操作
   setInterval(clearExpiredData, 24 * 60 * 60 * 1000); // 每天执行一次清理
   ```

3. **封装方法：** 将存储和读取数据的逻辑封装成方法，确保每次存取数据都经过时间戳检查，避免重复的代码。

   ```javascript
   function setData(key, data) {
     localStorage.setItem(key, JSON.stringify({ data, timestamp: new Date().getTime() }));
   }

   function getData(key) {
     const storedData = JSON.parse(localStorage.getItem(key));
     if (!storedData || storedData.timestamp + 30 * 60 * 1000 < new Date().getTime()) {
       // 数据不存在或已过期，返回 null 或者执行重新获取数据的操作
       return null;
     }
     return storedData.data;
   }
   ```

<br/>

### 实现 sum 方法，使 sum(x)(y),sum(x,y)返回的结果相同

公司：有赞、网易、乘法云

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/475)
要实现 `sum` 方法，使得 `sum(x)(y)` 和 `sum(x, y)` 返回相同的结果，你可以返回一个函数，并在返回的函数中处理参数的情况。以下是一个示例实现：

```javascript
function sum(x) {
  if (arguments.length === 2) {
    return x + arguments[1];
  } else {
    return function(y) {
      return x + y;
    };
  }
}

console.log(sum(2)(3)); // 输出 5
console.log(sum(2, 3)); // 输出 5
```

在这个实现中，`sum` 函数接受一个参数 `x`，如果传入两个参数，直接返回它们的和。如果只传入一个参数 `x`，则返回一个新的函数，这个新函数接受一个参数 `y`，返回 `x + y` 的结果。这样，无论是 `sum(x)(y)` 还是 `sum(x, y)` 都能返回相同的结果。

<br/>

### 两个对象如何比较

公司：有赞

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/474)
在JavaScript中，当你想要比较两个对象时，有两种常见的方法：浅比较和深比较。

#### 1. 浅比较

浅比较是比较两个对象的引用是否相同，即它们是否指向内存中的相同位置。你可以使用 `===` 运算符来进行浅比较。

```javascript
const obj1 = { name: 'Alice' };
const obj2 = { name: 'Alice' };

console.log(obj1 === obj2); // 输出 false，因为它们是两个不同的对象
```

在上面的例子中，`obj1` 和 `obj2` 是两个不同的对象，所以它们的引用不相同，`obj1 === obj2` 返回 `false`。

#### 2. 深比较

深比较是逐级比较两个对象的属性是否相同，如果它们的所有属性都相同，那么这两个对象就被认为是相等的。深比较通常需要使用递归函数或者一些库来实现。

以下是一个简单的递归深比较函数的例子：

```javascript
function deepEqual(obj1, obj2) {
  if (obj1 === obj2) {
    return true;
  }

  if (typeof obj1 !== 'object' || obj1 === null || typeof obj2 !== 'object' || obj2 === null) {
    return false;
  }

  const keys1 = Object.keys(obj1);
  const keys2 = Object.keys(obj2);

  if (keys1.length !== keys2.length) {
    return false;
  }

  for (let key of keys1) {
    if (!keys2.includes(key) || !deepEqual(obj1[key], obj2[key])) {
      return false;
    }
  }

  return true;
}

const obj1 = { name: 'Alice', age: 30 };
const obj2 = { name: 'Alice', age: 30 };

console.log(deepEqual(obj1, obj2)); // 输出 true，因为它们的属性相同
```

在上面的例子中，`deepEqual` 函数会递归地比较两个对象的属性是否相同，如果相同则返回 `true`，否则返回 `false`。这样，你可以通过 `deepEqual(obj1, obj2)` 来深比较两个对象。

<br/>

### 说一下变量的作用域链

公司：挖财

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/473)
JavaScript中的变量作用域链（Scope Chain）是指在函数嵌套的情况下，内部函数（包括局部变量、参数和函数声明）可以访问外部函数的变量和参数，甚至可以访问全局作用域的变量。这种机制形成了作用域链。

当代码在一个作用域中查找变量或函数时，如果在当前作用域没有找到，它会继续向上级作用域查找，直到找到该变量或函数，或者抵达全局作用域。这个查找的过程形成了一个链式结构，被称为作用域链。

让我们通过一个示例来理解作用域链：

```javascript
function outerFunction() {
  const outerVar = "I am from outer function";

  function innerFunction() {
    const innerVar = "I am from inner function";
    console.log(innerVar); // 输出 "I am from inner function"
    console.log(outerVar); // 输出 "I am from outer function"
    console.log(globalVar); // 输出 "I am a global variable"
  }

  innerFunction();
}

const globalVar = "I am a global variable";
outerFunction();
```

在这个例子中，`innerFunction` 内部可以访问到 `outerVar` 和 `globalVar`，这是因为在函数 `innerFunction` 的作用域链中包含了外部函数 `outerFunction` 的作用域和全局作用域。当 `innerFunction` 查找变量时，它首先在自身的作用域中查找，然后在外部函数的作用域中查找，最后在全局作用域中查找。

这种作用域链的机制使得函数能够访问外部作用域中的变量，但是外部作用域不能访问内部作用域的变量。这种封闭性和作用域链的概念是JavaScript闭包（Closures）的基础。

<br/>

### 介绍 dom 树对比

公司：挖财

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/472)
DOM树对比（DOM Diffing）是前端性能优化中的一个重要概念。当页面发生变化时（比如用户交互或者数据更新），为了避免重新渲染整个页面，前端框架通常会采用虚拟DOM和DOM Diffing技术来高效更新DOM。

#### 1. 虚拟DOM

虚拟DOM是一个轻量级的内存中的表示真实DOM结构的JavaScript对象。框架（比如React）在更新之前会先生成一个虚拟DOM树，然后将这个虚拟DOM与上一次渲染的虚拟DOM进行比较，找出变化的部分，最后再更新实际的DOM。这样可以减少直接操作DOM带来的性能开销。

#### 2. DOM Diffing

DOM Diffing是指比较两棵虚拟DOM树的差异，然后只更新必要的部分，而不是重新渲染整个页面。在DOM Diffing过程中，通常采用了一些策略来尽量减少比较的次数，以提高性能。这些策略包括：

- **策略1：同层比较**
  - 只比较相同层级的节点，不跨级比较。
- **策略2：节点类型相同就更新**
  - 如果两个节点的类型相同（比如都是`<div>`），则比较它们的属性，如果属性相同则认为无需更新，否则更新属性。
- **策略3：快速定位**
  - 在列表中查找相同类型的节点时，使用唯一标识（比如`key`属性）来加速查找，避免遍历整个列表。
- **策略4：批量更新**
  - 将所有变更集中处理，而不是一次性更新一个节点。

以上这些策略和算法可以减少比较和更新的次数，提高了DOM Diffing的效率，使得前端框架能够更高效地响应用户的交互和数据变化，从而提升了用户体验。

<br/>

### 如何设计状态树

公司：挖财

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/471)
设计状态树通常指的是前端应用中使用的状态管理模式，常见的状态管理库如Redux和Vuex等。以下是设计状态树的一般步骤：

#### 1. 定义状态

首先，明确定义应用中的状态。状态是应用数据的集合，包括用户信息、页面状态、API返回的数据等。将所有状态整理为一个对象，这个对象就是状态树的根。

```javascript
const initialState = {
  user: null,
  todos: [],
  // 其他状态属性...
};
```

#### 2. 定义操作（Actions）

Actions是描述状态变化的纯对象，每个Action通常包含一个`type`字段（表示动作类型）和payload字段（携带的数据）。Actions用来描述用户的交互、API请求等行为。

```javascript
const ActionTypes = {
  SET_USER: 'SET_USER',
  ADD_TODO: 'ADD_TODO',
  // 其他动作类型...
};

const setUser = (user) => ({
  type: ActionTypes.SET_USER,
  payload: user,
});

const addTodo = (todo) => ({
  type: ActionTypes.ADD_TODO,
  payload: todo,
});
```

#### 3. 定义Reducer函数

Reducer是一个纯函数，接收当前的状态和一个Action，根据Action的type来返回新的状态。Reducer负责处理状态的变化逻辑。

```javascript
const reducer = (state = initialState, action) => {
  switch (action.type) {
    case ActionTypes.SET_USER:
      return { ...state, user: action.payload };
    case ActionTypes.ADD_TODO:
      return { ...state, todos: [...state.todos, action.payload] };
    default:
      return state;
  }
};
```

#### 4. 创建Store

Store是状态的容器，包含了当前状态树、Reducer和一些操作方法（dispatch、subscribe等）。使用Reducer创建一个Store。

```javascript
import { createStore } from 'redux';

const store = createStore(reducer);
```

#### 5. 派发Action

通过`store.dispatch(action)`来派发Action，触发Reducer的执行，从而改变状态。

```javascript
store.dispatch(setUser({ id: 1, name: 'Alice' }));
store.dispatch(addTodo({ id: 1, text: 'Learn Redux' }));
```

<br/>

### Ajax 发生跨域要设置什么（前端）

公司：沪江

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/462)
在前端进行Ajax跨域请求时，需要注意跨域资源共享（CORS）和JSONP是两种常用的解决方法。以下是关于CORS的设置：

#### 跨域资源共享（CORS）

##### 1. 服务器端设置

在服务器端的响应头中添加`Access-Control-Allow-Origin`字段，用于指定允许访问的域名，可以是具体的域名或者`*`表示允许任意域名访问。

示例（Node.js Express框架）：

```javascript
const express = require('express');
const app = express();

// 允许所有域名访问
app.use((req, res, next) => {
  res.header('Access-Control-Allow-Origin', '*');
  // 其他CORS相关设置...
  next();
});

// 其他路由和业务逻辑...
```

##### 2. 前端设置

在前端的Ajax请求中，不需要特殊设置，只需正常发起Ajax请求即可。

```javascript
const xhr = new XMLHttpRequest();
xhr.open('GET', 'http://example.com/api/data', true);
xhr.onreadystatechange = function () {
  if (xhr.readyState === 4 && xhr.status === 200) {
    console.log(xhr.responseText);
  }
};
xhr.send();
```

需要注意的是，如果请求中包含自定义的请求头，例如`Content-Type`为`application/json`，则服务器端的响应头也需要包含`Access-Control-Allow-Headers`字段，指定允许的自定义请求头。

```javascript
// 服务器端设置允许自定义请求头
res.header('Access-Control-Allow-Headers', 'Content-Type');
```

<br/>

### 加上 CORS 之后从发起到请求正式成功的过程

公司：沪江

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/461)
当使用CORS（跨域资源共享）解决Ajax跨域请求时，从发起请求到请求正式成功的过程如下：

1. **前端发起请求：** 在前端代码中，通过XMLHttpRequest或Fetch API等方式发起跨域请求。

   ```javascript
   const xhr = new XMLHttpRequest();
   xhr.open('GET', 'http://example.com/api/data', true);
   xhr.onreadystatechange = function () {
     if (xhr.readyState === 4 && xhr.status === 200) {
       console.log(xhr.responseText);
     }
   };
   xhr.send();
   ```

2. **浏览器发送OPTIONS预检请求（Preflight Request）：** 浏览器在正式发送跨域请求之前，会发送一个OPTIONS方法的预检请求到服务器，询问服务器是否允许实际请求（GET、POST等）。

3. **服务器返回CORS响应头：** 服务器接收到预检请求后，会根据请求中的Origin字段（发起请求的源）判断是否允许该源进行跨域访问。如果允许，服务器会在响应头中添加`Access-Control-Allow-Origin`字段，指定允许的源。例如：

   ```
   Access-Control-Allow-Origin: http://example.com
   ```

   如果允许任意域名访问，可以设置为：

   ```
   Access-Control-Allow-Origin: *
   ```

   除了`Access-Control-Allow-Origin`，服务器还可以添加其他相关的CORS响应头，例如允许的请求方法、允许的自定义请求头等。

4. **浏览器发送实际请求：** 如果服务器返回了允许跨域访问的响应头，浏览器会发送实际的跨域请求（GET、POST等）。

5. **服务器处理请求：** 服务器接收到实际请求，处理请求并返回数据。

6. **浏览器接收响应：** 浏览器接收到服务器的响应，根据状态码和数据处理响应结果。

以上是使用CORS解决Ajax跨域请求的完整过程。需要注意，CORS并不适用于所有场景，例如在移动应用开发中，跨域请求可能需要使用其他解决方案，比如JSONP或者使用代理服务器。

<br/>

### Async 里面有多个 await 请求，可以怎么优化

公司：沪江

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/460)
在异步函数（async function）中有多个await请求时，你可以选择并行执行这些请求，以提高性能。可以使用`Promise.all()`或者`Promise.allSettled()`方法，它们都可以处理多个Promise并发执行的场景。这两种方法的主要区别在于对于某个Promise被rejected的处理。

#### 1. 使用`Promise.all()`

`Promise.all()`方法接收一个Promise数组，当所有的Promise都成功（resolved）时，返回一个包含所有Promise结果的数组；当有一个Promise被rejected时，返回的Promise会立即被reject。

```javascript
async function fetchData() {
  try {
    const [data1, data2, data3] = await Promise.all([
      fetchData1(),
      fetchData2(),
      fetchData3(),
    ]);
    // 所有请求成功，继续处理数据
    // ...
  } catch (error) {
    // 处理错误
    console.error(error);
  }
}
```

#### 2. 使用`Promise.allSettled()`

`Promise.allSettled()`方法接收一个Promise数组，不管Promise成功还是失败，返回的Promise都会被resolve，返回的结果是一个包含所有Promise状态的数组。

```javascript
async function fetchData() {
  const results = await Promise.allSettled([
    fetchData1(),
    fetchData2(),
    fetchData3(),
  ]);

  // 处理结果
  results.forEach((result) => {
    if (result.status === 'fulfilled') {
      console.log('成功:', result.value);
    } else if (result.status === 'rejected') {
      console.error('失败:', result.reason);
    }
  });
}
```

<br/>

### JavaScript 变量类型分为几种，区别是什么

公司：沪江、酷狗

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/456)
在JavaScript中，变量类型主要分为以下几种：

1. **基本数据类型（Primitive Data Types）：**
   - **Number（数字）：** 用于表示数字，包括整数和浮点数。例如：`let num = 10;`
   - **String（字符串）：** 用于表示文本。例如：`let str = "Hello";`
   - **Boolean（布尔值）：** 用于表示逻辑值，只有两个值：true和false。例如：`let isValid = true;`
   - **Undefined（未定义）：** 表示声明了变量但未赋值时的默认值。例如：`let value;`
   - **Null（空值）：** 表示没有值或空对象指针。例如：`let obj = null;`
   - **Symbol（符号）：** 用于创建唯一的标识符。例如：`let uniqueSymbol = Symbol('description');`
   - **BigInt（大整数）：** 用于表示任意精度的整数。例如：`let bigNum = 1234567890123456789012345678901234567890n;`

2. **引用数据类型（Reference Data Types）：**
   - **Object（对象）：** 用于表示复杂数据结构，包括数组、函数、日期等。例如：
     ```javascript
     let person = {
       name: "John",
       age: 30,
       hobbies: ["reading", "traveling"],
       sayHello: function() {
         console.log("Hello, " + this.name);
       }
     };
     ```

在JavaScript中，基本数据类型是按值传递的，即变量直接存储值。引用数据类型则是按引用传递的，变量存储的是对象的引用地址。这意味着当基本数据类型的变量赋值给另一个变量时，两个变量是相互独立的。而引用数据类型的变量赋值给另一个变量时，两个变量指向的是同一个对象，修改其中一个变量的值会影响到另一个变量。

例如：

```javascript
let num1 = 10;
let num2 = num1;
num2 = 20;
console.log(num1); // 输出：10，num1的值未受影响

let arr1 = [1, 2, 3];
let arr2 = arr1;
arr2.push(4);
console.log(arr1); // 输出：[1, 2, 3, 4]，arr1的值受到影响
```

基本数据类型的比较是按值比较的，而引用数据类型的比较是比较引用的地址。

<br/>

### JavaScript 里垃圾回收机制是什么，常用的是哪种，怎么处理的

公司：沪江、寺库

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/455)
JavaScript中的垃圾回收机制是一种自动管理内存的机制，它负责追踪内存中的变量，并在它们变得不再需要时将其释放，以便回收内存。垃圾回收的主要目标是标识并回收那些不再被程序使用的内存，以防止内存泄漏和提高程序性能。

JavaScript中常用的垃圾回收机制是**标记-清除算法（Mark and Sweep Algorithm）**。这个算法分为两个阶段：

1. **标记阶段（Marking）：** 在这个阶段，垃圾回收器会遍历所有的变量，标记那些仍然被引用的变量，通常是从全局对象开始递归遍历，标记所有可以被访问到的变量。

2. **清除阶段（Sweeping）：** 在这个阶段，垃圾回收器会遍历所有的变量，将未被标记的变量进行清除，释放其所占用的内存。

除了标记-清除算法，JavaScript引擎还会使用**引用计数（Reference Counting）**作为一种垃圾回收策略，但是引用计数在处理循环引用时会出现问题，因此在现代JavaScript引擎中主要使用标记-清除算法。

在日常开发中，开发者不需要手动处理垃圾回收。JavaScript引擎会自动执行垃圾回收，释放不再使用的内存。但是，开发者可以通过合理的代码设计和避免产生不必要的引用关系，来减少内存泄漏的可能性，例如避免在全局对象上存储大量数据，及时释放不再使用的引用等。

<br/>

### ES5 和 ES6 有什么区别

公司：饿了么

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/448)
ES5（ECMAScript 5）和ES6（ECMAScript 2015，也称为ES6或ECMAScript 6）是JavaScript的两个不同版本，它们之间存在一些重要的区别：

#### 1. **语法糖和新特性：**

- **let 和 const 关键字：** ES6引入了`let`和`const`关键字，用于声明变量，与`var`不同，它们具有块级作用域。
- **箭头函数：** ES6引入了箭头函数（Arrow Functions）语法，简化了函数的书写形式。
- **模板字符串：** ES6允许使用模板字符串（Template Strings）来创建多行字符串和在字符串中插入变量。
- **解构赋值：** ES6引入了解构赋值（Destructuring Assignment）语法，可以方便地从对象或数组中提取值并赋给变量。
- **类和继承：** ES6引入了类（Class）和extends关键字，使得面向对象编程更加方便。
- **Promise：** ES6引入了Promise对象，用于处理异步操作，解决了回调地狱的问题。
- **模块化：** ES6引入了模块化的概念，使用`import`和`export`关键字进行模块的导入和导出。

#### 2. **新的API和数据结构：**

- **Set 和 Map：** ES6引入了Set和Map这两种新的数据结构，用于存储唯一值和键值对。
- **Symbol：** ES6引入了Symbol数据类型，用于创建唯一的标识符，通常用作对象的属性名。
- **Proxy 和 Reflect：** ES6引入了Proxy和Reflect对象，用于创建代理对象和提供拦截操作的方法。

#### 3. **改进的函数和方法：**

- **默认参数：** ES6允许函数参数设置默认值，简化了函数的定义。
- **剩余参数和扩展操作符：** ES6引入了剩余参数（Rest Parameters）和扩展操作符（Spread Operator），方便处理不定数量的参数和数组、对象的拷贝与合并。

#### 4. **Promise 和异步编程：**

- **Promise：** ES6引入了Promise对象，提供了更好的异步编程解决方案，避免了回调地狱。
- **async/await：** ES7引入了async/await语法，基于Promise提供了更加简洁和可读性更强的异步编程语法。

<br/>

### 取数组的最大值（ES5、ES6）

公司：饿了么

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/447)

<br/>

### some、every、find、filter、map、forEach 有什么区别

公司：饿了么

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/446)

<br/>

### 页面上生成一万个 button，并且绑定事件，如何做（JS 原生操作 DOM）？循环绑定时的 index 是多少，为什么，怎么解决？

公司：饿了么

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/445)

<br/>

### 页面上有一个 input，还有一个 p 标签，改变 input 后 p 标签就跟着变化，如何处理？监听 input 的哪个事件，在什么时候触发？

公司：饿了么

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/444)

<br/>

### Promise 和 async/await，和 Callback 有什么区别

公司：携程、海风教育

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/442)

<br/>

### 项目中对于用户体验做过什么优化

公司：喜马拉雅

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/436)

<br/>

### 前后端通信使用什么方案

公司：喜马拉雅

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/434)

<br/>

### RESTful 常用的 Method

公司：喜马拉雅

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/433)

<br/>

### prototype 和proto区别

公司：兑吧

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/429)

<br/>

### new 的实现原理，动手实现一个 new

公司：兑吧

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/428)

<br/>

### 如何实现 H5 手机端的适配

公司：兑吧、网易、心娱

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/427)

<br/>

### 如何去除 url 中的#号

公司：兑吧

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/423)

<br/>

### base64 为什么能提升性能，缺点

公司：兑吧

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/421)

<br/>

### 介绍 webp 这个图片文件格式

公司：兑吧

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/420)

<br/>

### 异步请求，低版本 fetch 如何低版本适配

公司：兑吧

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/418)

<br/>

### ajax 如何处理跨域？CORS 如何设置？

公司：兑吧

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/417)

<br/>

### jsonp 为什么不支持 post 方法

公司：兑吧

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/416)

<br/>

### 介绍 Immuable

公司：兑吧

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/415)

<br/>

### 介绍 JS 全部数据类型，基本数据类型和引用数据类型的区别

公司：微医、玄武科技、快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/613)

<br/>

### Array 是 Object 类型吗

公司：微医

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/612)

<br/>

### 说一下栈和堆的区别，垃圾回收时栈和堆的区别

公司：微医、寺库

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/611)

<br/>

### 数组里面有 10 万个数据，取第一个元素和第 10 万个元素的时间相差多少

公司：微医

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/610)

<br/>

### Async/Await 怎么实现

公司：微医

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/609)

<br/>

### JavaScript 为什么要区分微任务和宏任务

公司：微医

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/608)

<br/>

### Promise 构造函数是同步还是异步执行，then 呢

公司：微医

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/607)

<br/>

### JavaScript 执行过程分为哪些阶段

公司：微医

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/605)

<br/>

### 词法作用域和 this 的区别

公司：微医

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/604)

<br/>

### loadsh 深拷贝实现原理

公司：微医

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/603)

<br/>

### ES6 中 let 块作用域是怎么实现的

公司：微医

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/602)

<br/>

### formData 和原生的 ajax 有什么区别

公司：宝宝树

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/779)

<br/>

### 介绍下表单提交，和 formData 有什么关系

公司：宝宝树

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/778)

<br/>

### promise 如何实现 then 处理，动手实现 then

公司：宝宝树

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/775)

<br/>

### 如何处理异常捕获

公司：海康威视

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/770)

<br/>

### 项目如何管理模块

公司：海康威视

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/769)

<br/>

### 尽可能多的写出判断数组的方法

公司：海康威视、新东方

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/768)

<br/>

### 介绍 localstorage 的 api

公司：海康威视

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/767)

<br/>

### 使用原型最大的好处

公司：蘑菇街

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/765)

<br/>

### 单例、工厂、观察者项目中实际场景

公司：酷家乐

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/763)

<br/>

### 添加原生事件不移除为什么会内存泄露，还有哪些地方会存在内存泄漏

公司：酷家乐

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/762)

<br/>

### setInterval 需要注意的点

公司：酷家乐

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/761)

<br/>

### 定时器为什么是不精确的

公司：酷家乐

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/760)

<br/>

### setTimeout(1)和 setTimeout(2)之间的区别

公司：酷家乐

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/759)

<br/>

### 介绍宏任务和微任务

公司：酷家乐

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/758)

<br/>

### promise 里面和 then 里面执行有什么区别

公司：酷家乐

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/757)

<br/>

### 介绍 class 和 ES5 的类以及区别

公司：酷家乐

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/755)

<br/>

### 介绍 defineProperty 方法，什么时候需要用到

公司：酷家乐

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/754)

<br/>

### for..in 和 object.keys 的区别

公司：酷家乐

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/753)

<br/>

### 使用闭包特权函数的使用场景

公司：酷家乐

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/752)

<br/>

### JavaScript 是什么范式语言

公司：海风教育

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/743)

<br/>

### Promise 有没有解决异步的问题

公司：海风教育

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/742)

<br/>

### Promise 和 setTimeout 的区别

公司：海风教育

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/741)

<br/>

### 按照调用实例，实现下面的 Person 方法

```js
Person("Li");
// 输出： Hi! This is Li!

Person("Dan").sleep(10).eat("dinner");
// 输出：
// Hi! This is Dan!
// 等待10秒..
// Wake up after 10
// Eat dinner~

Person("Jerry").eat("dinner").eat("supper");
// 输出：
// Hi This is Jerry!
// Eat dinner~
// Eat supper~

Person("Smith").sleepFirst(5).eat("supper");
// 输出：
// 等待5秒
// Wake up after 5
// Hi This is Smith!
// Eat supper
```

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/738)

<br/>

### 请写出正确的执行结果

```js
var yideng = {
  bar: function () {
    return this.baz;
  },
  baz: 1,
};
(function () {
  console.log(typeof arguments[0]());
})(yideng.bar);
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/737)

<br/>

### 请写出正确的执行结果

```js
function test() {
  console.log("out");
}
(function () { 
  if (false) {
    function test() {
      console.log("in");
    }
    test();
  }
})();
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/736)

<br/>

### 请写出正确的执行结果

```js
var x = [typeof x, typeof y][1];
typeof x;
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/735)

<br/>

### 请写出正确的执行结果

```js
(function (x) {
  delete x;
  return x;
})(1);
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/734)

<br/>

### 请写出正确的执行结果

```js
var x = 1;
if (function f() {}) {
  x += typeof f;
}
x;
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/733)

<br/>

### 请写出正确的执行结果

```js
function f() {
  return f;
}
new f() instanceof f;
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/732)

<br/>

### 请写出代码正确执行结果，并解释原因

```js
Object.prototype.a = "a";
Function.prototype.a = "a1";
function Person() {}
var yideng = new Person();
console.log(yideng.a);
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/731)

<br/>

### 请写出正确的执行结果

```js
var yideng = [0];
if (yideng) {
  console.log(yideng == true);
} else {
  console.log("yideng");
}
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/730)

<br/>

### 请写出正确的执行结果

```js
function yideng() {
  return
  {
    a: 1;
  }
}
var result = yideng();
console.log(result.a);
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/729)

<br/>

### 按要求完成代码

```js
const timeout = (ms) =>
  new Promise((resolve, reject) => {
    setTimeout(() => {
      resolve();
    }, ms);
  });
const ajax1 = () =>
  timeout(2000).then(() => {
    console.log("1");
    return 1;
  });
const ajax2 = () =>
  timeout(1000).then(() => {
    console.log("2");
    return 2;
  });
const ajax3 = () =>
  timeout(2000).then(() => {
    console.log("3");
    return 3;
  });
const mergePromise = (ajaxArray) => {
  // 1,2,3 done [1,2,3] 此处写代码 请写出ES6、ES3 2中解法
};
mergePromise([ajax1, ajax2, ajax3]).then((data) => {
  console.log("done");
  console.log(data); // data 为[1,2,3]
});
// 执行结果为：1 2 3 done [1,2,3]
```

公司：阿里

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/728)

<br/>

### 请写出正确的执行结果

```html
<script>
  //使用未定义的变量yideng
  yideng;
  console.log(1);
</script>
<script>
  console.log(2);
</script>
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/727)

<br/>

### 请写出正确的执行结果

```js
var yideng = Array(3);
yideng[0] = 2;
var result = yideng.map(function (elem) {
  return "1";
});
console.log(result);
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/726)

<br/>

### 请修改代码能跳出死循环

```js
while (1) {
  switch ("yideng") {
    case "yideng":
    //禁止直接写一句break
  }
}
```

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/725)

<br/>

### 请写出代码正确执行结果

```js
[1 < 2 < 3, 3 < 2 < 1];
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/723)

<br/>

### 请写出代码正确执行结果

```js
2 == [[[2]]];
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/722)

<br/>

### 计算以上字节每位 ✈️ 的起码点，并描述这些字节的起码点代表什么

```js
console.log("✈️".length);
// 1.计算以上字节每位✈️的起码点
// 2.描述这些字节的起码点代表什么
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/721)

<br/>

### 请写出代码正确执行结果，并解释原因

```js
var yidenga = Function.length,
  yidengb = new Function().length;
console.log(yidenga === yidengb);
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/720)

<br/>

### 请写出代码正确执行结果

```js
var length = 10;
function fn() {
  console.log(this.length);
}
var yideng = {
  length: 5,
  method: function (fn) {
    fn();
    arguments[0]();
  },
};
yideng.method(fn, 1);
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/719)

<br/>

### 介绍箭头函数的 this

公司：百分点

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/747)

<br/>

### 请写出代码正确执行结果，并解释原因

```js
var yi = new Date("2018-08-20"),
  deng = new Date(2018, 08, 20);
[yi.getDay() === deng.getDay(), yi.getMonth() === deng.getMonth()];
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/718)

<br/>

### 请写出代码正确执行结果

```js
for (
  let i = (setTimeout(() => console.log("a->", i)), 0);
  setTimeout(() => console.log("b->", i)), i < 2;
  i++
) {
  i++;
}
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/717)

<br/>

### 请写出代码正确执行结果，并解释原因

```js
[typeof null, null instanceof Object];
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/716)

<br/>

### 请问当前 textarea 文本框展示的内容是什么？

```html
<textarea maxlength="10" id="yideng"></textarea>
<script>
  document.getElementById("yideng").value = "a".repeat(10) + "b";
</script>
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/715)

<br/>

### 请写出代码正确执行结果

```js
function sidEffecting(ary) {
  arr[0] = arr[2];
}
function yideng(a, b, c = 3) {
  c = 10;
  sidEffecting(arguments);
  return a + b + c;
}
yideng(1, 1, 1);
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/714)

<br/>

### 请写出代码正确执行结果

```js
yideng();
var flag = true;
if (flag) {
  function yideng() {
    console.log("yideng1");
  }
} else {
  function yideng() {
    console.log("yideng2");
  }
}
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/713)

<br/>

### 请写出代码正确执行结果，并解释为什么

```js
var min = Math.min(),
  max = Math.max();
console.log(min < max);
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/712)

<br/>

### 请手写实现一个拖拽

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/711)

<br/>

### 请手动实现一个浅拷贝

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/710)

<br/>

### 介绍 instanceof 原理，并手动实现

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/709)

<br/>

### 请实现一个 JSON.stringfy

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/708)

<br/>

### 请实现一个 JSON.parse

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/707)

<br/>

### 请写出代码的正确执行结果，并解释原因？

```js
console.log("hello" + (1 < 2) ? "word" : "me");
```

公司：会小二

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/700)

<br/>

### 请写出代码的正确执行结果，并解释原因？

```js
var a = (b = 1);
(function () {
  var a = (b = 2);
})();
console.log(a, b);
```

公司：会小二

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/699)

<br/>

### 请写出代码的正确执行结果，并解释原因？

```js
if ([] instanceof Object) {
  console.log(typeof null);
} else {
  console.log(typeof undefined);
}
```

公司：会小二

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/698)

<br/>

### 请写出代码的正确执行结果，并解释原因？

```js
var obj = {};
obj.name = "first";
var peo = obj;
peo.name = "second";
console.log(obj.name);
```

公司：会小二

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/697)

<br/>

### 请写出代码的正确执行结果，并解释原因？

```js
function say(word) {
  let word = "hello";
  console.log(word);
}
say("hello Lili");
```

公司：会小二

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/696)

<br/>

### 请写出代码正确执行结果，并解释原因？

```js
function fun(n, o) {
  console.log(o);
  return {
    fun: function (m) {
      return fun(m, n);
    },
  };
}
var b = fun(0).fun(1).fun(2).fun(3);
```

公司：会小二

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/695)

<br/>

### JavaScript 中如何模拟实现方法的重载

公司：会小二

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/689)

<br/>

### 请解释 JSONP 的工作原理

公司：会小二、安居客

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/688)

<br/>

### 用 html、css、js 模拟实现一个下拉框，使得下拉框在各个浏览器下的样式和行为完全一致，说出你的设计方案，并且重点说明功能设计时要考虑的因素。

公司：会小二

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/687)

<br/>

### 实现一个打点计时器

```js
/* 
  1.从start至end,每隔100毫秒console.log一个数字，每次数字增幅为1
  2.返回的对象中需要包含一个cancel方法，用于停止定时操作
  3.第一个数字需要立即输出
*/
```

公司：会小二

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/685)

<br/>

### JavaScript 写一个单例模式，可以具体到某一个场景

公司：会小二

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/683)

<br/>

### JavaScript 基本数据类型都有哪些？用 typeOf 判断分别显示什么？

公司：会小二、安居客

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/682)

<br/>

### 怎么判断引用类型数据，兼容判断原始类型数据呢？

公司：会小二

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/681)

<br/>

### 概述异步编程模型

公司：酷狗

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/674)

<br/>

### 在一个 ul 里有 10 个 li,实现点击对应的 li,输出对应的下标

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/673)

<br/>

### 分别对以下数组进行去重，1:[1,'1',2,'2',3]，2:[1,[1,2,3['1','2','3'],4],5,6]

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/672)

<br/>

### 简述 JavaScript 中的函数的几种调用方式

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/671)

<br/>

### 编写一个 Person 类，并创建两个不同的 Person 对象

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/670)

<br/>

### 手写实现 call

公司：腾讯应用宝

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/666)

<br/>

### 手写实现 apply

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/665)

<br/>

### 一个 dom 必须要操作几百次，该如何解决，如何优化？

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/664)

<br/>

### 页面埋点怎么实现

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/660)

<br/>

### 除了 jsonp、postmessage 后端控制，怎么实现跨页面通讯

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/659)

<br/>

### 说一下 let、const 的实现，动手实现一下

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/655)

<br/>

### addEventListener 再 removeListener 会不会造成内存泄漏

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/651)

<br/>

### scrollview 如何进行性能优化(例如 page=100 时，往上滚动)

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/650)

<br/>

### 原生 JavaScript 获取 ul 中的第二个 li 里边的 p 标签的内容

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/648)

<br/>

### 说下 offsetWith 和 clientWidth、offsetHeight 和 clientHeight 的区别，说说 offsetTop，offsetLeft，scrollWidth、scrollHeight 属性都是干啥的

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/647)

<br/>

### 写一个函数打乱一个数组，传入一个数组，返回一个打乱的新数组

公司：快手

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/643)

<br/>

### 数组截取插入 splice，push 返回值，数组的栈方法、队列方法、排序方法、操作方法、迭代方法说一下

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/642)

<br/>

### 判断一个变量的类型，写个方法用 Object.prototype.toString 判断传入数据的类型

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/641)

<br/>

### 判断一个变量的类型，写个方法用 Object.prototype.toString 判断传入数据的类型？Object.prototype.toString.call(Symbol) 返回什么？

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/640)

<br/>

### 对作用域和闭包的理解，解释下 let 和 const 的块级作用域

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/639)

<br/>

### 以下代码输出什么？

```js
setTimeout(function () {
  console.log(1);
}, 0);
new Promise(function executor(resolve) {
  console.log(2);
  for (var i = 0; i < 10000; i++) {
    i == 9999 && resolve();
  }
  console.log(3);
}).then(function () {
  console.log(4);
});
console.log(5);
```

公司：心娱

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/638)

<br/>

### switch case，case 具体是怎么比较的，哪些情况下会走到 default

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/637)

<br/>

### 说下 typeof()各种类型的返回值？instanceof 呢？

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/636)

<br/>

### if([] == 0), [1,2] == "1,2", if([]), [] == 0 具体是怎么对比的

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/635)

<br/>

### 如何加快页面渲染速度，都有哪些方式

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/634)

<br/>

### generator 的实现原理

公司：滴滴、58

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/633)

<br/>

### 判断是否是数组的方法

公司：头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/627)

<br/>

### 手写 EventEmitter 实现

公司：头条、亚美科技

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/624)

<br/>

### 给出的两行代码为什么这么输出

```js
var s = "laohu";
s[0] = 1;
console.log(s); //laohu
var s = "laohu";
s += 2020;
console.log(s); // laohu2020
// 上面两行为什么这么输出
```

公司：老虎

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/622)

<br/>

### 动画性能如何检测

公司：酷狗

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/621)

<br/>

### 平时都用到了哪些设计模式

公司：酷狗、沪江、58

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/619)

<br/>

### 对 service worker 的理解

公司：酷狗

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/617)

<br/>

### 单点登录实现原理

公司：CVTE

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/862)

<br/>

### 尾递归实现

公司：CVTE

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/861)

<br/>

### 有 1000 个 dom，需要更新其中的 100 个，如何操作才能减少 dom 的操作？

公司：爱范儿

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/860)

<br/>

### 商城的列表页跳转到商品的详情页，详情页数据接口很慢，前端可以怎么优化用户体验？

公司：爱范儿

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/859)

<br/>

### 多个 tab 只对应一个内容框，点击每个 tab 都会请求接口并渲染到内容框，怎么确保频繁点击 tab 但能够确保数据正常显示？

公司：爱范儿

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/858)

<br/>

### 请实现鼠标点击页面中的任意标签，alert 该标签的名称(注意兼容性)

公司：爱范儿、道一云

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/854)

<br/>

### 完成一个表达式，验证用户输入是否是电子邮箱

公司：爱范儿

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/853)

<br/>

### 原生实现 ES5 的 Object.create()方法

公司：爱范儿

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/852)

<br/>

### 如何记录前端在用户浏览器上发生的错误并汇报给服务器？

公司：爱范儿

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/850)

<br/>

### 有哪几种方式可以解决跨域问题？(描述对应的原理)

公司：爱范儿

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/849)

<br/>

### 按要求完成题目

```js
/* 
  a)在不使用vue、react的前提下写代码解决一下问题
    一个List页面上，含有1000个条目的待办列表，现其中100项在同一时间达到了过期时间，需要在对应项的text-node里添加“已过期”文字。需要尽可能减少dom重绘次数以提升性能。
  b)尝试使用vue或react解决上述问题
*/
```

公司：爱范儿

分类：JavaScript、Vue、React、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/848)

<br/>

### 你是如何组织 JavaScript 代码的？（可以从模块、组件、模式、编程思想等方面回答）

公司：爱范儿

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/847)

<br/>

### 填充代码实现 template 方法

```js
var str = "您好，<%=name%>。欢迎来到<%=location%>";
function template(str) {
  // your code
}
var compiled = template(srt);
// compiled的输出值为：“您好，张三。欢迎来到网易游戏”
compiled({ name: "张三", location: "网易游戏" });
```

公司：网易

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/844)

<br/>

### 请描述下为什么页面需要做优化？并写出常用的页面优化实现方案？

公司：玄武科技

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/841)

<br/>

### 请列出至少 5 个 JavaScript 常用的内置对象，说明用途

公司：玄武科技

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/838)

<br/>

### 请描述下 JavaScript 中 Scope、Closure、Prototype 概念，并说明 JavaScript 封装、继承实现原理。

公司：玄武科技

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/837)

<br/>

### 请列出目前主流的 JavaScript 模块化实现的技术有哪些？说出它们的区别？

公司：玄武科技

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/836)

<br/>

### 请用 JavaScript 代码实现事件代理

公司：玄武科技

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/832)

<br/>

### 实现格式化输出，比如输入 999999999，输出 999,999,999

公司：亚美科技

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/831)

<br/>

### 使用 JavaScript 实现 cookie 的设置、读取、删除

公司：亚美科技

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/830)

<br/>

### 请编写一个 JavaScript 函数 parseQueryString,它的用途是把 URL 参数解析为一个对象，url="http://iauto360.cn/index.php?key0=0&key1=1&key2=2"

公司：亚美科技

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/829)

<br/>

### 如何实现 a,b 两个变量的交换

公司：高思教育

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/825)

<br/>

### 给 JavaScript 的 String 原生对象添加一个名为 trim 的原型方法，用于截取字符串前后的空白字符

公司：高思教育

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/822)

<br/>

### 微任务和宏任务的区别

公司：58

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/814)

<br/>

### 原生 JavaScript 实现图片懒加载的思路

公司：安居客

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/809)

<br/>

### 回调函数和任务队列的区别

公司：安居客

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/808)

<br/>

### 写出下面代码的输出结果

```js
//counter.js
let counter = 10;
export default counter;

//index.js
import myCounter from "./counter";
myCounter += 1;
console.log(myCounter);
```

公司：快手

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/802)

<br/>

### 有这样一个函数 A,要求在不改变原有函数 A 功能以及调用方式的情况下，使得每次调用该函数都能在控制台打印出“HelloWorld”

```js
function A() {
  console.log("调用了函数A");
}
```

公司：新东方

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/800)

<br/>

### 在浏览器执行以下代码，写出打印结果

```js
console.log("start");
setTimeout(() => {
  console.log("children2");
  Promise.resolve().then(() => {
    console.log("children3");
  });
}, 0);
new Promise(function (resolve, reject) {
  console.log("children4");
  setTimeout(function () {
    console.log("children5");
    resolve("children6");
  }, 0);
}).then((res) => {
  console.log("children7");
  setTimeout(() => {
    console.log(res);
  }, 0);
});
```

公司：新东方

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/799)

<br/>

### 请写出弹出值，并解释为什么？

```js
alert(a);
a();
var a = 3;
function a() {
  alert(10);
}
alert(a);
a = 6;
a();
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/794)

<br/>

### 写出输出值，并解释为什么

```js
function test(m) {
  m = { v: 5 };
}
var m = { k: 30 };
test(m);
alert(m.v);
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/793)

<br/>

### 请写出代码执⾏结果，并解释为什么

```js
function yideng() {
  console.log(1);
}
(function () {
  if (false) {
    function yideng() {
      console.log(2);
    }
  }
  console.log(typeof yideng);
  yideng();
})();
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/792)

<br/>

### 请写出代码执⾏结果，并解释为什么

```js
function fn() {
  console.log(this.length);
}
var person = {
  length: 5,
  method: function (fn) {
    fn();
  },
};
person.method(fn, 1);
```

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/790)

<br/>

### 给定⼀个⼤⼩为 n 的数组，找到其中的众数。众数是指在数组中出现次数⼤于 n/2 的元素

分类：数据结构与算反

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/789)

<br/>

### 原生实现addClass,用多种方法

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/783)

<br/>

### 实现一个倒计时,setInterval实现的话，如何消除时间误差

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/871)

<br/>

### 函数中的arguments是数组吗？若不是，如何将它转化为真正的数组？

公司：头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/866)

<br/>

### 请写出以下代码的打印结果

```js
if([] == false){console.log(1)};
if({} == false) {console.log(2)};
if([]){console.log(3)};
if([1] == [1]){console.log(4)};
```

公司：头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/865)

<br/>

### 以最小的改动解决以下代码的错误(可以使用ES6)

```js
const obj = {
  name:"jsCoder",
  skill:["es6","react","angular"],
  say:function(){
    for(var i = 0,len = this.skill.length;i<len;i++){
      setTimeout(function(){
        console.log('No.' + i + this.name);
        console.log(this.skill[i]);
        console.log('----------------');
      },0);
      console.log(i);
    }
  }
}
obj.say();

/* 
  期望得到下面的结果
  1
  2
  3
  No.1 jsCoder
  es6
  ----------------
  No.2 jsCoder
  react
  ----------------
  No.3 jsCoder
  angular
*/
```

公司：头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/864)

<br/>

### 实现Function 原型的bind方法，使得以下程序最后能输出“success”

```js
function Animal(name,color){
  this.name = name;
  this.color = color;
}
Animal.prototype.say = function(){
  return `I'm a ${this.color}${this.name}`;
}
const Cat = Animal.bind(null,'cat');
const cat = new Cat('white');
if(cat.say() === "I'm white cat" && cat instanceof Cat && cat instanceof Animal){
  console.log('sunccess');
}
```

公司：头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/863)

<br/>

### 文件上传如何做断点续传

公司：网易、洋葱学院

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/236)

<br/>

### 列举 3 种强制类型转换和 2 种隐式类型转换

公司：58

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/812)

<br/>