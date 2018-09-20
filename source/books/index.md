---
title: 我的图书库 —— 大前端是怎么炼成的
date: 2017-06-15 16:28:43
---

<style>
.book-wrapper {flex: 0 0 100%;margin:10px;flex-wrap: wrap;}
.library {width: 100%;}
.library .book-title{font-size:20px;font-weight:bold;}
.library .book-img{width:240px;height:310px;}
.library .book-img img{width:100%; height:100%;}
@media (min-width: 420px) {
  .library {display: flex; flex-wrap: wrap;}
}
@media (min-width: 420px) and (max-width: 800px) {
 .book-wrapper {flex: 0 0 calc(50%);margin:10px;padding:10px;}
}
@media (min-width: 801px) and (max-width: 1170px) {
 .book-wrapper {flex: 0 0 calc(50% - 24px);margin:10px;padding:10px;} 
}
@media (min-width: 1171px) and (max-width: 1400px) {
 .book-wrapper {flex: 0 0 calc(33% - 40px);margin:10px;padding:10px;} 
}
@media (min-width: 1401px) {
 .book-wrapper {flex: 0 0 calc(25% - 40px);margin:10px;padding:10px;} 
}
</style>

> 作为一名攻城狮(误~)，建立自己的知识仓库是很有必要的，结合着思维脑图等辅助工具能帮助自己更好地获取吸收知识。互联网行业就是与信息与变化打交道，作为一名前端er，JavaScript等基本功是底气，而架构与其他知识体系则需慢慢积累。在精研专业领域把视野慢慢拓宽，本书库以前端必精语言JS为主，当然，不仅仅是前端，大前端，全栈——生命不息，折腾不止，欢迎多多交流分享。

ps 标题只是大气和激励自己…  学海无涯，看官一笑

注：以下我例举的图书都已购物正版纸质或电子书，若是读完的书会写自己的书评，没读完的简历放的都是官方的…… （以此来监督自己的学习）

