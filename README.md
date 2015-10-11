# per-FE-Interview
自己整理的前端面试题问题大纲，主要分三大部分html,css,js  
## [html部分]()  
1、[Doctype作用？严格模式与混杂模式如何区分？它们有何意义?](#Doctype作用？严格模式与混杂模式如何区分？它们有何意义?)  
2、[文本流和文档流](#文本流盒文档流)    
3、[什么是web语义化,有什么好处](#什么是web语义化,有什么好处)    
4、[`<img>`的title和alt有什么区别](#`<img>`的title和alt有什么区别)  
5、[行内元素有哪些？块级元素有哪些？空(void)元素有那些？](#行内元素有哪些？块级元素有哪些？空元素有那些？)  
6、[页面导入样式时，使用link和@import有什么区别？](#页面导入样式时，使用link和@import有什么区别？)  
7、[浏览器内核差异](#浏览器内核差异)   
8、[html5有哪些新特性、移除了那些元素？如何处理HTML5新标签的浏览器兼容问题？如何区分HTML和HTML5？](#html5有哪些新特性、移除了那些元素？如何处理HTML5新标签的浏览器兼容问题？如何区分HTML和HTML5？)  
9、[HTML5的离线储存怎么用，工作原理能不能解释一下？](#HTML5的离线储存怎么用，工作原理能不能解释一下？)  
10、[浏览器是怎么对HTML5的离线储存资源进行管理和加载的呢？](#浏览器是怎么对HTML5的离线储存资源进行管理和加载的呢？)  
11、[请描述一下cookies,sessionStorage和localStorage的区别？](#请描述一下cookies,sessionStorage和localStorage的区别？)  
12、[iframe有那些缺点？](#iframe有那些缺点？)  
13、[如何实现浏览器内多个标签页之间的通信? ](#如何实现浏览器内多个标签页之间的通信? )  
14、[如何使用websocket？如何兼容低浏览器？](#如何使用websocket？如何兼容低浏览器？)  
15、[页面可见性(PageVisibility)API可以有哪些用途？](#页面可见性(PageVisibility)API可以有哪些用途？)  
xx、[](#)  



  
------------------------------------------------------------------  


## [CSS部分]()  
1、[介绍一下标准的CSS的盒子模型？与IE的盒子模型有什么不同的？](#介绍一下标准的CSS的盒子模型？与IE的盒子模型有什么不同的？)   
2、[display有哪些值？说明他们的作用。position的值relative和absolute定位原点是？](#display有哪些值？说明他们的作用。position的值relative和absolute定位原点是？)  
3、[用纯CSS创建一个三角形的原理是什么？](#用纯CSS创建一个三角形的原理是什么？)  
4、[一个满屏品字布局如何设计?](#一个满屏品字布局如何设计?)    
5、[li与li之间有看不见的空白间隔是什么原因引起的？有什么解决办法？](#li与li之间有看不见的空白间隔是什么原因引起的？有什么解决办法？)    
6、[为什么要初始化CSS样式](#为什么要初始化CSS样式)   
7、[absolute的containing\block计算方式跟正常流有什么不同？](#absolute的containing\block计算方式跟正常流有什么不同？)  
8、[对BFC规范的理解？](#对BFC规范的理解？)  
9、[CSS里的visibility属性有个collapse属性值是干嘛用的？在不同浏览器下以后什么区别？](#CSS里的visibility属性有个collapse属性值是干嘛用的？在不同浏览器下以后什么区别？)  
10、[CSS权重优先级是如何计算的？](#CSS权重优先级是如何计算的？)   
11、[请解释一下浮动和它的工作原理？清除浮动的技巧](#请解释一下浮动和它的工作原理？清除浮动的技巧)   
12、[移动端的布局用过媒体查询吗？](#移动端的布局用过媒体查询吗？)  
13、[CSS优化、提高性能的方法有哪些？](#CSS优化、提高性能的方法有哪些？)  
14、[浏览器是怎样解析CSS选择器的？](#浏览器是怎样解析CSS选择器的？)  
15、[在网页中的应该使用奇数还是偶数的字体？为什么呢？](#在网页中的应该使用奇数还是偶数的字体？为什么呢？)  
16、[margin和padding分别适合什么场景使用？](#margin和padding分别适合什么场景使用？)  
17、[元素竖向的百分比设定是相对于容器的高度吗？](#元素竖向的百分比设定是相对于容器的高度吗？)  
18、[全屏滚动的原理是什么？用到了CSS的那些属性？](#全屏滚动的原理是什么？用到了CSS的那些属性？)  
19、[什么是响应式设计？响应式设计的基本原理是什么？如何兼容低版本的IE？](#什么是响应式设计？响应式设计的基本原理是什么？如何兼容低版本的IE？)  
20、[什么是伪元素，什么是伪类？,他们的区别是什么？](#什么是伪元素，什么是伪类？,他们的区别是什么？)  
21、[如何修改chrome记住密码后自动填充表单的黄色背景？](#如何修改chrome记住密码后自动填充表单的黄色背景？)  
22、[你对line-height是如何理解的？](#你对line-height是如何理解的？)  
23、[`position:fixed;`在android下无效怎么处理？](#fixed在android下无效怎么处理？)  
24、[`display:inline-block;`什么时候会显示间隙?](#inline-block什么时候会显示间隙)  
25、[`overflow:scroll;`时不能平滑滚动的问题怎么处理？](#overflow时不能平滑滚动的问题怎么处理？)  
26、[怎么让Chrome支持小于12px;的文字？](#怎么让Chrome支持小于12px;的文字？)  
27、[CSS3有哪些新特性（包含哪些模块）？](#CSS3有哪些新特性（包含哪些模块）？)  
28、[请解释一下CSS3的Flexbox（弹性盒布局模型）,以及适用场景？](#请解释一下CSS3的Flexbox（弹性盒布局模型）,以及适用场景？)  
29、[IE各个版本兼容性及hack](#IE各个版本兼容性及hack)   
xx、[](#)  

------------------------------------------------------------------   

##JavaScript部分









