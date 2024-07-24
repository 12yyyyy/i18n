<p align="center">
    <a href="https://12yyyyy.github.io/i18n/" target="_blank" rel="noopener noreferrer">
        <img width="100" src="/logo.jpg" alt="12yyyyy logo" />
    </a>
</p>

<p align="center"><b>贰耶</b> [ˈ12yyyyy]，耶系-i18n（internationalization）</p>



# CPOJ待上线(测试中)...

# i18n

（其来源是英文单词 internationalization的首末字符i和n，18为中间的字符数）是“国际化”的简称。在资讯领域，国际化(i18n)指让产品（出版物，软件，硬件等）无需做大的改变就能够适应不同的语言和地区的需要。对程序来说，在不修改内部代码的情况下，能根据不同语言及地区显示相应的界面。 在全球化的时代，国际化尤为重要，因为产品的潜在用户可能来自世界的各个角落。通常与i18n相关的还有L10n（“本地化”的简称）。

## 介绍

在信息技术领域，国际化与本地化（英文：internationalization and localization）是指修改软件使之能适应目标市场的语言、地区差异以及技术需要。

国际化是指在设计软件，将软件与特定语言及地区脱钩的过程。当软件被移植到不同的语言及地区时，软件本身不用做内部工程上的改变或修正。本地化则是指当移植软件时，加上与特定区域设置有关的信息和翻译文件的过程。

国际化和本地化之间的区别虽然微妙，但却很重要。国际化意味着产品有适用于任何地方的“潜力”；本地化则是为了更适合于“特定”地方的使用，而另外增添的特色。用一项产品来说，国际化只需做一次，但本地化则要针对不同的区域各做一次。这两者之间是互补的，并且两者合起来才能让一个系统适用于各地 [1]。

基于他们的英文单字长度过长，常被分别简称成i18n（18意味着在“internationalization”这个单字中，i和n之间有18个字母）及L10n。使用大写的L以利区分i18n中的i和易于分辨小写l与1。


## 背景信息
众所周知，计算机技术发源于英语国家，英语也因此成为世界范围内程序员的通用语言，许多优秀的编程语言、开发工具、文档都是英文版，导致许多软件开发者习惯首先开发英文版本，根据需要，再把软件界面和文档翻译成不同国家、地区的语言版本。

但是由于实现翻译的途径、翻译的工作效率、翻译的可重用性等因素各不相同，使翻译工作面临很大困境，也阻碍了软件的推广和应用。

为了方便地将软件翻译成不同语言的版本，需要一套翻译规范和通用工具，这就导致了“国际化”机制的出现。

仅仅翻译是不够的，同一种语言在不同国家、地区可能存在多个支系，它们在表达习惯、语法结构甚至文字种类和编码上都有不同，方言更是千奇百怪，通用的翻译其质量肯定是不高的。涉及到计算机领域，还存在操作习惯上的差别，而且对某种语言提供完美的输入、显示、打印、保存、传输并非一件轻而易举的事，这就导致了“本地化”机制的出现。

国际化是指在设计软件时，将软件与特定语言及地区脱钩的过程。当软件被移植到不同的语言地区时，软件本身不用做内部工程上的改变或修正。本地化则是指当移植软件时，加上与特定区域设置有关的资讯和翻译文件的过程。 国际化和本地化之间的区别虽然微妙，但却很重要。国际化意味着产品有适用於任何地方的潜力；本地化则是为了更适合於特定地方的使用，而另外增添的特色。用一项产品来说，国际化只需做一次，但本地化则要针对不同的区域各做一次。 这两者之间是互补的，并且两者结合起来才能让一个系统适用於各地。

简而言之，“国际化”是“本地化”的一部分，主要是指国际化的实现机制和翻译工作， “本地化”包含“国际化”，是对“国际化”的补充和完善，它还包括为实现对某种特定语言良好的支持而进行的有针对性的翻译调整以及对软件进行的打补丁工作。

在如微软及IBM等企业中，则会使用全球化（globalization）来表示此两者的合称。在英文中，也会使用 g11n做为简称。

随着全球经济的一体化，软件开发者开发出支持多国语言、国际化的应用是一种趋势。对于Web应用来说，同样的页面在不同的语言环境下需要显示不同的效果。也就是说，一个Web应用程序在运行时能够根据客户端请求所来自的国家和语言显示不同的用户界面。

## 国际组织