[更多细节请移步我的Github仓库](https://github.com/Fridolph/my-books)

## 近期购买 | 阅读 | 推荐 (排名不分先后)

<div class="library">
  <div class="book-wrapper">
    <div class="book-title">《深入理解ES6》</div>
    <div class="book-author">Nicholas C. Zakas / 2017-7</div>
    <div class="book-img"><img alt="深入理解ES6" src="https://img1.doubanio.com/lpic/s29478358.jpg" /></div>
    <div class="book-desc">高级程序设计的作者所写预售，7月10号拿到手了300多页，放着慢慢看了… 看目录非常不错，书本质量挺好，深入ES6推荐入手。</div>
  </div>  
  <div class="book-wrapper">
    <div class="book-title">《现代前端技术解析》</div>
    <div class="book-author">张成文 / 2017-4</div>
    <div class="book-img"><img alt="现代前端技术解析" src="https://img1.doubanio.com/lpic/s29428008.jpg" /></div>
    <div class="book-desc">对于我来说，今年最好的一本书没有之一，无论是对视野、面试、广度等都很具有参考性，当然深度的话还是得靠实践项目慢慢积累。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《Web API的设计与开发》</div>
    <div class="book-author">水野贵明 / 2017-5</div>
    <div class="book-img"><img alt="WebAPI的设计与开发" src="http://file.ituring.com.cn/SmallCover/1705413f5c52cffff0ce" /></div>
    <div class="book-desc">本书不仅适合在工作中需要设计、开发或修改Web API的技术人员阅读，对想了解技术细节的产品经理、运维人员而言，也有一定的参考价值。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《Web安全开发指南》</div>
    <div class="book-author">John Paul Mueller / 2017-7</div>
    <div class="book-img"><img alt="Web安全开发指南" src="http://file.ituring.com.cn/SmallCover/1705ed516d8cc2bafd33" /></div>
    <div class="book-desc">详细介绍了Web安全开发的必备知识，旨在让前端开发相关人士了解新形势下的安全技能，涉及从最新的智能手机到老旧的台式计算机等各种设备，并且不限定平台</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《前端架构设计》</div>
    <div class="book-author">Micah Godbolt / 2017-4</div>
    <div class="book-img"><img alt="前端架构设计" src="http://file.ituring.com.cn/SmallCover/01006227398faf4a1a1d" /></div>
    <div class="book-desc">作者结合自己在Red Hat公司的项目实战经历，探讨了前端架构原则和前端架构的核心内容，包括工作流程、测试流程和文档记录，以及作为前端架构师所要承担的具体开发工作</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《CSS核心技术详解》</div>
    <div class="book-author">肖志华 / 2017-6</div>
    <div class="book-img"><img alt="CSS核心技术详解" src="https://img3.doubanio.com/lpic/s29459174.jpg" /></div>
    <div class="book-desc">怎么说呢，读完没学到什么干货，当然亮点和不知道的知识也有，例子太随意且深度不够，300页2天读完不如去阅读张鑫旭老师的博客。</div>
  </div>
</div>

## JavaScript系列

### 原生JS

<div class="library">
  <div class="book-wrapper">
    <div class="book-title">《深入理解ES6》</div>
    <div class="book-author">Nicholas C. Zakas / 2017-7</div>
    <div class="book-img"><img alt="深入理解ES6" src="https://img1.doubanio.com/lpic/s29478358.jpg" /></div>
    <div class="book-desc">一本不错的书，高级程序设计的作者所写，不过这是预售，还没到手开看啦，啊哈哈</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《你不知道的JavaScript 上》</div>
    <div class="book-author">Kyle Simpson / 赵望野、梁杰 / 2015-4</div>
    <div class="book-img"><img alt="你不知道的JavaScript 上" src="https://img3.doubanio.com/lpic/s28033372.jpg" /></div>
    <div class="book-desc">非常棒的一本书，本书言简意赅的对JavaScript的各种细节娓娓道来，指出了JavaScript的一些陷阱以及如何避免它们，也给出了一下JavaScript的最佳实践。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《你不知道的JavaScript 中》</div>
    <div class="book-author">Kyle Simpson / 单业/姜南 / 2016-8</div>
    <div class="book-img"><img alt="你不知道的JavaScript 中" src="https://img3.doubanio.com/lpic/s28969600.jpg" /></div>
    <div class="book-desc">本套书直面当前JavaScript开发人员不求甚解的大趋势，深入理解语言内部的机制，全面介绍了JavaScript中常被人误解和忽视的重要知识点。本书是其中卷，主要介绍了类型、语法、异步和性能。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《ES6标准入门 (第2版)》</div>
    <div class="book-author">阮一峰 / 2016-1</div>
    <div class="book-img"><img alt="ES6标准入门 (第2版)" src="https://img3.doubanio.com/lpic/s28383612.jpg" /></div>
    <div class="book-desc">是国内仅有的一本 ES6 教程，在前版基础上增补了大量内容——对标准进行了彻底的解读，所有新增的语法知识（包括即将发布的 ES7）都给予了详细介绍，并且紧扣业界开发实践，给出了大量简洁易懂、可以即学即用的示例代码</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《实战 ES2015》</div>
    <div class="book-author">小问 / 2016-10</div>
    <div class="book-img"><img alt="实战 ES2015" src="https://img3.doubanio.com/lpic/s29114904.jpg" /></div>
    <div class="book-desc">在ES2015标准中的表现，以及利用ES2015中新特性在应用开发中的实践。以清晰的思路说明ES2015的详细特性和意义，并以实际案例展示利用ES2015中的特性如何提高应用的前端和后端的开发速度和工程化模式</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《精通JavaScript（第2版）》</div>
    <div class="book-author"> John Resig / John Paxton / Russ Ferguson / 2016-9 </div>
    <div class="book-img"><img alt="你不知道的JavaScript 中" src="https://img1.doubanio.com/lpic/s29028887.jpg" /></div>
    <div class="book-desc">想精通还是去读通犀牛书吧。不过本书对JS的一些细节和处理下了些功夫，算是高程里精要内容的提炼吧，不同思路可以一读</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《JavaScript高级程序设计（第3版）》</div>
    <div class="book-author">Nicholas C. Zakas / 2012-3</div>
    <div class="book-img"><img alt="JavaScript高级程序设计（第3版）" src="https://img3.doubanio.com/lpic/s8958650.jpg" /></div>
    <div class="book-desc">本书是JavaScript 超级畅销书的最新版。ECMAScript 5 和HTML5 在标准之争中双双胜出，使大量专有实现和客户端扩展正式进入规范，同时也为JavaScript 增添了很多适应未来发展的新特性。</div>
  </div>  
  <div class="book-wrapper">
    <div class="book-title">《JavaScript忍者秘籍》</div>
    <div class="book-author">John Resig / Bear Bibeault / 2015-10</div>
    <div class="book-img"><img alt="JavaScript忍者秘籍" src="https://img3.doubanio.com/lpic/s28313380.jpg" /></div>
    <div class="book-desc">JavaScript语言非常重要，相关的技术图书也很多，但没有任何一本书对JavaScript语言的重要部分（函数、闭包和原型）进行深入、全面的介绍，也没有任何一本书讲述跨浏览器代码的编写。本书是jQuery库创始人编写的一本深入剖析JavaScript语言的书</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《JavaScript学习指南》(第三版)</div>
    <div class="book-author">Ethan Brown / 2017-7</div>
    <div class="book-img"><img alt="JavaScript学习指南" src="https://img1.doubanio.com/mpic/s6633627.jpg" /></div>
    <div class="book-desc">和犀牛书封面一样，不过页数少一半多，最新的有讲到ES6相关的介绍，其实JS类进阶书都大同小异，关键是我们要把这些点都一一克服、理解，如果像我一样读不下去犀牛书的可以读读这本，效果挺好</div>
  </div>  
  <div class="book-wrapper">
    <div class="book-title">《JavaScript DOM编程艺术 （第2版）》</div>
    <div class="book-author">Jeremy Keith / Jeffrey Sambells / 2011-4</div>
    <div class="book-img"><img alt="JavaScript DOM编程艺术 （第2版）" src="https://img3.doubanio.com/lpic/s4677623.jpg" /></div>
    <div class="book-desc">JavaScript是Web开发中最重要的一门语言，它强大而优美。无论是桌面开发，还是移动应用。JavaScript都是必须掌握的技术。W3C的DOM标准是开发Web应用的基石。已经得到所有现代浏览器的支持，这使得跨平台Web开发成了一件轻松惬意的事。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《JavaScript权威指南(第6版)》</div>
    <div class="book-author">David Flanagan / 淘宝前端 / 2012-4</div>
    <div class="book-img"><img alt="JavaScript权威指南(第6版)" src="https://img3.doubanio.com/lpic/s8958854.jpg" /></div>
    <div class="book-desc">本书是程序员学习核心JavaScript语言和由Web浏览器定义的JavaScript API的指南和综合参考手册，工具书，有时间耐心可以慢慢读，不过我买来一直压箱底了……惭愧。</div>
  </div>  
</div>

### 性能与工程化

<div class="library">
  <div class="book-wrapper">
    <div class="book-title">《JavaScript设计模式与开发实践》</div>
    <div class="book-author">曾探 / 2015-5</div>
    <div class="book-img"><img alt="JavaScript设计模式与开发实践" src="https://img3.doubanio.com/lpic/s28065006.jpg" /></div>
    <div class="book-desc">本书在尊重《设计模式》原意的同时，针对JavaScript语言特性全面介绍了更适合JavaScript程序员的了16个常用的设计模式，讲解了JavaScript面向对象和函数式编程方面的基础知识，介绍了面向对象的设计原则及其在设计模式中的体现，还分享了面向对象编程技巧和日常开发中的代码重构</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《高性能JavaScript》</div>
    <div class="book-author">Nicholas C.Zakas / 2015-8</div>
    <div class="book-img"><img alt="高性能JavaScript" src="https://img3.doubanio.com/lpic/s6245861.jpg" /></div>
    <div class="book-desc">如果你使用JavaScript构建交互丰富的Web应用，那么JavaScript代码可能是造成你的Web应用速度变慢的主要原因。《高性能JavaScript》揭示的技术和策略能帮助你在开发过程中消除性能瓶颈。你将会了解如何提升各方面的性能，包括代码的加载、运行、DOM交互、页面生存周期等。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《编写可维护的JavaScript》</div>
    <div class="book-author">扎卡斯 / 2013-4</div>
    <div class="book-img"><img alt="编写可维护的JavaScript" src="https://img3.doubanio.com/lpic/s25808235.jpg" /></div>
    <div class="book-desc">《编写可维护的JavaScript》内容涵盖了编码风格、编程技巧、自动化、测试等几方面，既包括具体风格和原则的介绍，也包括示例和技巧说明，最后还介绍了如何通过自动化的工具和方法来实现一致的编程风格</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《JavaScript语言精粹》</div>
    <div class="book-author">Douglas Crockford / 2012-9</div>
    <div class="book-img"><img alt="JavaScript语言精粹" src="https://img3.doubanio.com/lpic/s27993864.jpg" /></div>
    <div class="book-desc">这是一本介绍 JavaScript 语言本质的权威书籍，值得任何正在或准备从事JavaScript 开发的人阅读，并且需要反复阅读。学习、理解、实践大师的思想，我们才可能站在巨人的肩上，才有机会超越大师，这本书就是开始。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《响应式Web设计性能优化》</div>
    <div class="book-author">Tom Barker  / 2015-9</div>
    <div class="book-img"><img alt="响应式Web设计性能优化" src="https://img3.doubanio.com/lpic/s29418010.jpg" /></div>
    <div class="book-desc">该书展示了如何在你的项目计划中将响应性和性能很好地结合起来，在服务器端，使用Node.js提供设备专有功能， 并且将自动测试整合到持续集成环境中。而且你将学习到很多非常有用的工具和响应式框架。</div>
  </div>
</div>

### 前端框架

<div class="library">
  <div class="book-wrapper">
    <div class="book-title">《深入react技术栈》</div>
    <div class="book-author">陈屹 / 2016-11</div>
    <div class="book-img"><img alt="深入react 技术栈" src="https://img3.doubanio.com/lpic/s29162154.jpg" /></div>
    <div class="book-desc">全面讲述React技术栈的第一本原创图书，pure render专栏主创倾力打造覆盖React、Flux、Redux及可视化，帮助开发者在实践中深入理解技术和源码前端组件化主流解决方案，一本书玩转React“全家桶”本书讲解了非常多的内容，不仅介绍了面向普通用户的API、应用架构和周边工具，还深入介绍了底层实现。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《深入浅出React和Redux》</div>
    <div class="book-author">程墨 / 2017-4</div>
    <div class="book-img"><img alt="深入浅出React和Redux" src="https://img3.doubanio.com/lpic/s29456776.jpg" /></div>
    <div class="book-desc">本书作者是资深开发人员，有过多年的开发经验，总结了自己使用React和Redux的实战经验，系统分析React和Redux结合的优势，与开发技巧，为开发大型系统提供参考。和上面那本深入比不了，不过作为入门React书还不错。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《React与Redux开发实例精解》</div>
    <div class="book-author">刘一奇 / 2016-12</div>
    <div class="book-img"><img alt="React与Redux开发实例精解" src="https://img3.doubanio.com/lpic/s29196005.jpg" /></div>
    <div class="book-desc">《React与Redux开发实例精解》适合熟悉JavaScript 编程，有意使用React 与Redux 搭建Web 应用的程序员学习参考。入门书还是挺友好的，结合着github上的例子，项目还是能跑起来，剩下的修行看个人</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《锋利的jQuery》</div>
    <div class="book-author">单东林 / 张晓菲 / 魏然 / 2012-7</div>
    <div class="book-img"><img alt="锋利的jQuery" src="https://img1.doubanio.com/lpic/s28026858.jpg" /></div>
    <div class="book-desc">循序渐进地对jQuery的各种函数和方法调用进行了介绍，读者可以系统地掌握jQuery的选择器、DOM操作、事件和动画、AJAX应用、插件、jQuery Mobile、jQuery各个版本变化、jQuery性能优化和技巧等知识点，并结合每个章节后面的案例演示进行练习，达到掌握核心知识点的目的。</div>
  </div>
</div>

## HTML与CSS

<div class="library">  
  <div class="book-wrapper">
    <div class="book-title">《Head First HTML与CSS（第2版）》</div>
    <div class="book-author">Lea Verou / 2016-4</div>
    <div class="book-img"><img alt="Head First HTML与CSS（第2版）" src="https://img3.doubanio.com/lpic/s27104165.jpg" /></div>
    <div class="book-desc">我的第一本入门书，强烈推荐！！至今看到它也会带着深厚的感情，默默陪伴着我度过了没有js的美好时光，只用简单的结构和样式就能写出漂亮的页面……每天无比开心，直到JavaScript那个大魔王的到来……</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《CSS揭秘》</div>
    <div class="book-author">Lea Verou / 2016-4</div>
    <div class="book-img"><img alt="CSS揭秘" src="https://img1.doubanio.com/lpic/s28659699.jpg" /></div>
    <div class="book-desc">本书是一本注重实践的教程，作者为我们揭示了 47 个鲜为人知的 CSS 技巧，主要内容包括背景与边框、形状、 视觉效果、字体排印、用户体验、结构与布局、过渡与动画等。本书将带领读者循序渐进地探寻更优雅的解决方案，攻克每天都会遇到的各种网页样式难题。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《HTML5基础知识、核心技术与前沿案例》</div>
    <div class="book-author">刘欢 / 2016-10</div>
    <div class="book-img"><img alt="HTML5基础知识、核心技术与前沿案例" src="https://img1.doubanio.com/lpic/s29137878.jpg" /></div>
    <div class="book-desc">《HTML5基础知识、核心技术与前沿案例 》是一本引导初、中级学习者深入了解并有效掌握HTML5核心技巧的技术实战书籍，全书采用“基础知识+案例驱动”的双轨模式，精心安排了大量经典的HTML5设计实战案例。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《CSS核心技术详解》</div>
    <div class="book-author">肖志华 / 2017-6</div>
    <div class="book-img"><img alt="CSS核心技术详解" src="https://img3.doubanio.com/lpic/s29459174.jpg" /></div>
    <div class="book-desc">《CSS核心技术详解》内容精练、实例丰富、通俗易懂，可作为广大CSS设计人员和前端开发人员的参考书。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《响应式Web设计（第二版）》</div>
    <div class="book-author">Ben Frain / 奇舞团 / 2017-2</div>
    <div class="book-img"><img alt="响应式Web设计（第二版）" src="https://img3.doubanio.com/lpic/s29295711.jpg" /></div>
    <div class="book-desc">挺不错的一本书，响应式就是这么简单，这本是买的电子书，内容不深，毕竟没有js那些逻辑，把html、css当小说看，用了3天晚上把书和例子搞定。css就是要多用多写多对比，无他，熟能生巧</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《HTML5与CSS3权威指南》</div>
    <div class="book-author">陆凌牛 / 2015-9</div>
    <div class="book-img"><img alt="HTML5与CSS3权威指南" src="https://img3.doubanio.com/lpic/s28319866.jpg" /></div>
    <div class="book-desc">(1—17章)全面系统地讲解了HTML 5相关的技术，以HTML 5对现有Web应用产生的变革开篇，顺序讲解了HTML 5与HTML 4的区别、HTML 5的结构、表单及新增页面元素、图形绘制、多媒体、本地存储、文件、WebRTC通信、扩展的XMLHttpRequest、离线应用、WebWorkers、地理位置信息、拖放与通知等内容</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《图解CSS3》</div>
    <div class="book-author">大漠 / 2014-7</div>
    <div class="book-img"><img alt="图解CSS3" src="https://img3.doubanio.com/lpic/s27319226.jpg" /></div>
    <div class="book-desc">本书内容极为全面、丰富和翔实，由浅入深地讲解了CSS3新特性的语法、功能和使用技巧，涵盖选择器、边框、背景、文本、颜色、UI、动画、新型盒模型、媒体查询、响应式设计等各种模块</div>
  </div>  
</div>

## 专业领域相关拓展

<div class="library">  
  <div class="book-wrapper">
    <div class="book-title">《深入浅出Node.js》</div>
    <div class="book-author">朴灵 / 2013-12</div>
    <div class="book-img"><img alt="深入浅出Node.js" src="https://img3.doubanio.com/lpic/s27269296.jpg" /></div>
    <div class="book-desc">本书从不同的视角介绍了 Node 内在的特点和结构。由首章Node 介绍为索引，涉及Node 的各个方面，主要内容包含模块机制的揭示、异步I/O 实现原理的展现、异步编程的探讨、内存控制的介绍、二进制数据Buffer 的细节、Node 中的网络编程基础、Node 中的Web 开发、进程间的消息传递、Node 测试以及通过Node 构建产品需要的注意事项</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《现代前端技术解析》</div>
    <div class="book-author">张成文 / 2017-4</div>
    <div class="book-img"><img alt="现代前端技术解析" src="https://img1.doubanio.com/lpic/s29428008.jpg" /></div>
    <div class="book-desc">这是一本以现代前端技术思想与理论为主要内容的书。前端技术发展迅速，涉及的技术点很多，我们往往需要阅读很多书籍才能理解前端技术的知识体系。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《Web API的设计与开发》</div>
    <div class="book-author">水野贵明 / 2017-5</div>
    <div class="book-img"><img alt="WebAPI的设计与开发" src="http://file.ituring.com.cn/SmallCover/1705413f5c52cffff0ce" /></div>
    <div class="book-desc">本书不仅适合在工作中需要设计、开发或修改Web API的技术人员阅读，对想了解技术细节的产品经理、运维人员而言，也有一定的参考价值。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《Web安全开发指南》</div>
    <div class="book-author">John Paul Mueller / 2017-7</div>
    <div class="book-img"><img alt="Web安全开发指南" src="http://file.ituring.com.cn/SmallCover/1705ed516d8cc2bafd33" /></div>
    <div class="book-desc">详细介绍了Web安全开发的必备知识，旨在让前端开发相关人士了解新形势下的安全技能，涉及从最新的智能手机到老旧的台式计算机等各种设备，并且不限定平台</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《前端架构设计》</div>
    <div class="book-author">Micah Godbolt / 2017-4</div>
    <div class="book-img"><img alt="前端架构设计" src="http://file.ituring.com.cn/SmallCover/01006227398faf4a1a1d" /></div>
    <div class="book-desc">作者结合自己在Red Hat公司的项目实战经历，探讨了前端架构原则和前端架构的核心内容，包括工作流程、测试流程和文档记录，以及作为前端架构师所要承担的具体开发工作</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《MySQL必知必会》</div>
    <div class="book-author">Ben Forta / 2009-1</div>
    <div class="book-img"><img alt="MySQL必知必会" src="https://img3.doubanio.com/lpic/s29459174.jpg" /></div>
    <div class="book-desc">《MySQL必知必会》MySQL是世界上最受欢迎的数据库管理系统之一。书中从介绍简单的数据检索开始，逐步深入一些复杂的内容，包括联结的使用、子查询、正则表达式和基于全文本的搜索、存储过程、游标、触发器、表约束，等等。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《图解HTTP》</div>
    <div class="book-author">上野宣 / 2014-4</div>
    <div class="book-img"><img alt="图解HTTP" src="https://img3.doubanio.com/lpic/s27283822.jpg" /></div>
    <div class="book-desc">本书对互联网基盘——HTTP协议进行了全面系统的介绍。作者由HTTP协议的发展历史娓娓道来，严谨细致地剖析了HTTP协议的结构，列举诸多常见通信场景及实战案例，最后延伸到Web安全、最新技术动向等方面。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《数据结构与算法JavaScript描述》</div>
    <div class="book-author">Michael McMillan / 2014-8</div>
    <div class="book-img"><img alt="数据结构与算法JavaScript描述" src="https://img1.doubanio.com/lpic/s27371758.jpg" /></div>
    <div class="book-desc">通过本书的学习，读者将能自如地选择最合适的数据结构与算法，并在JavaScript开发中懂得权衡使用。此外，本书也概述了与数据结构与算法相关的JavaScript特性。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《算法图解》</div>
    <div class="book-author">Aditya Bhargava / 2017-3</div>
    <div class="book-img"><img alt="算法图解" src="https://img3.doubanio.com/lpic/s29358625.jpg" /></div>
    <div class="book-desc">本书示例丰富，图文并茂，以让人容易理解的方式阐释了算法，旨在帮助程序员在日常项目中更好地发挥算法的能量。注：例子都是python语言- -所以有了下面那本……入坑</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《Python编程：从入门到实践》</div>
    <div class="book-author">埃里克·马瑟斯 / 2016-7</div>
    <div class="book-img"><img alt="Python编程：从入门到实践" src="https://img1.doubanio.com/lpic/s29389159.jpg" /></div>
    <div class="book-desc">本书是一本针对所有层次的Python 读者而作的Python 入门书。全书分两部分：第一部分介绍用Python 编程所必须了解的基本概念，包括matplotlib、NumPy 和Pygal 等强大的Python 库和工具介绍，以及列表、字典、if 语句、类、文件与异常、代码测试等内容</div>
  </div>  
</div>

## 产品与设计

<div class="library">  
  <div class="book-wrapper">
    <div class="book-title">《人人都是产品经理》</div>
    <div class="book-author">苏杰 / 2010-4</div>
    <div class="book-img"><img alt="人人都是产品经理" src="https://img1.doubanio.com/lpic/s4241529.jpg" /></div>
    <div class="book-desc">产品入门书，这类适合当小说感，带着轻松愉快的心情，好了，一两晚估计就翻完了，然后呢？ Get到产品技能……（并不会）</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《人人都是设计师》</div>
    <div class="book-author">Rebecca Hagen / Kim Golombisky / 2016-9</div>
    <div class="book-img"><img alt="人人都是产品经理" src="https://img3.doubanio.com/lpic/s28990046.jpg" /></div>
    <div class="book-desc">本书是一本为没有艺术背景的普通人所写的平面设计指导书，作者通过图文并茂的典型案例讲解了设计的主要原则和规则，主要内容有：什么是设计，设计前的调查研究和头脑风暴，设计的元素和原理，版式的有效原则和13条规则，为什么需要网格，布局、字体和色彩的选用原则，如何使用照片、插图和信息图，多媒体组件，网页的输出和印刷输出等。</div>
  </div>
  <div class="book-wrapper">
    <div class="book-title">《设计师要懂心理学》</div>
    <div class="book-author">Susan Weinschenk / 2013-5</div>
    <div class="book-img"><img alt="设计师要懂心理学" src="https://img3.doubanio.com/lpic/s26251595.jpg" /></div>
    <div class="book-desc">内容实用，示例清晰，以创造美观实用的设计为宗旨，讨论了设计师必须了解的100个心理学问题，每个问题都配以权威经典的示例，并给出即学即用的设计建议，篇幅简短，让你轻松理解设计背后的心理学动机，拓展视野，创新思维，为你的设计打造全新用户体验。</div>
  </div>  
</div>

## 学习方法

<div class="library">
  <div class="book-wrapper">
    <div class="book-title">《番茄工作法图解》</div>
    <div class="book-author">Staffan Nöteberg / 2011-2</div>
    <div class="book-img">
      <img alt="番茄工作法图解" src="https://img3.doubanio.com/lpic/s4599081.jpg" />
    </div>
    <div class="book-desc">本书介绍了时下最流行的时间管理方法之一——番茄工作法。作者根据亲身运用番茄工作法的经历，以生动的语言，传神的图画，将番茄工作法的具体理论和实践呈现在读者面前。</div>
  </div> 
</div>

## 其他

... 其他类的就不放在这里了，[更多细节请移步我的Github仓库](https://github.com/Fridolph/my-books)

欢迎多多交流分享。