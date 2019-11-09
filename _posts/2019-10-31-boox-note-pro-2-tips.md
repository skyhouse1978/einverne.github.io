---
layout: post
title: "Boox Note 2 使用感受及小技巧"
tagline: ""
description: ""
category:
tags: [boox, e-ink, reader, e-reader, kindle, boox-note2]
last_updated:
---

作为 Kindle 的用户，很早就开始注意电子墨水屏，然而 Amazon 久久不推出大屏的电子墨水阅读器，这就使得阅读 PDF 变得困难，所以最开始的时候注意到了 Sony 出的两款电子墨水屏，但是无奈价格一直非常坚挺，所以在综合一番搜索之后，首先是 YouTube 上推荐了 Boox 这个品牌，再然后就是一番搜索，发现原来国内厂商一致在做着自己的努力，Boox，iReader,LikeBook 等等，台湾的厂商读墨今年也发布了 [mooInk](https://readmoo.com/mooink-series) 阅读器，电子墨水屏渐渐进入了大众的视线，经过这么多年的发展，技术也有了进步。所以综合考虑，我终于入手了这款 Boox Note 2, 原来考虑的是 Note Pro，但是看在新发布 Note 2, 系统较新，性能也更好一些，所以还是买了新发布的 Note 2.

## 购前调查 {#before}
就如上面所说，最终锁定 Boox，经过了非常复杂的心路历程。而在 Boox 复杂的机型中，也是经过了一番比较才锁定 Note2。首先要明确自己的需求，可能对于某些人来说电子墨水并不是最佳的选择，同价格档位的选择已经可以买一台入门的 iPad Air，甚至一台不错的笔记本了。而对于我，我得主要目的是用来读 PDF，硬盘中积累了非常多的 PDF 文件，因为电脑上看起来比较费劲，而且常常容易被打断，所以我想要一台沉浸能看 PDF 的设备，另外一点就是电子笔记，iPad 的笔记手写笔记体验使得整个行业重视起手写笔记的体验，手写笔记，不仅包括阅读时的批注，也包括完全的手写笔记本。我之前有一个非常迫切的需求就是将手上的纸质笔记本电子化，纸质内容占用体积，又比较难索引，所以长久以来就只能依靠网络笔记本 WizNote 之类来整理。

所以总结来看，有两点：

- 沉浸式的 PDF 阅读体验
- 手写笔记

实际上这两点，要想达到倒也不是很难，关掉通知的 iPad 就能做到，但是结合我自身的情况，我并没有完整的苹果生态，我的主力笔记本是 Linux Mint，我的主力手机是 Android，我也并没有在 iOS 生态上花过钱，反而是在 Play Store 中买过很多应用，包括我想着可能在电子墨水屏上会很好用的 moon reader pro。所以最后还是选择了开放生态系统的 Boox . 并且还知道它可以支持 Google Play Store.

而选择 Boox 机型的过程也是经过了一番考虑，Boox 的机型数量非常庞大，覆盖了 7 寸到 13 寸所有常见尺寸。首先我肯定不会选择 7 存的机型了，因为我已经有 Kindle，在阅读 mobi, epub 格式的文件的时候并不会有任何的问题，再者 13 寸，我觉得有点大，虽然还是看到很多人非常喜欢 Max 的超大屏幕，但是我还是忍住了，一是价格，二是便携程度。

![boox history](/assets/boox-history.png)

### Size

参数          | Note Pro           | Note 2          | iPad Pro
--------------|--------------------|-----------------|-----------
处理器 		  | 1.6GHz 4 核处理器 | Qualcomm Octa-core 2.0 GHz 8 core A53 processor | A12X
内存          | 4G   | 4G  | 4G
存储          | 64G  | 64G | 64G 起不同
重量          | 325g | 378g  | 469g
厚度          | 6.8mm | 7.1mm | 5.9mm
系统          | Android 6.0 | Android 9.0 | iOS
屏幕          | 10.3 | 10.3 | iOS
分辨率        | 10.3 | 1872*1404(227PPI)| 2388*1668(264PPI)
电池          | 4100  | 4300 毫安|
接口          | Type-C| Type-C | Type-C


## First impression
等商家即来已经是第三天，拿到手拆开包装，第一感觉就是大，相比较 Kindle，可显示面积大太多了，10.3 寸确实是阅读 PDF 的最佳尺寸了。开机进入界面非常简洁，我的 Boox Note2 开机后甚至什么书籍内容都没有，侧边几个选择清晰的表明了几大功能，快速浏览了一遍设置，更新一下固件，修改一下休眠时间，设置 PIN 和指纹，开启 Google Play Store，登录 Google 账号同步一切都非常满意。

然后就是连上 USB 快速的导入了几本测试书籍。

## Boox Note Pro 开启 Google Play {#google-play}
倒没有我想象得麻烦，直接在设置中开启，认证之后就能够直接使用了，如果登录失败，重启一次就成功了。

## Font
Oreader 路径，本地存储 fonts 文件夹。

Onyx Neo Reader : 路径 `adobe/resources/fonts` 放入 TTF 文件


## Dictionary
系统自带字典文件，指定目录是：`sdcard\dicts\xxx`，每个字典都以文件夹形式保存。

最多支持同时查阅 5 本字典。

支持的字典格式：stardict\bgl\mdict 等格式。


## Wifi 传书
同一局域网中，可以使用浏览器访问 Boox 中显示的地址。默认的存储路径为 `\WifiTransfer`

推送图书，推送网址：<http://send2boox.com>，支持 Onyx 账号绑定多个设备，支持单文件 200M 以内推送。

## Tips
使用过程中感觉需要总结的一些使用小技巧，对于一些显而易见的技巧就不在多说，比如手写笔上中间加入的擦除按钮，稍微使用一下就知道使用方式。这里主要总结一些不看说明可能摸索不出来的小技巧。

### Screenshot
截图是一个说常用也不是很常用，但是要用起来不得不用的一个功能。我们都知道 Android 的截图快捷键是电源键加音量下键，但是 Boox 并没有音量键，所以 Boox 学习了 Kindle 的做法，**同时按下屏幕左上角和右下角**，这时屏幕就会出现截屏选项，保存分享都随意了。截图文件会存放在存储空间的 `Screenshots` 目录下。

### App Freezer
Boox 使用 Android 系统，优点是开放，可以一下子拥抱 Android 世界许许多多的优质应用，但是缺点也是有些应用会滥用权限，无形中消耗电量，所以 Boox 在应用界面加入了应用冻结，可以将不常用的应用冻结起来。和我平时用的 icebox 有些相似。

### Go back to HOME
Android 上返回到桌面是比较常见的操作，而在 Boox 回到桌面有这样几种方式：

- 用实体按键
- 双击 navigation ball
- 或者在任何应用内返回，退出

### Custom Note Template
Note2 的笔记应用已经自带很多笔记模板，但是你也可以自定义笔记模板，只要将模板图片放到根目录下 `/noteTemplate` 即可。

## 一些可用的应用

### 阅读类
阅读任何格式，自带的阅读器就能够满足，当然如果追求 PDF 裁边，重排可以试试 KOReader

- KOReader <https://github.com/koreader/koreader>
- Moon Reader Pro 很早就买了，Android 上唯一阅读器

其他应用，比如微信读书，多看，掌阅，网易蜗牛，kindle，不过个人倒是不是很喜欢在 Boox 上用这些为手机而设计的应用。

### 漫画
平时不怎么看漫画，不过这几个似乎不错：

- 快看漫画
- 漫画人
- 哔哩哔哩漫画

另外很多人用电子墨水屏来看新闻，我是觉得非常不妥的，任何带滑动列表的应用都是不推荐的。

## reference

- <http://bbs.onyx-international.com/>