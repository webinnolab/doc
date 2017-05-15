# 初识JavaScript
这个是在国外经常被应用的一条和JavaScript有关系的著名定律：

Atwood's Law: any application that can be written in JavaScript, will eventually be written in JavaScript.

翻译过来就是：
Atwood定律：凡是能用JavaScript写出来的，最终都会用JavaScript写出来。

# JavaScript是什么

JavaScript一种直译式脚本语言，是一种动态类型、弱类型、基于原型的语言，内置支持类型。它的解释器被称为JavaScript引擎，为浏览器的一部分，广泛用于客户端的脚本语言，最早是在HTML（标准通用标记语言下的一个应用）网页上使用，用来给HTML网页增加动态功能。
在1995年时，由Netscape公司的Brendan Eich，在网景导航者浏览器上首次设计实现而成。因为Netscape与Sun合作，Netscape管理层希望它外观看起来像Java，因此取名为JavaScript。但实际上它的语法风格与Self及Scheme较为接近。 
为了取得技术优势，微软推出了JScript，CEnvi推出ScriptEase，与JavaScript同样可在浏览器上运行。为了统一规格，因为JavaScript兼容于ECMA标准，因此也称为ECMAScript。

# JavaScript能做什么

## 现在JavaScript能做的事情已经非常多了：
* 图形处理
* PDF生成
* 建立服务器
* 编译解释器
* 图形界面
* 数据库
* 各种测试工具
* 视频和音频播放处理
* 通信
* 多人协作

等等等等.....


## Web前端
很早以前各大公司对于 Web 标准的恶战让 JS 的环境异常恶劣，加之语言其本身的不成熟让其功能仅限于一些简单的前端交互。Ajax 技术的出现让前端可以在不刷新页面的情况下和后端进行数据交换，jQuery/zepto 等库的盛行让 JS 变得异常简单，Bootstrap/Amaze UI 等 UI 框架更是让前端的成本无限降低，RequireJS/SeaJs 让 JavaScript 也可以进行依赖管理，MVVM（Model-View-ViewModel 的出现让前后端的分离做到了极致，JavaScript 在前端领域前景明朗。

## 后端之旅

2009年5月，Ryan Dah 发布了 Node 的最初版本。Node 是一个基于 Chrome JavaScript 运行时建立的平台，它对 Google V8 引擎进行了封装，使 JavaScript 第一次走出前端运行在了服务器上。这对 JavaScript 来说是一种质的突破，这使得 Web 编程可以只用一门语言便可完成。It's Amazing! Web 的大一统时代仿佛就要来了。同时 Node 也诞生了 npm，从此 JavaScript 也有了强大的包管理机制。

## Hybrid App

传统上 JavaScript 只能在浏览器中运行，Node 的出现让 JavaScript 运行在了服务端，然而脱离浏览器 JavaScript 还是不能跨平台运行。人们总是希望用一种方式去做所有的事情，于是聪明的工程师们就发明了 Hybrid App 这种形式，让 JavaScript 在一定意义上运行在了移动设备上。然而当前 Hybrid App 虽然让 JavaScript 也可以写出 JAVA/Objective-C 才能实现的 APP，但是这种方式仍然没有抛弃浏览器运行环境，对 WebView 有很强的依赖性，性能和原生应用还有很大差距。

![image.png](http://upload-images.jianshu.io/upload_images/3623627-1290b0839fc1a9e3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
## 桌面应用
至此 JavaScript 除了可以被浏览器解析，也可以作为后端语言使用，还可以用来构建移动端 APP。仿佛已经够强大了吧，然而这还不够，JavaScript 还可以用来构建桌面应用！

## Node-webkit
Node-webkit 是一个 Web 应用程序运行时环境，它可以让你以 Web 的方式来写桌面应用程序，你可以用任何流行的 Web 技术来编写一个跨平台（Windows，Linux，MacOS）的桌面程序，并且性能和交互也是良好的，Teambition 桌面客户端便是使用 Node-webkit 编写的。目前在GitHub 上有 24463 Star

## heXheX 
是有道公司开发的采用前端技术（HTML，CSS，JavaScript）开发桌面应用软件的跨平台解决方案，意在解决传统桌面应用开发中繁琐的 UI 和交互开发工作，使其变的简单而高效。特别适合重 UI，重交互的桌面应用软件。新版有道词典 beta 版的首页便是使用 heX 开发完成的

## 神作 React
ReactReact（React.js） 是由 FaceBook 开发和维护的前端框架，目前在 GitHub 得到了 27900+ star。它摒弃了 MVC/MVVM 的模式，仅仅是做 UI，开创性地采用了 Virtual DOM（虚拟 DOM）避免了 DOM 操作消耗性能的问题，将 UI 拆分成不同的可组合、可复用、可维护的组件，组件和组件之间耦合度极低，开发效率大幅度增加。在前端 UI 组件化的趋势下，这很值得去尝试。instagram.com全站都采用 React 进行开发。

## 游戏
世界上最流行的 2D 游戏引擎之一 Cocos2d 和最流行的 3D 游戏引擎之一 Unity3D 均支持 JS 开发游戏。

## Cocos2d-js
Cocos2d-JS 是 Cocos2d-x 的 JavaScript 版本，融合了 Cocos2d-html5 和Cocos2d-x JavaScript Bindings。它支持 Cocos2d-x 的所有核心特性并提供更简单易用的 JavaScript 风格 API，并且天然支持原生、浏览器跨平台应用。在3.0版中，Cocos2d-JS 完成了不同平台工作流的彻底整合，为不同平台提供了统一的开发体验。无论开发 Web 应用还是原生应用，都可以便捷地采用 Cocos2d-JS 实现“一次开发，全平台运行”。采用 Cocos2d-JS 开发的同一套 JavaScript 游戏代码，可以同时运行在 Mac OS X, Windows, iOS, Android等原生平台、以及所有现代浏览器上，这将使得我们的开发者轻松覆盖几乎所有发行渠道，带来前所未有的机遇。另一方面，若开发者只想开发一款 Web 轻度休闲游戏，Cocos2d-JS 也专门为此类游戏定制了 Lite Version，直接将 Cocos2d-JS Lite Version 集成到页面中即可使用。



![image.png](http://upload-images.jianshu.io/upload_images/3623627-3927dc140d37fecb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Unity3D
Unity3D 是一个跨平台的 3D 游戏引擎，与 Cocos2d 最大的区别在于前者主要面对 2D 游戏开发者，后者主要进行大型 3D 游戏的开发







