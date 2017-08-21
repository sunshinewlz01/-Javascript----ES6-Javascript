# 第1章 Javascript的前世今生和未来展望
Javascript已经从最初的1995年作为营销策略推出而获得战术优势的语言，发展到如今2017年最受欢迎应用平台（web）上的核心编程语言。这门语言不仅仅运行在浏览器中，还被用来创建桌面和移动应用，以及用于硬件设备嵌入式开发，甚至被用于NASA的太空套件设计开发。    
Javascript是如何走到今天的？未来又将如何发展？本文将着重介绍。

## Javascript标准简史
时间回到1995年，Netscape公司设想了一种HTML不能够实现的动态web网站。Brendan Eich最初被招进Netscape去开发一门功能上类似于Scheme但供浏览器使用的语言。他加入Netscape后发现，公司高层预期这门语言看起来像Java，并且达成这样效果的协议已经开始进行。    
Brendan借鉴Scheme的一等公民函数和原型链作为主要组成部门，仅仅花了10天时间创建了第一版Javascript原型，这个初版被命名为Mocha。它没有数组和对象字面量的概念，并且每一个错误都会导致一个alert报警。由于没有对异常做处理，直到今天，很多操作会导致NaN或者undefined。不过Brendan致力于DOM 0层级的工作和Javascript的最初版本为后来的标准化工作打下了坚实的基础。    

1995年9月，本次修订的Javascript随着Netscape Navigator 2.0浏览器的beta版本以LiveScript推销出去。1995年12月，随着Navigator 2.0 beta 3的发布，LiveScript又被重新命名为Javascript（这个商标为Sun公司所有，现在归属于Oracle）。这个版本发布后不久，Netscape公司又介绍了一门在Netscape Enterprise Server上编程的服务端Javascript实现，并把它命名为LiveWire。从[1998年的小册子](http://docs.oracle.com/cd/E19957-01/816-6411-10/contents.htm)可以看出，当初服务端Javascript LiveWire是多么复杂。1996年，微软通过对Javascript的反向工程实现，创建了Jscript，它被绑定到IE3，并且Jscript在IIS服务端同样可以使用。    

1996年，Javascript在ECMAScript的名义下开始走向标准化道路，在ECMA组织下面的TC39技术委员会领导下，被标准化到ECMA-262规范。由于Sun公司不愿意转让JavaScript的商标给ECMA，尽管Microsoft愿意转让Jscript，但是遭到了其他会员公司的反对，所以这门语言的名字就成了ECMAScript。    

由于存在实现上的抵触矛盾，Netscape的JavaScript和Microsoft的Jscript当时在TC39的标准委员会上占据主导地位。尽管如此，技术委员会还是取得了成果：把向后兼容作为黄金法则来遵守，比如说虽然有了新的严格相等运算符===，但是JavaScript同时兼容了非严格相等运算符==。    

ECMA-262规范的第一个版本在1997年6月发布，一年以后也就是1998年6月，这个规范在ISO/IEC 16262国际标准下呗重新定义，并且被ISO认证机构逐条审查认证，最终形成了第二版。
1999年12月，第三版正式发布，