i18n 和 L10n 的国际组织是 Openi18n 组织，其前身是 li18nux 组织。它原来是制定GNU/Linux 自由操作系统上软件全球化标准的国际计划，后来扩充到GNU/Linux 之外所有开放源代码的技术领域，因而更名为 Open Internationalization Initiative，由非营利组织 Free Standards Group 赞助，并为世界各大厂商所支持，对于GNU/Linux 系统上的多国语言文字处理技术和环境有决定性的影响。各个开源软件开发组织通常都有负责“国际化”和“本地化”工作的分支机构。

i18n 主要使用 gettext 软件包使软件实现国际化支持。事实上它是一整套 i18n解决方案。现在开源程序中普遍通过分离语言文件 ，然后通过 gettext 软件包来实现国际化发展。

## 范围

国际化与本地化工作的焦点包括：

### 语言
电子文件
字母。目前大部分的系统都采用统一码为标准来解决字符编码。
不同的数字命名系统。
书写方向。譬如德语是从左到右，而波斯语、希伯来语和阿拉伯语是由右到左。
相同语言在不同地区的拼法差异，如美国英语、加拿大英语使用localization，而英国英语和澳大利亚英语使用localisation。
文件处理上的差异，如某些文字存在大小写，其它则否。字母顺序。
文字的图像表示（列印物、内含线上图片）。
读法（音频）
视频的字幕

### 文化
图片和颜色：这牵涉到理解和文化适宜的议题。
名字和称谓
政府给定的编码（如美国的社会安全码，英国的National Insurance number，爱沙尼亚的Isikukood及其它各国的身份证号码）和护照
电话号码、地址和国际邮递区号
货币 （符号、货币标志的位置）
度量衡
纸张大小


### 书写习惯
日期跟时间的格式，包含各式日历。
时区（在国际场合会使用世界标准时间）
数字格式（小数点、分隔点的位置、分隔所用的字符）

### 产品和服务所要面向的法规

### 只属于本地化的主题有：

翻译
针对特定语言（如东亚语言）的特别支持
符合当地习惯
符合当地的道德观念
针对当地撰写内容
符号
排序方法
美学
当地的文化价值和社会环境

## 困难

开发软件时，国际化和本地化对开发者是一个有挑战性的任务，特别是当软件当初设计时没有考虑这个问题时。通常作法是将文本和其他环境相关的资源与程序代码相分离。这样在理想的情况下，应对变化的环境时无需修改代码，只要修改资源，从而显著简化了工作。

开发团队需要了解其他语言和文化，而这样的人才可能难以寻觅。而且资源的复制也可能成为维护的恶梦。例如，如果某个语言中显示给用户的信息变化了，其他的翻译版本都要随之变化。Gettext之类软件库有助于解决这一问题。

由于自由软件自由地修改和再分发，因此它比较容易国际化。当KDE拥有70个语言版本时，大多数专有软件只能够用于商业上有利可图的语言。

## 区域设置

计算机中一套定义用户的语言、国家和用于定义用户希望在其用户界面上看到的各种可以改变的选择的参数集合。通常一个locale标识符至少包括一个语言标识符和一个区域标识符。

在UNIX和WINDOWS中，locale的控制是不同的。在UNIX下，通常通过环境变量来控制locale。这些环境变量包括：LC_ALL, LC_CTYPE, LC_TIME, 等等。你可以通过改变这些环境变量来控制你的程序或者命令所表现出来的locale，前提是这些程序或者命令必须是已经被国际化的和本地化的。在Windows下，你可以通过改变控制面板上的“语言/区域”中的区域的值来设定Windows的当前用户的locale。

与全球化的关系

国际化有时与 全球化 交替使用以描述联系日益紧密的世界的经济与文化影响。
国际化经常（特别是在软件中）指提供一个用于多语言的框架，有时也指事物（机构、理念）可以藉此影响多个民族的过程。 此时很少使用全球化，因为它一般指机构和产品出现与世界各地（同时也引起了对本地化的需求）。

本地化可能用于描述贴近最终用户以减小全球化的环境和其他副作用。

## 其它

除了i18n，L10n（localization），g11n（globalization），还有m17n（multilingualization），区别是：

i18n支持多种语言，但是同一时间只能是英文和一种选定的语言，例如英文+中文、英文+德文、英文+韩文等等；

L10n（localization），支持2种语言，英文和另外一种语言（例如中文）；

g11n（globalization），简单的理解可以认为g11n = i18n + L10n。

m17n（multilingualization）可以在同一时间支持多种语言，例如你可以在一个页面里看到中文、英文、德文和韩文。
