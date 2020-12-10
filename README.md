# <div align=center>每日优秀文章推荐</div>

### ⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️

### 作者会每天推荐一篇优秀文章给大家
### 每天会不定时更新，以下文章均是平时累计 转载请联系文章原作者。
### 麻烦给小编一颗🌟，让小编更有动力总结出更多优秀文章和作品。

### ⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️
标签：
-------

【==规范==】【==定义==】【==语法==】

-------

【==基础知识==】【==基础控件==】

-------

【==小常识==】【==时间==】【==颜色==】【==二维码==】【==地图==】【==网络==】【==相册==】【==定时器==】【==推送==】【==模拟器==】

-------

【==动画==】【==性能==】【==多线程==】【==安全==】【==算法==】【==视频==】【==绘制==】 【==支付==】【==逆向==】【==优化==】【==测试==】

-------

【==架构==】【==框架==】【==三方框架==】

-------

【==开发模式==】【==混编==】【==开发==】【==版本管理==】【==服务器==】

-------

【==审核==】 【==推广==】

-------

<br>
<br>
<br>


## <div align=center>2020/12/10</div>
* iOS warning 警告禁用与启用[点击前往](https://www.jianshu.com/p/cbd1f2e52542)【==优化==】
    ```
    1、code will never be executed
    -Wno-unreachable-code   全局禁用警告
    -Wunreachable-code      全局启用警告
    .
    2、Unused Entity Issue / unused function 'xxxxx'
    -Wno-unused-function    全局禁用
    -Wunused-function       全局启用
    ```

* Pointer is missing a nullability type specifier[点击前往](https://www.jianshu.com/p/a95ebd6befc9)【==优化==】
    ```
    NS_ASSUME_NONNULL_BEGIN
    NS_ASSUME_NONNULL_END
    ```

* Xcode 忽略第三方库的警告[点击前往](https://www.shiqidu.com/d/820)【==优化==】
    ```
    Pods -> target -> Other Warning Flags 添加 -w
    ```
    
* Suppressing deprecated warnings in Xcode[点击前往](https://stackoverflow.com/questions/2622017/suppressing-deprecated-warnings-in-xcode)【==优化==】
    ```
    Try -Wno-deprecated-declarations, 
    or its corresponding setting in Xcode, 
    GCC_WARN_ABOUT_DEPRECATED_FUNCTIONS 
    (pro tip: just type in "deprecated" in the build settings to find the specific setting for this warning).
   
   
    Deprecated Functions  -- NO
    ```

* “This function declaration is not a prototype” warning in Xcode 9[点击前往](https://stackoverflow.com/questions/44473146/this-function-declaration-is-not-a-prototype-warning-in-xcode-9)【==优化==】
    ```
    void (^)(void)
    ```

* 消除xcode8中Empty paragraph passed to '***' command的警告[点击前往](https://blog.csdn.net/studying_ios/article/details/53840996)【==优化==】
    ![](https://img-blog.csdn.net/20161223160455763?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvc3R1ZHlpbmdfaW9z/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)


* Double-quoted include "pb.h" in framework header, expected angle-bracke[点击前往](https://stackoverflow.com/questions/63951540/googledatatransport-is-throwing-double-quoted-include-in-framework-header-expect)【==优化==】
    ```
    quoted include -- No
    ```
    
* “View Controller“ is unreachable because it has no entry points[点击前往](https://medium.com/彼得潘的-swift-ios-app-開發問題解答集/view-controller-is-unreachable-because-it-has-no-entry-points-8149f8cca8eb)【==优化==】
    ```
    設定 Storyboard ID
    或者
    删除没有使用的controller
    ```
    
* 去除烦人的第三方引用库警告[点击前往](https://www.jianshu.com/p/6c2233dc92c3)【==优化==】
    ![](https://upload-images.jianshu.io/upload_images/10899155-137b589f3feb1903.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200)

<br>
<br>
<br>

## <div align=center>2020/12/8</div>
* iOS单元测试和集成测试[点击前往](https://www.jishudog.com/20853/html)【==测试==】
  
    ```
    单元测试和集成测试
    Unit: 单元测试，保证每一个类能够正常工作
    UI: UI测试，也叫做集成测试，从业务层的角度保证各个业务可以正常工作。
    ```

<br>
* XCTAssert单元测试[点击前往](https://blog.csdn.net/u010130947/article/details/47320083)【==测试==】
* iOS测试各个断言用法[点击前往](https://www.jianshu.com/p/560656589757)【==测试==】
<br>

* 经验教程 I iOS单元测试[点击前往](https://baijiahao.baidu.com/s?id=1665935755164300616&wfr=spider&for=pc)【==测试==】

* iOS单元测试从入门到应用（长文）[点击前往](https://www.jianshu.com/p/9707ff30e567)【==测试==】

* iOS-单元测试[点击前往](https://blog.csdn.net/samuelandkevin/article/details/104947613)【==测试==】
    * iOS进阶之单元测试 [视频链接](https://www.bilibili.com/video/av46726217/)

* iOS 单元测试[点击前往](https://chars.tech/blog/ios-unit-test/)【==测试==】

    `单元测试（unit testing），是指对软件中的最小可测试单元进行检查和验证。对于单元测试中单元的含义，一般来说，要根据实际情况去判定其具体含义，如 C 语言中单元指一个函数，Java 里单元指一个类，图形化的软件中可以指一个窗口或一个菜单等。总的来说，单元就是人为规定的最小的被测功能模块。`
    
* iOS 单元测试[点击前往](https://juejin.cn/post/6844903618793963534)【==测试==】

* ios自动化测试（xcode自带的UI测试）[点击前往](https://www.jianshu.com/p/877f2a1dcabc)【==测试==】

<br>
<br>
<br>

## <div align=center>2020/10/27</div>
* iOS 性能优化实践：头条抖音如何实现 OOM 崩溃率下降50%+[点击前往](https://juejin.im/post/6885144933997494280)【==优化==】

* 抖音品质建设 - iOS启动优化《原理篇》[点击前往](https://juejin.im/post/6887741815529832456)【==优化==】

* 网易云音乐 iOS 14 小组件实战手册[点击前往](https://juejin.im/post/6887759096506744840)【==基础控件==】
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/7b524e1281824d8a9b51146e23170963~tplv-k3u1fbpfcp-zoom-1.image)
    
<br>
<br>
<br>

## <div align=center>2020/10/12</div>
* iOS14 Widget小组件开发实践1——了解Widget[点击前往](https://www.jianshu.com/p/55dce7a524f5)【==基础控件==】

* iOS(Swift)通过极光推送实现跳转自定义页面[点击前往](https://izumi.pub/ios/622/)【==推送==】

* 极光推送iOS SDk集成指南[点击前往](https://docs.jiguang.cn/jpush/client/iOS/ios_guide_new/)【==推送==】

<br>
<br>
<br>


## <div align=center>2020/08/27</div>
* 一天精通iOS Swift多线程（GCD）[点击前往](https://juejin.im/post/6858126631760986126)【==多线程==】

* Flutter - 混合开发[点击前往](https://juejin.im/post/6850418111096324103)【==混编==】

* Rickey-iOS-Notes[点击前往](https://github.com/RickeyBoy/Rickey-iOS-Notes)【==小常识==】

<br>
<br>
<br>

## <div align=center>2020/08/17</div>
* 保姆级教程，如何发现 GitHub 上的优质项目[点击前往](https://juejin.im/post/6854818587808464910)【==小常识==】

* GitHub 统计卡片[点击前往](https://github.com/anuraghazra/github-readme-stats/blob/master/docs/readme_cn.md)【==小常识==】


* 如何访问/var/mobile/Containers/Data/Application...这样的文件夹[点击前往](https://www.jianshu.com/p/14fea5f91f92)【==小常识==】

* R.swift 运行失败 xcode Cycle inside xxx; building could produce unreliable results. 错误解决 xcode10[点击前往](https://www.jianshu.com/p/b2931d7b916f)【==小常识==】


* 编程范式：命令式编程(Imperative)、声明式编程(Declarative)和函数式编程(Functional)[点击前往](https://www.cnblogs.com/sirkevin/p/8283110.html)【==小常识==】


<br>
<br>
<br>

## <div align=center>2020/07/03</div>
* iTerm2 + Oh My Zsh 打造舒适终端体验[点击前往](https://www.jianshu.com/p/9c3439cc3bdb)【==小常识==】

* iOS界面调试工具Reveal4 配置[点击前往](https://www.jianshu.com/p/25f6d16627e1)【==小常识==】

* iOS比优鸡调试技巧篇（一）：reveal视图调试[点击前往](https://jakciehoo.github.io/2016/09/12/2016-09-12-using-reveal-to-debug/)【==小常识==】

* Dart vs Swift[点击前往](https://juejin.im/post/5c506a7c51882525c71333d2)【==开发模式==】
    ![](https://user-gold-cdn.xitu.io/2019/1/29/1689a21b2d263a75?imageView2/1/w/1304/h/734/q/85/interlace/1)
    
    ```
    强烈推荐，很好的学习swift和dart语法。
    避免将两门语言的语法搞混。
    ```

<br>
<br>
<br>

## <div align=center>2020/06/30</div>
* iOS Protocol 详解[点击前往](https://juejin.im/entry/58806914128fe1006c205041)【==基础知识==】

    `Protocol（协议）的声明看起来类似一个类的接口，不同的是Protocol没有父类也不能定义实例变量。Protocol是一种特殊的程序设计结构，用于声明专门被别的类实现的方法。因为OC是单继承的，由于不支持多继承，所以很多时候都是用Protocol和Category来代替实现多继承。Protocol只能定义公用的一套接口，但不能提供具体的实现方法。也就是说，它只告诉你要做什么，但具体怎么做，它不关心。`
    
    `Protocol的基本用途：
    （1）可以用来声明一大堆方法（不能声明成员变量）
    （2）只要某个类遵守了这个协议，就相当于拥有这个协议中的所有方法声明
    （3）只要父类遵守了某个协议，就相当于子类也遵守了
    （4）和java中的接口很相似，但比接口功能更丰富`

* R.swift的使用和安装[点击前往](https://www.jianshu.com/p/78508ed5739a)【==三方框架==】
* R.swift:以一种优雅安全的方式使用资源文件[点击前往](http://www.cocoachina.com/articles/14525)【==三方框架==】

* iOS逆向工程——获取app素材图片[点击前往](https://blog.csdn.net/a411358606/article/details/52179422)【==逆向==】

<br>
<br>
<br>

## <div align=center>2020/06/28</div>
* Xcode 实用快捷键（持续更新）[点击前往](https://juejin.im/post/5ef2a3f06fb9a0586e268724)【==小常识==】

    `文件方法:  command + shift + o
    选中自动对齐:  control + i
    当前文件栈 前进｜后退:  command + ctrl + ➡️ ｜ ⬅️
    切当前页面的兄弟页面 ｜ 方法:  control + 5 ｜ 6
    到文件目录:  command + shfit + J
    `
    
    
* iOS | 多态的实际运用[点击前往](https://juejin.im/entry/5c20fdf95188256ec35ff89c)【==基础知识==】

    `子类重写父类的方法，父类指针指向子类。`


* iOS中的设计模式——工厂模式(Factory)[点击前往](http://ibloodline.com/articles/2016/09/06/factory.html)【==基础知识==】

    `简单工厂模式:
    通过工厂类根据参数负责创建具体的产品，即工厂类在工厂方法中通过对参数进行条件判断(if、switch)来创建不同的实例)。
    `
    
    `抽象工厂模式:
    抽象工厂模式：提供了创建一系列相关抽象子类的接口，而无需指定它们具体的类型。也叫做Kit模式。
    `

<br>
<br>
<br>

## <div align=center>2020/06/23</div>
* iOS-类方法与实例方法[点击前往](https://www.jianshu.com/p/8248468ef54f)【==基础知识==】
    * 动态方法/实例方法
    
        `1).标识符：— 类开头
        2).调用方式：(实例对象    函数)
        3).实例方法在堆栈上。
        `
        
    * 静态方法/类方法
    
        `1).标识符:+ 类开头
        2).调用方式:(类    函数)
        3).静态方法在堆上分配内存。
        `
        
* iOS静态方法与动态方法[点击前往](https://blog.csdn.net/luozhiwei_iOS/article/details/48573425)【==基础知识==】

    `两者的差异包括：
    （1）方法列表是区分开的，分别存储在类对象与元类中。
    （2）动态方法是在运行期中调用，编译器无法检测错误，静态方法是在编译器就确定，编译器能检测错误。
    （3）动态方法由对象调用，静态方法由类调用，因为调用方法是通过isa和super指针实现的。因此对象只能调用类对象的方法，而类对像能调用元类的方法。
    `

* iOS 类方法与实例方法总结[点击前往](https://blog.csdn.net/luozhiwei_iOS/article/details/48573425)【==基础知识==】

    `类方法，也称静态方法，在C++中指的是用static关键字修饰的方法，而在OC里就是+方法，在Swift里是class func。`
    
    `实例方法，在C++中指的是不用static关键字修饰的方法，OC中是-方法，Swift中就是普通的func。`


<br>
<br>
<br>

## <div align=center>2020/06/12</div>
* JSPatch 平台介绍[点击前往](https://jspatch.com/Docs/intro)【==审核==】

      `JSPatch 是一个开源项目(Github链接)，只需要在项目里引入极小的引擎文件，就可以使用 JavaScript 调用任何 Objective-C 的原生接口，替换任意 Objective-C 原生方法。目前主要用于下发 JS 脚本替换原生 Objective-C 代码，实时修复线上 bug。`

* iOS WKWebView+UITableView混排[点击前往](https://juejin.im/post/5ed999fd51882542f9389949)【==性能==】

* 前端电商 sku 的全排列算法很难吗？学会这个套路，彻底掌握排列组合。[点击前往](https://juejin.im/post/5ee6d9026fb9a047e60815f1)【==算法==】

    ```
    let names = ["iPhone X", "iPhone XS"]
    
    let colors = ["黑色", "白色"]
    
    let storages = ["64g", "256g"]
    
    let combine = function (...chunks) {
      let res = []
    
      let helper = function (chunkIndex, prev) {
        let chunk = chunks[chunkIndex]
        let isLast = chunkIndex === chunks.length - 1
        for (let val of chunk) {
          let cur = prev.concat(val)
          if (isLast) {
            // 如果已经处理到数组的最后一项了 则把拼接的结果放入返回值中
            res.push(cur)
          } else {
            helper(chunkIndex + 1, cur)
          }
        }
      }
    
      // 从属性数组下标为 0 开始处理
      // 并且此时的 prev 是个空数组
      helper(0, [])
    
      return res
    }
    
    console.log(combine(names, colors, storages))
    ```

<br>
<br>
<br>

## <div align=center>2020/06/12</div>
* Swift Combine[点击前往](https://www.jianshu.com/p/df8535b40079)【==基础知识==】 
    
    `Combine是Apple在2019年WWDC上推出的一个新框架。该框架提供了一个声明性的Swift API，用于随时间处理值。这些值可以表示多种异步事件。`

* MVVM with Combine Tutorial for iOS[点击前往](https://www.jianshu.com/p/79e5fcf82446)【==基础知识==】 
    
    `本教程将介绍如何使用 Combine + SwiftUI + MVVM架构模式 来构建一个简单的天气App。`
    
* ios building for ios simulator, but the linked framework ''xxxx" was built for ios 解决[点击前往](https://www.jianshu.com/p/fe75ae11da9a)【==小常识==】

    `在xcode中选择File->WorkSpace Settings->Build System 选择 Legacy Build System 就可以编译通过啦。`

<br>
<br>
<br>

## <div align=center>2020/06/12</div>
* iOS内存缓存和磁盘缓存的区别[点击前往](https://www.jianshu.com/p/3b0e290cc049)【==基础知识==】 
    `缓存分为内存缓存和磁盘缓存两种，其中内存是指当前程序的运行空间，缓存速度快容量小，是临时存储文件用的，供CPU直接读取，比如说打开一个程序,他是在内存中存储,关闭程序后内存就又回到原来的空闲空间；磁盘是程序的存储空间，缓存容量大速度慢可持久化与内存不同的是磁盘是永久存储东西的，只要里面存放东西,不管运行不运行 ，他都占用空间！磁盘缓存是存在Library/Caches。`
    
<br>
    
* iOS NSSetUncaughtExceptionHandler[点击前往](https://www.jianshu.com/p/3b0e290cc049)【==优化==】
    `Foundation里面提供了一个NSSetUncaughtExceptionHandler函数，可以设置一个顶层异常处理函数，让我们在程序发生异常并终止前，有最后的机会来捕获并输出异常信息`
  
* ios Crash闪退日志获取和上传至服务器（NSSetUncaughtExceptionHandler）[点击前往](https://blog.csdn.net/folish_audi/article/details/36001629)【==优化==】

* iOS监听signal捕捉崩溃[点击前往](https://www.jianshu.com/p/579a8597cf95)【==优化==】

* [iOS]使用signal让app能够在从容崩溃[点击前往](https://www.cnblogs.com/daxiaxiaohao/p/4466097.html)【==优化==】

* Baymax：网易iOS App运行时Crash自动防护实践[点击前往](https://mp.weixin.qq.com/s?__biz=MzUxMzcxMzE5Ng==&mid=2247488311&idx=1&sn=0db090c8d4a5efafa47f00af4b3f174f&source=41&key=136c1b77805d77d5e3fc94f9961e1208e8a1c83f09dd489c62c8423767471a4467f741bbfcd082aa746c107aa7d6d3567ba344fad24ef9d9310961495da22364a024d6bff7ac263ff476828ae770bea4&ascene=0&uin=MTY2Nzc0OTY4MQ%3D%3D&devicetype=iMac+MacBookPro11%2C4+OSX+OSX+10.13.6+build(17G65)&version=12010210&nettype=WIFI&lang=zh_CN&fontScale=100&pass_ticket=PZLiwk2GvlCCMNT7WmjU3s5ly58yCkcbEJvLmX4klJnlEF5y1QmU0ldTSZypp8SM)【==优化==】

    `当然目前系统的功能并没有强大到可以把所有的crash都处理掉，不过一些常见的高频次发生的crash，系统均会针对他们一一处理。目前可以处理掉的crash类型具体有以下几种：
    1.unrecognized selector crash
    2.KVO crash
    3.NSNotification crash
    4.NSTimer crash
    5.Container crash（数组越界，插nil等）
    6.NSString crash （字符串操作的crash）
    7.Bad Access crash （野指针）
    8.UI not on Main Thread Crash (非主线程刷UI(机制待改善))
    对于每种类型的crash，安全系统都采取不同的方式，进行了对应的处理。`

<br>
<br>
<br>

## <div align=center>2020/06/11</div>
* 苹果强制要求更换启动方式的解决方案[点击前往](https://mp.weixin.qq.com/s/mdReGqt5E7T8VWC2q7ImKw)【==审核==】 

    `苹果要求：2020年June 30之前必须将启动方式通过storyboard进行加载。具体参考官方文档(https://developer.apple.com/news/?id=03262020b)。`

* 苹果审核上报[点击前往](https://juejin.im/post/5edafe106fb9a047dd275cc5)【==审核==】 

    `为了能够更好的过审，需要能全面监控苹果审核人员的操作，记录下来，并通过机器人接口上报钉钉群。`

* iOS定义静态变量、静态常量、全局变量[点击前往](https://www.jianshu.com/p/aec2e85b9e84)【==基础知识==】

* iOS 静态、全局变量、常量[点击前往](https://www.jianshu.com/p/7fafc3157432)【==基础知识==】

* 浅谈iOS开发中static变量的三大作用[点击前往](https://www.jb51.net/article/108393.htm)【==基础知识==】

<br>
<br>
<br>

## <div align=center>2020/06/05</div>
* 让iOS 开发更便捷-JSONConverter[点击前往](https://www.jianshu.com/p/cc604d8b1f7a)【==小常识==】

    `JSONConverter是MAC上iOS开发的辅助小工具，可以快速的把json数据转换生成对应的模型类属性，目前支持Objective-C、Swift以及目前流行的第三方库: SwiftyJSON、HandyJSON，ObjectMapper,可以灵活选择构建class/struct，并支持配置类名前缀等,省去手敲模型的麻烦，借此提高我们的开发效率。`
    
* 在JSONConverter的基础上调整后的工具JsonModel👍[点击前往](https://github.com/iOShuyang/JsonModel)【==小常识==】  
<br>

* 学习 Swift Moya（一）[点击前往](https://www.jianshu.com/p/265343901b79)【==框架==】 
* 学习 Swift Moya（二）- Moya + SwiftyJSON + RxSwift[点击前往](https://www.jianshu.com/p/aba7aed61afd)【==框架==】 

* RxSwift、Alamofire、Moya和HandyJson的结合使用[点击前往](https://blog.csdn.net/LuodeCoding/article/details/106519567)【==框架==】 

<br>
<br>
<br>

## <div align=center>2020/06/03</div>
* iOS 单元测试（Unit Test 和 UI Test）[点击前往](https://www.jianshu.com/p/84ffc4f11042)【==基础知识==】
* Xcode:为你的项目集成单元测试(unit tests)时记得避开这些坑[点击前往](https://www.jianshu.com/p/d15a7dea0c5a)【==基础知识==】
<br>

* iOS 13 SceneDelegate适配[点击前往](https://blog.csdn.net/weixin_38735568/article/details/101266408)【==基础知识==】
* iOS App生命周期及AppDelegate、SceneDelegate[点击前往](https://www.cnblogs.com/Jamwong/p/12347288.html)【==基础知识==】
* 如何删除SceneDelegate[点击前往](https://blog.csdn.net/weixin_43864837/article/details/104232482)【==基础知识==】


<br>
<br>
<br>

## <div align=center>2020/05/28</div>
* Swift中消失的main函数[点击前往](https://a1049145827.github.io/2018/03/22/Swift%E4%B8%AD%E6%B6%88%E5%A4%B1%E7%9A%84main%E5%87%BD%E6%95%B0/)【==小常识==】

* 你真的会用 CocoaPods 吗？[点击前往](https://juejin.im/post/59f2c7eaf265da432c2318e5)【==小常识==】


* 优雅的使用UITableView（OC 上）[点击前往](https://juejin.im/post/5a348a9b6fb9a0451a7672bb)【==规范==】

* 优雅的使用UITableView（Swift 中）[点击前往](https://juejin.im/post/5a64509cf265da3e36415bd3)【==规范==】

<br>
<br>
<br>


## <div align=center>2020/05/26</div>
* iOS启动速度优化总结[点击前往](https://blog.csdn.net/u013602835/article/details/96429977)【==优化==】

* 阿里数据iOS端启动速度优化的一些经验[点击前往](http://www.cocoachina.com/articles/22120)【==优化==】

* 今日头条iOS客户端启动速度优化[点击前往](https://www.jianshu.com/p/7096478ccbe7)【==优化==】

* 我是如何让微博绿洲的启动速度提升30%的[点击前往](https://juejin.im/post/5ea79839f265da7bba509590)【==优化==】

* 我是如何让微博绿洲的启动速度提升30%的(二)[点击前往](https://juejin.im/post/5eab84566fb9a043445a8529)【==优化==】

* 抖音研发实践：基于二进制文件重排的解决方案 APP启动速度提升超15%[点击前往](https://mp.weixin.qq.com/s/Drmmx5JtjG3UtTFksL6Q8Q)【==优化==】



<br>
<br>
<br>

## <div align=center>2020/05/22</div>
* podfile中 use_frameworks! 和 #use_frameworks!区别[点击前往](https://www.jianshu.com/p/ac629a1cb8f5)【==小常识==】

* ZFJObsLib-iOS代码混淆工具-马甲包混淆工具（Python脚本混淆iOS工程）[点击前往](https://zfj1128.blog.csdn.net/article/details/95482006)【==审核==】

* pod install速度慢，pod repo update 速度慢解决方法 [点击前往](https://www.cnblogs.com/jys509/p/12016226.html)【==小常识==】
    ```
    打开终端
    输入export ALL_PROXY=socks5://127.0.0.1:1080
    再 pod install
    需要开一个终端输入一次有效
    ```
    
<br>
<br>
<br>

## <div align=center>2020/03/23</div>
* pod忽略引入库的所有警告[点击前往](https://blog.csdn.net/syzd451529064/article/details/100071299)【==小常识==】
<br>

* iOS项目技术还债之路《一》后台下载趟坑[点击前往](https://juejin.im/post/5cf7eb0351882576710e5c15)【==架构==】
* iOS项目技术还债之路《二》IAP掉单优化[点击前往](https://juejin.im/post/5df64beff265da33e97fcd2f)【==架构==】
<br>

* Swift集成微信登录[点击前往](https://www.jianshu.com/p/246937829c4e)【==审核==】
* 微信登陆接入(Android/IOS(swift)/Java后台)[点击前往](https://www.jianshu.com/p/c7cd6aad513e)【==审核==】
* 苹果登录集成 Sign in with Apple[点击前往](https://www.jianshu.com/p/15cf5c39e9d4)【==审核==】
* iOS 13-Sign In with Apple[点击前往](https://www.jianshu.com/p/e1284bd8c72a)【==审核==】
* Sign in with Apple[点击前往](https://www.jianshu.com/p/8e5b89f302af)【==审核==】
* 苹果登录集成 Sign in with Apple[点击前往](https://www.jianshu.com/p/15cf5c39e9d4)【==审核==】

<br>
<br>
<br>

## <div align=center>2019/12/31</div>
* Xcode 打包到蒲公英[点击前往](https://blog.csdn.net/zhangyingeiOS/article/details/93473543)【==小常识==】
* Xcode10+打包内测版苹果ipa并发布到蒲公英平台[点击前往](https://www.jianshu.com/p/d32c174c51ec)【==小常识==】
<br>

* iOS APP之间的跳转方式[点击前往](https://www.jianshu.com/p/5c77f6e5ef90)【==小常识==】
* iOS--两个APP之间的相互跳转[点击前往](https://www.jianshu.com/p/403d9e067b81)【==小常识==】
* iOS应用之间的跳转，看这篇就够了[点击前往](https://www.jianshu.com/p/6b746f95b568)【==小常识==】


<br>
<br>
<br>

## <div align=center>2019/12/31</div>
* iOS 13 适配要点总结[点击前往](https://juejin.im/post/5d8af88ef265da5b6e0a23ac)【==小常识==】

```
适配要求
根据官网的说法，2020年4月之后所有提交到 App Store 的 iPhone 和 iPad 应用必须使用 iOS 13 以上的 SDK 进行编译，并支持 iPhone Xs Max 或 12.9 寸 iPad Pro (3代) 及以后版本的全屏幕设计。

新特性适配
1. Dark Mode
2. Sign In with Apple

API 适配
1. 私有方法 KVC 可能导致崩溃
2. 推送的 deviceToken 获取到的格式发生变化
3. 模态视图的默认样式发生改变
4. UISearchBar 黑线处理导致崩溃
5. UITabBarButton 不同状态下结构不同
6. UINavigationBar 设置按钮边距导致崩溃
7. 子线程修改界面导致崩溃（相册首次授权回调必现）

方法弃用
1. UIWebView 将被禁止提交审核
2. 使用 UISearchDisplayController 导致崩溃
3. MPMoviePlayerController 被弃用

工程适配
1. 蓝牙权限字段更新导致崩溃以及提交审核失败
2. CNCopyCurrentNetworkInfo 使用要求更严格
3. LaunchImage 被弃用
4. UISegmentedControl 默认样式改变
5. Xcode 11 创建的工程在低版本设备上运行黑屏
6. 默认弹出样式打开的页面在 WKWebView 中获取照片崩溃

SDK 适配
1. 使用 @available 导致旧版本 Xcode 编译出错
```

* iOS导航栏之UINavigationController,UINavigationbar和UINavigationItem的关系[点击前往](https://www.jianshu.com/p/6803ead6df48)【==小常识==】

* iOS中使用blend改变图片颜色[点击前往](https://onevcat.com/2013/04/using-blending-in-ios/)【==绘制==】

<br>
<br>
<br> 

## <div align=center>2019/11/29</div>
* 在 iOS 里 100% 还原 Sketch 实现的阴影效果[点击前往](https://juejin.im/post/5dd4cd71f265da0bf80b5820)【==小常识==】

* iOS使用模拟器各种网络环境调试[点击前往](https://www.jianshu.com/p/cbaa06715b75)【==小常识==】

* iOS Universal Links实现微信内网页跳转至App的方案[点击前往](https://www.jianshu.com/p/704fc947a1d8)【==小常识==】

<br>
<br>
<br>

## <div align=center>2019/11/20</div>
* 理解RESTful架构[点击前往](https://www.ruanyifeng.com/blog/2011/09/restful.html)【==规范==】

* RESTful API 设计指南[点击前往](http://www.ruanyifeng.com/blog/2014/05/restful_api.html)【==规范==】

* RESTful API 最佳实践[点击前往](http://www.ruanyifeng.com/blog/2018/10/restful-api-best-practices.html)【==规范==】

<br>
<br>
<br>

## <div align=center>2019/11/13</div>
* iOS 13 适配要点总结[点击前往](https://juejin.im/post/5d8af88ef265da5b6e0a23ac)【==小常识==】

* post使用form-data和x-www-form-urlencoded的本质区别[点击前往](https://blog.csdn.net/u013827143/article/details/86222486)【==基础知识==】

* form-data、x-www-form-urlencoded、raw、binary的区别[点击前往](https://blog.csdn.net/ye1992/article/details/49998511)【==基础知识==】

<br>
<br>
<br>

## <div align=center>2019/10/08</div>
* iOS 使用模拟器模拟定位[点击前往](https://www.jianshu.com/p/c8e5badacd37)【==模拟器==】

* 史上最强、最详细无痕埋点方案[点击前往](http://www.cocoachina.com/articles/50070)【==架构==】


* iOS动画总结：UIKit动画和Core Animation[点击前往](https://www.jianshu.com/p/043e7ec7f3ef)【==动画==】
* iOS动画，从入门到放弃?[点击前往](https://www.jianshu.com/p/2fcc2a318925)【==动画==】

<br>
<br>
<br>


## <div align=center>2019/09/17</div>
`目前比较流行服务端框架主要有Vapor、Perfect、Kitura和Zewo`
* 阿里云[点击前往](https://www.aliyun.com/?spm=5176.12302674.fszjobuve.2.7f854e01auD8Yy)

* Mac下 Ubuntu 16.04 配置http、https[点击前往](https://www.jianshu.com/p/4a4af62efa35)【==服务器==】
* Swift + Perfect 开发你的服务器（初级版）[点击前往](https://www.jianshu.com/p/0531baaff867)【==服务器==】
* Swift + Perfect 开发你的服务器（中级版）[点击前往](https://www.jianshu.com/p/de9fe773ee86)【==服务器==】
* Swift + Perfect 开发你的服务器（高级版）[点击前往](https://www.jianshu.com/p/a63d23fc8614)【==服务器==】

<br>
<br>
<br>

## <div align=center>2019/08/14</div>
* contentful iOS SDK[点击前往](https://www.contentful.com/developers/docs/ios/tutorials/using-delivery-api-with-swift/)【==三方框架==】

    `Contentful希望通过将存储内容的位置与显示内容的方式分离的手段，解决目前存在的种种问题。在这种解决方案之下，开发人员可以通过应用程序接口（API）访问每段内容（如本文的标题）。事实上，在目前的现代网络环境大背景之下，对于开发人员来说，基于API的内容管理系统操作更简洁。同时，由于内容创建者能够在同一个存储库里编写和更改内容，所以他们能够随心所以地进行跨平台无缝修改。
    `

* 如何优雅地解决 Objective-C 不支持方法默认参数的问题[点击前往](https://juejin.im/post/5d4ff10f51882515084f55a3)【==基础知识==】

* 有赞移动 iOS 组件化（模块化）架构设计实践[点击前往](https://juejin.im/post/5d4136295188255d5861d0e4)【==基础知识==】

    `业务组件化（或者叫模块化）作为移动端应用架构的主流方式之一，近年来一直是业界积极探索和实践的方向。有赞移动团队自16年起也在不断尝试各种组件化方案，在有赞微信商城，有赞零售，有赞美业等多个应用中进行了实践。我们踩过一些坑，也收获了很多宝贵的经验，并沉淀出 iOS 相关框架 Bifrost (雷神里的彩虹桥)。在过程中我们深刻体会到“没有绝对正确的架构，只有最合适的架构”这句话的意义。很多通用方案只是组件化的冰山一角，实际落地过程中还有相当多的东西需要考量。
    `

<br>
<br>
<br>

## <div align=center>2019/08/06</div>
* 分析一个App需要的技术手段[点击前往](https://www.jianshu.com/p/7d4b96f69087)【==逆向==】


    ![](https://mmbiz.qpic.cn/mmbiz_png/rzprzksWzSgJFj1Ls4DT4nWwxhiblZjgnKjQqesTVNk1E9eBos1Gd35ymLK4jH6d7ZUz0f4Aicfh1mF0rh9ia7szw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)
    
    
* (强烈推荐)移动端音视频从零到上手[点击前往](https://juejin.im/post/5d29d884f265da1b971aa220)【==视频==】
    * 原理（采集-处理-编码-传输-解码-音视频同步）
    * 推流，拉流


* RoyalPay网关支付接口[点击前往](https://mpay.royalpay.com.au/docs/cn/#api-JSApi-WxJSAPIPay)【==支付==】
![](https://mpay.royalpay.com.au/docs/cn/img/RoyalPay_Gateway_choose_cn.jpg)


<br>
<br>
<br>

## <div align=center>2019/07/19</div>
* 使用Moya库,进行https证书校验[点击前往](https://www.jianshu.com/p/7d4b96f69087)【==网络==】

```
public func defaultAlamofireManager() -> Manager {
   let configuration = URLSessionConfiguration.default
   configuration.httpAdditionalHeaders = Alamofire.SessionManager.defaultHTTPHeaders
   //获取本地证书
   let path: String = Bundle.main.path(forResource: "证书名", ofType: "cer")!
   let certificateData = try? Data(contentsOf: URL(fileURLWithPath: path)) as CFData
   let certificate = SecCertificateCreateWithData(nil, certificateData!)
   let certificates :[SecCertificate] = [certificate!]
   
   let policies: [String: ServerTrustPolicy] = [
       "域名" : .pinCertificates(certificates: certificates, validateCertificateChain: true, validateHost: true)
   ]
   let manager = Alamofire.SessionManager(configuration: configuration,serverTrustPolicyManager: ServerTrustPolicyManager(policies: policies))
   return manager
}
//把defaultAlamofireManager当参数传进去就行了
let kProvider = MoyaProvider<APIManager>(endpointClosure: myEndpointClosure, requestClosure: requestClosure, manager:defaultAlamofireManager(), plugins: [networkPlugin], trackInflights: false)
```

* iOS：自签名证书 xxx.crt 转化成 xxx.cer 格式[点击前往](https://www.jianshu.com/p/128b0275eeea)【==网络==】

* iOS - Swift NSTimeZone	时区[点击前往](https://www.cnblogs.com/QianChia/p/5777449.html)【==小常识==】


<br>
<br>
<br>

## <div align=center>2019/06/10</div>
* ios 日期格式 日期转换[点击前往](https://blog.csdn.net/reylen/article/details/8028641)【==小常识==】
  
```iOS-NSDateFormatter 格式说明：
  
  G: 公元时代，例如AD公元
    yy: 年的后2位
    yyyy: 完整年
    MM: 月，显示为1-12
    MMM: 月，显示为英文月份简写,如 Jan
    MMMM: 月，显示为英文月份全称，如 Janualy
    dd: 日，2位数表示，如02
    d: 日，1-2位显示，如 2
    EEE: 简写星期几，如Sun
    EEEE: 全写星期几，如Sunday
    aa: 上下午，AM/PM
    H: 时，24小时制，0-23
    K：时，12小时制，0-11
    m: 分，1-2位
    mm: 分，2位
    s: 秒，1-2位
    ss: 秒，2位
    S: 毫秒

常用日期结构：
yyyy-MM-dd HH:mm:ss.SSS
yyyy-MM-dd HH:mm:ss
yyyy-MM-dd
MM dd yyyy
```

* 说说MVVM[点击前往](https://juejin.im/post/5ce5687de51d45109725fdd1)【==架构==】
`关于软件架构模式（确切的说是一种软件编码规范或者软件开发模式），这几年骂战不断。争论的焦点主要是在MVC、MVVM、MVP哪种架构最好，哪种架构才是最牛逼的、扩展性更强的、可维护性更高的。笔者不才，在实际项目中很少用过MVP架构，对于MVP的掌握也是只停留在写写Demo阶段。本篇文章主要着重介绍下MVVM架构在真实项目当中的应用，以及抛开RAC，我们如何自己动手写一个View和ViewModel之间的绑定框架。`


* iOS-OpenCV之蔡徐坤教你玩转边框画[点击前往](https://juejin.im/post/5cebb78451882512c54ca9f1)【==绘制==】


<br>
<br>
<br>

## <div align=center>2019/06/04</div>
* WWDC2019之SwiftUI[点击前往](https://juejin.im/post/5cf5f4596fb9a07ede0b2fa1)【==开发模式==】
 
    `SwiftUI只支持Xcode 11、iOS 13版本及以上。`
    
* Introducing SwiftUI[官网](https://developer.apple.com/tutorials/swiftui)【==开发模式==】
    ![](https://docs-assets.developer.apple.com/published/b7f464081b/d04c64b4-ca23-47b6-8701-7d1468760d7c.png)

* iOS13-适配夜间模式/深色外观(Dark Mode)[点击前往](https://juejin.im/post/5cf6276be51d455a68490b26)【==小常识==】


<br>
<br>
<br>

## <div align=center>2019/05/21</div>
* Flutter 接入 firebase 快速构建应用[点击前往](https://juejin.im/post/5c90514e6fb9a070c859029c)【==三方框架==】
     `
     Firebase 为后台开发提供以下几个功能
    1.实时数据库（Realtime database）
    2.用户认证（Authentication）
    3.自定义API（Cloud function）
    4.消息推送（Cloud messaging）
    5.静态网页Hosting
    6.云存储（Cloud storage）
    7.实时监控（Analytics）`
    
* 将 Firebase 添加到您的 Flutter 应用 [点击前往](https://firebase.google.cn/docs/flutter/setup?hl=zh-cn)【==三方框架==】 


* Flutter进阶—Firebase数据库实例 [点击前往](https://blog.csdn.net/hekaiyou/article/details/74990042)【==三方框架==】 

* firebase cloud message 使用 [点击前往](https://www.jianshu.com/p/db752f05db30)【==三方框架==】 

* Flutter – Firestore CRUD (Reading and writing data) [点击前往](https://tphangout.com/flutter-firestore-crud-reading-and-writing-data/)【==三方框架==】 

<br>
<br>
<br>

## <div align=center>2019/05/16</div>
* 关于iOS选取相册中iCloud云上图片和视频[点击前往](http://www.cnblogs.com/junhuawang/p/8034247.html)【==小常识==】

    `由于手机内存小，而用户又打开了相册同步iCloud，在这时，如果本地可用内存过小，会导致
    将本地相册中的图片或视频删除只留缩略图，如果App调用的时候想要选取这种图片就需要从iCloud云中进行下载，
    才能获取原图或原视频。`

* iOS iCloud入门  [点击前往](https://blog.csdn.net/u012265444/article/details/77714727)【==基础知识==】
   
    `1.1为应用开启iCloud服务
    1.2设置iCloud的数据
    1.3代码操作iCloud功能`

* iOS项目iCloud及CloudKit Dashboard运用  [点击前往](http://www.cnblogs.com/wujy/p/5971273.html)【==基础知识==】



* iOS开发-iCloud的简单使用（1）-配置iCloud环境以及key-value storage的使用  [点击前往](https://www.jianshu.com/p/c1373fb12ebc)【==基础知识==】
* iOS开发-iCloud的简单使用（2）-Documents数据的使用 [点击前往](https://www.jianshu.com/p/43186b39f9b0)【==基础知识==】
* iOS开发-iCloud的简单使用（3）-Cloud Kit的使用 [点击前往](https://www.jianshu.com/p/ddb8f4ff7ac3)【==基础知识==】

<br>
<br>
<br>

## <div align=center>2019/05/15</div>
```
Pusher Channels provides realtime communication between servers, apps and devices. Pusher Channels is used for notifications, chat, gaming, web-page updates, IoT, and many other systems requiring realtime communication.

When something happens in your system, it can update web-pages, apps and devices. When an event happens on an app, the app can notify all other apps and your system. For example, If the price of Bitcoin changes, your system could update the display of all open apps and web-pages. Or if Bob starts typing a message, his app could tell Alice’s app to display “Bob is typing …”.

Pusher Channels has libraries for everything: web browsers, iOS and Android apps, PHP frameworks, cloud functions, bash scripts, IoT devices. Pusher Channels works everywhere because it uses WebSockets and HTTP, and provides fallbacks for devices that don’t support WebSockets.
```

* [Pusher的CHANNELS](https://pusher.com/docs/channels)

* [Pusher的CHANNELS的github](https://github.com/pusher/pusher-websocket-swift#configuration)


```
Chatkit is designed to make it as simple as possible to add chat to your app. It lets you add 1-1 and group chat to your app, along with typing indicators, file attachments and storage, user online presence and a flexible permissions system.
```
* [Pusher的CHATKIT](https://pusher.com/docs/chatkit)

* [Pusher的CHATKIT的github](https://github.com/pusher/chatkit-swift#installation)


```
Beams makes it easy to send push notifications to iOS and Android apps. It takes the hassle out of managing device tokens and interacting with Apple and Google's messaging services. With Interest subscriptions to notify segmented devices in each request and delivery SLAs offered on premium plans, it's built to scale.
```
* [Pusher的BEAMS](https://pusher.com/docs/beams)


<br>
<br>
<br>

## <div align=center>2019/05/13</div>
* 学习并理解 23 种设计模式[点击前往](https://juejin.im/post/5c8756e6e51d456cda2e7ff1)【==基础知识==】
  
  `一.UML 类图
   二.六大原则
   三.模式分类
   四.创建型 - 设计模式
   五.结构型 - 设计模式
   六.行为型 - 设计模式
  `
  
* iOS app秒开H5优化总结[点击前往](https://juejin.im/post/5c9c664ff265da611624764d)【==小常识==】
  
  `离线包
   拦截并加载本地资源包
  `

* iOS 基础[点击前往](https://juejin.im/post/5c989fd15188252d5255f7f3)【==小常识==】


<br>
<br>
<br>

## <div align=center>2019/05/07</div>
`在项目实战当中遇到的问题`

* flutter环境搭建mac版[点击前往](https://segmentfault.com/a/1190000014845833)【==开发模式==】
  
  `1.系统环境要求
   2.下载flutter
   3.配置环境变量
   4.检查环境
   5.搭建环境常见问题整理
  `

* flutter APP 编译运行时报 package androidx && AAPT 、AAPT2 && parsing resources[点击前往](https://blog.csdn.net/julystroy/article/details/88793817)【==开发模式==】

     `This version of image_picker will break your Android build if it or its dependencies aren't compatible with Android`


* flutter错误解决--Error running Gradle 错误[点击前往](https://blog.csdn.net/mo911108/article/details/88603003)【==开发模式==】

    `在Debug项目的时候， 出现  Error running Gradle:一般是因为不能翻墙的原因`
    
    
* Flutter已有项目导入，没法启动Android模拟器的解决方法(iOS模拟器可以启动)[点击前往](https://juejin.im/post/5b5044d26fb9a04f9a5cd1a8)【==开发模式==】
   
   
* Flutter打包IPA报错Could not find an option named "track-widget-creation".[点击前往](https://blog.csdn.net/weixin_34306446/article/details/87538720)【==开发模式==】

     `在Xcode上进行archive之前先在终端运行以下命令行：
     进入项目目录
     $flutter build ios --release`

<br>
<br>
<br>

## <div align=center>2019/05/06</div>
* Firebase 初步使用教程[点击前往](https://www.jianshu.com/p/d5f3fa462515)【==三方框架==】

* Firebase 教程 —— 一个实时聊天室  [点击前往](https://www.jianshu.com/p/98eb3356593b)【==三方框架==】  
     
     `Firebase是一家实时后端数据库创业公司，它能帮助开发者很快的写出Web端和移动端的应用。自2014年10月Google收购Firebase以来，用户可以在更方便地使用Firebase的同时，结合Google的云服务。`
     
     `Firebase能让你的App从零到一。也就是说它可以帮助手机以及网页应用的开发者轻松构建App。通过Firebase背后负载的框架就可以简单地开发一个App，无需服务器以及基础设施。`
     ![](https://gss2.bdstatic.com/9fo3dSag_xI4khGkpoWK1HF6hhy/baike/c0%3Dbaike180%2C5%2C5%2C180%2C60/sign=14e1c399a76eddc432eabca958b2dd98/78310a55b319ebc4ad509be58826cffc1e1716a5.jpg)


* Mac下配置全局gradlew命令  [点击前往](https://www.cnblogs.com/huyang011/p/9758126.html)【==小常识==】



<br>
<br>
<br>

## <div align=center>2019/04/28</div>
* iOS Enabled 和 UserInteractionEnabled 的区别[点击前往](https://www.jianshu.com/p/6d9791541747)【==小常识==】

* iOS 录音、音频的拼接剪切以及边录边压缩转码[点击前往](https://www.jianshu.com/p/1a752b92070b)【==视频==】
   
    `总体内容
    1、录音实现
    2、录音的编辑 (拼接音频:可以设置多段，音频的剪切：按照时间段剪切)
    3、lame静态库进行压缩转码`
    
* 如何用好 github 中的 watch、star、fork[点击前往](https://www.jianshu.com/p/6c366b53ea41)【==小常识==】

* 自从升级到Xcode 10.2后，我无法再通过cli运行react-native run-ios[点击前往](https://cloud.tencent.com/developer/ask/210512)【==小常识==】
    
    `此问题这两天一直困扰着我，请问有没有高手知道如何具体处理，按照此文章思路暂时未解决`

<br>
<br>
<br>

## <div align=center>2019/04/19</div>
* Xcode9 Swift4下编译Swift第三方框架时报错Swift compiler Error的解决方案[点击前往](https://www.jianshu.com/p/2c0e9c70b8ad)【==小常识==】

* iOS Xcode自定义代码块以及迁移[点击前往](http://www.cocoachina.com/ios/20190416/26821.html)【==小常识==】

* RunLoop实战：实时卡顿监控[点击前往](https://juejin.im/post/5cacb2baf265da03904bf93b)【==性能==】

<br>
<br>
<br>

## <div align=center>2019/03/29</div>
* iOS开发常用框架总览！[点击前往](http://www.cocoachina.com/ios/20190314/26565.html)【==基础知识==】

* Carthage 包管理工具[点击前往](https://blog.csdn.net/u012938194/article/details/52816350)【==基础知识==】

* iOS--关于时间格式“ISO 8601”标准转换问题：“2017-09-30T09:00:00”[点击前往](https://blog.csdn.net/weixin_34379433/article/details/86898441)【==小常识==】

* iOS中解析ISO 8601格式的时间[点击前往](https://blog.csdn.net/weixin_34379433/article/details/86898441)【==小常识==】

* iOS WKWebView与JS交互 [点击前往](https://www.jianshu.com/p/4d12d593ba60)【==基础控件==】


<br>
<br>
<br>

## <div align=center>2019/03/29</div>
![](https://raw.githubusercontent.com/iOShuyang/Book-Save-PhotoAlbum/master/164fb2a8c8db84df.png)
* Flutter 完整开发实战详解(一、Dart 语言和 Flutter 基础)[点击前往](https://juejin.im/post/5b631d326fb9a04fce524db2)【==开发模式==】

* Flutter 完整开发实战详解(二、快速实战篇)[点击前往](https://juejin.im/post/5b685a2a5188251ac22b71c0)【==开发模式==】

* Flutter 完整开发实战详解(三、打包填坑篇)[点击前往](https://juejin.im/post/5b6fd4dc6fb9a0099e711162)【==开发模式==】

* Flutter 完整开发实战详解(四、Redux、主题、国际化)[点击前往](https://juejin.im/post/5b79767ff265da435450a873)【==开发模式==】

* Flutter 完整开发实战详解(五、深入探索)[点击前往](https://juejin.im/post/5bc450dff265da0a951f032b)【==开发模式==】

* Flutter 完整开发实战详解(六、 深入Widget原理)[点击前往](https://juejin.im/post/5c7e853151882549664b0543)【==开发模式==】

* Flutter 完整开发实战详解(七、 深入布局原理)[点击前往](https://juejin.im/post/5c8c6ef7e51d450ba7233f51)【==开发模式==】

* Flutter完整开发实战详解(八、 实用技巧与填坑)[点击前往](https://www.jianshu.com/p/8117fbc5b4d3)【==开发模式==】

* Flutter完整开发实战详解(九、 深入绘制原理)[点击前往](https://www.jianshu.com/p/d7693c47a70e)【==开发模式==】

* Flutter完整开发实战详解(十、 深入图片加载流程)[点击前往](https://www.jianshu.com/p/d3c94d01bd3f)【==开发模式==】

<br>
<br>
<br>

## <div align=center>2019/03/27</div>

* iOS 如何查找app在模拟器下的文件[点击前往](https://www.jianshu.com/p/a1e3e526a997)<br>[翻墙点击前往](https://stackoverflow.com/questions/6480607/is-there-any-way-to-see-the-file-system-on-the-ios-simulator)【==小常识==】

* Navicat Premium 12.1.18 强大的数据库管理工具[点击前往](https://xclient.info/s/navicat-premium.html#versions)

<br>
<br>
<br>

## <div align=center>2019/03/26</div>

* Swift5 新特性预览 [点击前往](http://www.cocoachina.com/ios/20180510/23345.html)【==基础知识==】

* Dart Packages[点击前往](https://pub.dartlang.org)【==开发模式==】

* flutter常用插件[点击前往](https://www.jianshu.com/p/028b9d4c65e3)【==开发模式==】

* Flutter 一些常用库[点击前往](https://www.cnblogs.com/yangyxd/p/9232308.html)【==开发模式==】

* Flutter部分插件 后续持续更新～[点击前往](https://www.jianshu.com/p/c78ef5cf7f6a)【==开发模式==】

<br>
<br>
<br>

## <div align=center>2019/03/25</div>
![](https://www.vixverify.com/assets/uploads/2016/08/verification-ID2-600x476.jpg)
* [身份验证Green ID](https://www.vixverify.com/greenid-services/verification-of-identity/)

* [IOS GreenID SDK](https://vixverify.atlassian.net/wiki/spaces/GREEN/pages/63746413/IOS+GreenID+SDK+GIDResources.bundle+Configuration.)

<br>
<br>
<br>

## <div align=center>2019/03/22</div>
![](https://user-gold-cdn.xitu.io/2019/1/20/1686a75118251a47?imageslim)

* Flutter学习之入门和体验[点击前往](https://juejin.im/post/5c443681f265da613a544bca)【==开发模式==】

* Flutter学习之Dart语法特性[点击前往](https://juejin.im/post/5c44727df265da611c274087)【==开发模式==】

* Flutter学习之认知基础组件[点击前往](https://juejin.im/post/5c5c1f21e51d457fcc5a9f9f)【==开发模式==】

* Flutter学习之布局、交互、动画[点击前往](https://juejin.im/post/5c617e34f265da2d90581613)【==开发模式==】

* Flutter学习之事件循环机制、数据库、网络请求[点击前往](https://juejin.im/post/5c698a606fb9a049d81c63df)【==开发模式==】

<br>
<br>
<br>

## <div align=center>2019/03/11</div>
* Flutter 即学即用系列博客——04 Flutter UI 初窥[点击前往](https://juejin.im/post/5c862d15f265da2da67c65d4)【==开发模式==】

* Flutter开发之Dart语法基础[点击前往](https://juejin.im/post/5c6ba76551882562ea7233a3)【==开发模式==】

* Flutter开发之Dart的数据类型01[点击前往](https://juejin.im/post/5c6cbd7651882523f026608c)【==开发模式==】

* Flutter开发之Dart的数据类型02[点击前往](https://juejin.im/post/5c788a7cf265da2d8b635742)【==开发模式==】


<br>
<br>
<br>

## <div align=center>2019/03/01</div>
* Why flutter, how to flutter?[点击前往](https://www.jianshu.com/p/a1344cfea21d)【==开发模式==】

* flutter基础-看完这篇就可以撸app了[点击前往](http://www.cocoachina.com/ios/20180612/23765.html)【==开发模式==】

* Flutter知乎App实践：UI+Json+Utils[点击前往](https://juejin.im/post/5c5014a6518825260d7ef89a)【==开发模式==】

* Flutter调试技巧总结——高效开发的秘密[点击前往](https://juejin.im/post/5bb9b8a75188255c791b1984)【==开发模式==】

<br>
<br>
<br>

## <div align=center>2019/02/28</div>
* Flutter中文网[点击前往](https://flutterchina.club/get-started/codelab/)【==开发模式==】

* React Native中文网[点击前往](https://reactnative.cn/docs/next/getting-started/)【==开发模式==】

* flutter的一个强大的特性就是其炫酷霸气的UI库，官方传送门 Material-UI库[点击前往](https://v0.material-ui.com/#/)【==开发模式==】

<br>
<br>
<br>

## <div align=center>2019/02/27</div>
* 从零讲解 iOS 中 OpenGL ES 的纹理渲染[点击前往](https://juejin.im/post/5c74b06bf265da2d90584313)【==绘制==】


* iOS原生级别后台下载详解[点击前往](https://juejin.im/post/5c4ed0b0e51d4511dc730799)【==网络==】


* TikTok(抖音国际版)逆向，全球的小姐姐们，我来啦！[点击前往](https://juejin.im/post/5c19a38ae51d453e0a209256)【==逆向==】
    * `iOS逆向工程指的是软件层面上进行逆向分析的过程。
在一般的软件开发流程中，都是过程导向结果。在逆向中，你首先拿到的是结果，然后是去分析实现这个结果的过程。理清过程之后，才开始进行逆向的代码编写，在整个流程中，分析过程的占比是90%，代码书写的过程只占10%。所以本篇更多的讲的是一个思路，代码其实很日常`

<br>
<br>
<br>

## <div align=center>2019/02/21</div>
* iOS中常见Crash总结[点击前往](https://juejin.im/post/5c617b85e51d45015e0475ac)【==小常识==】
    * 
```
 1、找不到方法的实现unrecognized selector sent to instance
找不到方法的实现unrecognized selector sent to instance
 2、KVC造成的crash
 3、EXC_BAD_ACCESS
 4、KVO引起的崩溃
 5、集合类相关崩溃
 6、多线程中的崩溃
 7、Socket长连接，进入后台没有关闭
 8、Watch Dog超时造成的crash
 9、后台返回NSNull导致的崩溃，多见于Java做后台服务器开发语言
```

* AppDelegate的模块化+瘦身[点击前往](https://juejin.im/post/5c62caf6e51d457fc905dd75)【==小常识==】

* 关于Socket，看我这几篇就够了(三)原来你是这样的Websocket[点击前往](https://juejin.im/post/5c60e31251882562cf29bdb5)【==基础知识==】

* iOS国际化（多语言）漫谈[点击前往](https://juejin.im/post/5c64cdd2e51d45015b4ca8aa)【==基础知识==】

<br>
<br>
<br>



## <div align=center>2019/02/20</div>
* 丧心病狂的Github技巧[点击前往](https://www.jianshu.com/p/758e8bd48308)【==基础知识==】

* Flutter试用报告[点击前往](https://juejin.im/post/5c64cc2d518825626b76d7a5)【==开发模式==】

* 来一次有侧重点的区分Swift与Objective-C[点击前往](https://juejin.im/post/5c653aa6e51d457fbf5dc298)【==基础知识==】

<br>
<br>
<br>

## <div align=center>2019/02/19</div>
* 搞iOS的，面试官问Hash干嘛？原因远比我下面要介绍的多[点击前往](https://juejin.im/post/5c6abfc86fb9a049c04396a7)【==基础知识==】

    ![](https://user-gold-cdn.xitu.io/2019/2/18/16900fde7fec739e?imageslim)

* [译] 用这些 iOS 技巧让你的 APP 性能更佳[点击前往](https://juejin.im/post/5c6a0b6ef265da2de660f83f)【==小常识==】
    * `简要概括: 良好的性能对于提供良好的用户体验至关重要，iOS 用户通常对其应用程序抱有很高的期望。缓慢且无响应的应用可能会让用户放弃使用你的应用，或者更糟糕的是，对应用留下差评。
    虽然现代 iOS 硬件功能十分强大，足以处理许多密集和复杂的任务，但是如果你不关心你的 APP 是怎么执行的话，用户的设备仍会出现无响应的情况。在本文中，我们将研究五种优化技巧，使你的 APP 更流畅。`

* iOS 本地图片优化实践[点击前往](https://juejin.im/post/5c6826656fb9a049dc02c958)【==小常识==】
    * `删除无用图片、去重复、压缩、分析、网络下载、Xcode 配置`

<br>
<br>
<br>


## <div align=center>2019/02/18</div>
* 怎么让self.view的Y从navigationBar下面开始计算[点击前往](https://www.jianshu.com/p/c9fdf8086435)【==小常识==】

* iOS 开发工具 - Swift VS Objective-C[点击前往](https://www.jianshu.com/p/cdd049ef1c3e)【==混编==】

* iOS 了解Xcode Bitcode[点击前往](https://www.jianshu.com/p/4fa8168e2892)【==小常识==】

<br>
<br>
<br>

## <div align=center>2019/01/26</div>

![](https://www.tradingview.com/x/8GpeJWJz/)
* [TradingView](https://cn.tradingview.com/publishing-tools/)是股票、期货和外汇市场里的交易者和投资者社交网络! 图表库附带 API 以显示您自己的数据。 可定制且易于安装。


* [序言· tradingView开发文档](https://zlq4863947.gitbooks.io/tradingview/book/Package-Content.html)

* [github上的demo](https://github.com/tradingview/charting-library-examples)

* [24小时精通TradingView开发教学视频](https://space.bilibili.com/19853384?spm_id_from=333.788.b_765f7570696e666f.1)

* [TradingView + WebSocket 实时推送 K 线脱坑指南](https://juejin.im/post/5bb1f22151882557305835f8?utm_medium=hao.caibaojian.com&utm_source=hao.caibaojian.com)

<br>
<br>
<br>

## <div align=center>2019/01/22</div>
![](https://raw.githubusercontent.com/iOShuyang/Save_PhotoAlbum/master/屏幕快照%202019-01-22%20下午4.12.59.png)
* 集成[身份管理和认证平台Auth0](https://auth0.com/)

* [Auth0登录后的Dashboard](https://manage.auth0.com/#/)

* [Auth0集成文档](https://auth0.com/docs/quickstart/native/ios-swift)

* [Auth0的GitHub上的demo](https://github.com/auth0/Auth0.swift)

* [Auth0的Lock for iOS v2 Style Customization ](https://auth0.com/docs/libraries/lock-ios/v2/customization)

<br>
<br>
<br>


## <div align=center>2019/01/21</div>
* ios开发——解决UICollectionView的cell间距与设置不符问题[点击前往](https://blog.csdn.net/u013604612/article/details/41450167)【==小常识==】

* UICollectionView中Cell左对齐 居中 右对齐 等间距------你想要的，这里都有[点击前往](https://www.cnblogs.com/liangyi-cn/p/7520387.html)【==小常识==】


* 使用水平和垂直滑动的UICollectionView来制作粘性的行和列[点击前往](https://www.jianshu.com/p/a0089f2db49e)【==小常识==】
![](https://upload-images.jianshu.io/upload_images/318204-d52b7b752f79a9e0.gif?imageMogr2/auto-orient/strip%7CimageView2/2/w/312)

<br>
<br>
<br>

## <div align=center>2019/01/17</div>
* UICollectionViewCell「居左显示」[点击前往](https://www.jianshu.com/p/d8297960d797)【==小常识==】

* ios 设置导航器navigationItem.titleView无效问题记录[点击前往](https://www.jianshu.com/p/a377377ba3db)【==小常识==】

    `只有在push进导航器的vc或者是作为导航器 rootViewController的vc才能够修改titleView.由于tabbar继承于UIViewController,且为导航器的rootViewController,所以如果要修改titleView只能够在tabbarView中去实现,在tabbar里面的vc去设置是不会出现效果的.`

* iOS12远程推送新特性[点击前往](https://www.jianshu.com/p/6175911ad14d)【==推送==】

 `新特性
Grouped notifications 推送分组
Provisional authorization 临时授权
Notification management 推送消息的管理
Critical alerts 警告性质的推送
Notification content extensions 推送内容扩展中的可交互和动态更改Action`

* iOS 链式编程一行代码完成屏幕适配[点击前往](https://www.jianshu.com/p/292e5c8185e9)【==小常识==】

<br>
<br>
<br>

## <div align=center>2019/01/16</div>
* iOS后台模式开发指南[点击前往](http://www.codeceo.com/article/ios-background-guide.html)【==小常识==】

    `每一次iOS的发布都会在后台操作和细节上的放宽限制，以此提升用户体验和延长电池寿命.对于在iOS中实现”真正”的多任务来说,后台模式不是一个神奇的解决办法.当用户切换到其他的APP应用时,大多数的APP应用仍然会完全的暂停运行.你的应用只被允许在很特殊的情况下才能在后台中继续运行.例如,这些包括播放音频,获取位置更新,或者从服务器获取最新内容的情况.`
    
* warning: templates not found /usr/local/git/share/git-core/templates[点击前往](https://blog.csdn.net/qq_15602525/article/details/70802589)【==小常识==】

* CAEmitterLayer 粒子动画[点击前往](http://www.cocoachina.com/ios/20190110/26093.html)【==动画==】
 ![](https://upload-images.jianshu.io/upload_images/1680733-2061ece5f61b6c73.gif?imageMogr2/auto-orient/strip%7CimageView2/2/w/341/format/webp)
 
 * iOS 按时间给 model 数组排序[点击前往](https://www.jianshu.com/p/bb83975a244a)【==小常识==】

* Flutter实战详解--高仿好奇心日报[点击前往](https://juejin.im/post/5c31f7236fb9a04a04412d0b)【==开发模式==】

<br>
<br>
<br>

## <div align=center>2019/01/11</div>
![](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1547485151617&di=4ffae9b59bc4552919c1fe9d1a3c2f0c&imgtype=0&src=http%3A%2F%2Fww1.sinaimg.cn%2Fcrop.0.0.889.499.1000.562%2Fe9475adegw1f8myfsfftqj20p00dwaa7.jpg)
* iOS马甲包混淆必过4.3审核上线解决方案[点击前往](https://zhuanlan.zhihu.com/p/38481422)【==审核==】

* 苹果又被拒了：Guideline 4.3 - Design[点击前往](https://blog.csdn.net/quantum7/article/details/81195660?utm_source=blogxgwz6)【==审核==】

* iOS4.3马甲包审核被拒和解决方法、[点击前往](https://www.jianshu.com/p/d7cea95bf899)【==审核==】

* Guideline 4.2.2 - Design - Minimum Functionality 被拒及解决方法[点击前往](https://blog.csdn.net/qq_31810357/article/details/84654401)【==审核==】

<br>
<br>
<br>

## <div align=center>2019/01/10</div>
* 高德地图绘制面官方文档[点击前往](https://lbs.amap.com/api/ios-sdk/guide/draw-on-map/draw-plane)【==地图==】

* 热力图 热图 地图 图层覆盖物（dingsoung的代码）[点击前往](http://code.cocoachina.com/u/316271)【==地图==】

* iOS 原生地图MKMapView上添加图片遮盖物[点击前往](https://www.jianshu.com/p/ae11b3dd3486)【==地图==】

* 地图：MapKit的简单使用——MKOverlay[点击前往](https://blog.csdn.net/c13232906050/article/details/47168741)【==地图==】

* MKMapView 位置与地图(三)给地图添加覆盖层[点击前往](https://blog.csdn.net/hmt20130412/article/details/36009093)【==地图==】

<br>
<br>
<br>


## <div align=center>2019/01/09</div>
* CocoaPods 都做了什么？[点击前往](https://mp.weixin.qq.com/s?__biz=MzA5NzMwODI0MA==&mid=2647761981&idx=1&sn=49d0dd19bdb79bf3797756c646aef4ca&chksm=8887df02bff05614bdd422ff39833c9f2c5708ca9861922b968bc97604f59e7aa0d2e1967717&scene=21#wechat_redirect)【==小常识==】

* 使用 Metal 和 Core ML 评价照片质量[点击前往](https://mp.weixin.qq.com/s?__biz=MzA5NzMwODI0MA==&mid=2647761989&idx=1&sn=f9e5cbbaea284a44789e7a6f47c269b6&chksm=8887df7abff0566c1936600e032208201a07f2c53e9b66657ff53bff087a330361f754a3efa5&scene=21#wechat_redirect)【==框架==】


<br>
<br>
<br>

## <div align=center>2019/01/08</div>
* 😊GitHub可免费创建无限量私人储存库

    ![](http://t11.baidu.com/it/u=3027523945,746257153&fm=173&app=49&f=JPEG?w=636&h=394&s=24F0E53201907DCA02E5DCDA000070B1)

* [git lfs](https://git-lfs.github.com)

`Git LFS（Large File Storage, 大文件存储）是可以把音乐、图片、视频等指定的任意文件存在 Git 仓库之外，而在 Git 仓库中用一个占用空间 1KB 不到的文本指针来代替的小工具。通过把大文件存储在 Git 仓库之外，可以减小 Git 仓库本身的体积，使克隆 Git 仓库的速度加快，也使得 Git 不会因为仓库中充满大文件而损失性能。`

* 处理 github 不允许上传超过 100MB 文件的问题[点击前往](http://www.liuxiao.org/2017/02/git-处理-github-不允许上传超过-100mb-文件的问题/)【==小常识==】

* 上传超过100M的文件到github[点击前往](https://www.jianshu.com/p/f8339c74fbe3)【==小常识==】

## <div align=center>2019/01/07</div>
* 获取网络图片的大小[点击前往](http://www.cocoachina.com/ios/20181210/25770.html)【==小常识==】

* 网络请求优化之取消请求[点击前往](https://juejin.im/post/5c04fb896fb9a04a016413b0)【==网络==】
`页面返回的时候，将网络请求取消 
同一个请求多次请求时，短时间忽略相同的请求 
同一个请求多次请求时，取消之前发出的请求 
发送的请求，多次尝试并确保成功`

* 初级程序员需要知道的基本代码规范[点击前往](http://www.cocoachina.com/ios/20181203/25675.html)【==规范==】

<br>
<br>
<br>

## <div align=center>2019/01/03</div>
* Apple TV 编程指南--介绍[点击前往](http://www.cocoachina.com/ios/20151120/14335.html)【==框架==】

    `tv OS 开发由 iOS 开发衍生而来但又有所不同,包括 tv OS 特有的一些框架。你会发现 Apple TV 的开发跟 iOS 开发很相似，它结合了支持分享技术、多用户体验，并且开辟了你在 iOS 设备上没有发现的app开发领域的空间。你可以创建新的APP也可以使用 iOS 代码作为起点。无论是哪种开发，你使用的都是熟悉的工具（Xcode）、语言（Objective-C,Swift以及JavaScript）。`

* TVOS tips[点击前往](https://justsee.iteye.com/blog/2329380)【==框架==】

* tvOS 开发第一个tvOS应用[点击前往](https://blog.csdn.net/u012265444/article/details/80045561)【==框架==】

* 苹果电视 tvOS UI设计规范总结 （五）图标和图像[点击前往](https://www.ui.cn/detail/205793.html)【==框架==】

* iOS仿滴滴预约用车时间选择器[点击前往](https://www.jianshu.com/p/ca60479a6ce0)【==时间==】

<br>
<br>
<br>

## <div align=center>2019/01/02</div>
* [Charts的github](https://github.com/danielgindi/Charts)

* iOS使用Charts框架绘制—柱形图[点击前往](https://www.jianshu.com/p/5f777671e9e4)【==三方框架==】
![](https://upload-images.jianshu.io/upload_images/1803339-5c0f985eec02e11a.gif?imageMogr2/auto-orient/strip%7CimageView2/2/w/315)

* iOS BarChartView的使用，Charts版本3.2.1[点击前往](https://www.jianshu.com/p/85d8ecd95c14)【==三方框架==】


* 学会使用Objective-C中的block[点击前往](https://www.jianshu.com/p/d911cd16c100)【==基础知识==】

    `Apple从OS X 10.4和iOS 4以后开始支持block，相对于delegate，block有很多便捷之处，使得代码更简洁，可读性更强。但是如果使用不当，则会造成很多问题。本文结合自己的经验和《Pro Multithreading and Memory Management for iOS and OS X: with ARC, Grand Central Dispatch, and Blocks》书中的知识点，介绍block的相关知识点。`

<br>
<br>
<br>

## <div align=center>2019/01/01</div>
* iOS 基于PhotoKit框架的自定义相册[点击前往](http://www.cocoachina.com/ios/20181221/25915.html)【==相册==】

    `之前公司的项目需要自定义相册，并且需要获取图片的经纬度信息，使用UIImagePickerController自然是实现不了的。所以就用到了我们今天所说的PhotoKit框架，因为PhotoKit是iOS8之后出的，所以iOS8以前的项目是不能使用的（可以使用AssetsLibrary，这里就不多介绍了）。`

* UITableView性能优化-中级篇[点击前往](http://www.cocoachina.com/ios/20181218/25843.html)【==性能==】

    `最近遇到一个需求，对tableView有中级优化需求
    要求 tableView 滚动的时候,滚动到哪行，哪行的图片才加载并显示,滚动过程中图片不加载显示;
    页面跳转的时候，取消当前页面的图片加载请求；`

* 新手也看得懂的 iOS Runtime 教程[点击前往](http://www.cocoachina.com/ios/20181213/25821.html)【==基础知识==】

     `在 C 语言中，将代码转换为可执行程序，一般要经历三个步骤，即编译、链接、运行。在链接的时候，对象的类型、方法的实现就已经确定好了。
     而在 Objective-C 中，却将一些在编译和链接过程中的工作，放到了运行阶段。也就是说，就算是一个编译好的 .ipa 包，在程序没运行的时候，也不知道调用一个方法会发生什么。这也为后来大行其道的「热修复」提供了可能。因此我们称 Objective-C 为一门动态语言。
     这样的设计使 Objective-C 变得灵活，甚至可以让我们在程序运行的时候，去动态修改一个方法的实现。而实现这一切的基础就是 Runtime 。
     简单来说， Runtime 是一个库，这个库使我们可以在程序运行时创建对象、检查对象，修改类和对象的方法。`

<br>
<br>
<br>

## <div align=center>2018/12/27</div>
* 最火移动端跨平台方案盘点：React Native、weex、Flutter[点击前往](https://baijiahao.baidu.com/s?id=1608650340331187704&wfr=spider&for=pc)【==开发模式==】
    
    `1）react native、weex均使用JavaScript作为编程语言，目前JavaScript在跨平台开发中，可谓占据半壁江山，大有“一统天下”的趋势；`
    
    `2）kotlin-native开始支持 iOS 和 Web 开发，（kotlin已经成为android的一级语言）也想尝试“一统天下”；`
    
    `3）flutter是Google跨平台移动UI框架，Dart作为谷歌的亲儿子，毫无疑问Dart成为flutter的编程语言。作为巨头新生儿，在flutter官网也可以看出，flutter同样“心怀天下”（可支持Web端、Android端、iOS端等）。`
    
* Apple Pay--iOS开发  [点击前往](https://www.jianshu.com/p/807a730135ca)【==支付==】
     `Apple Pay，简单来说, 就是一种移动支付方式。通过Touch ID/ Passcode，用户可使用存储在iPhone 6, 6p等设备上的信用卡和借记卡支付证书来授权支付； 它是苹果公司在2014苹果秋季新品发布会上发布的一种基于NFC的手机支付功能，于2014年10月20日在美国正式上线，2016年2月18日凌晨5：00， Apple Pay 业务在中国上线。`
     
* iOS 使用模拟器模拟定位  [点击前往](https://www.jianshu.com/p/c8e5badacd37)【==小常识==】 

<br>
<br>
<br>

## <div align=center>2018/12/25</div>

* Google 地图官方文档[点击前往](https://developers.google.com/maps/documentation/ios-sdk/utility/heatmap#add_a_simple_heatmap)【==地图==】

* Google 地图github[点击前往](https://github.com/googlemaps?utf8=%E2%9C%93&q=&type=&language=objective-c)

* iOS 接入谷歌地图[点击前往](https://www.jianshu.com/p/60ea3a19e661)【==地图==】
    
* iOS GMSMap(谷歌地图） 地图下载和初级使用[点击前往](https://www.jianshu.com/p/cc919aadaa60)【==地图==】
    
* iOS Google地图开发小结(2017)[点击前往](https://www.jianshu.com/p/7c1293ee83ff)【==地图==】
    
* Google map生成热力图[点击前往](https://www.jianshu.com/p/f1c33ebd891b)【==地图==】

<br>
<br>
<br>

## <div align=center>2018/12/24</div>
`是一家提供让个人或公司在互联网上接受付款服务的科技公司。Stripe提供在网上接受付款所需的技术、避免信用卡诈骗技术及银行基础设施`
* Stripe 官方集成文档[点击前往](https://stripe.com/docs/mobile/ios/custom)【==支付==】

* Stripe使用指南：Swift开发中的信用卡支付[点击前往](https://baiyunpeng.com/?p=693)【==支付==】

* iOS oc版Stripe支付[点击前往](https://www.jianshu.com/p/29e5cf6de6e7)【==支付==】


<br>
<br>
<br>

## <div align=center>2018/12/21</div>
* 项目需求(此项目需要科学上网)
![](https://raw.githubusercontent.com/iOShuyang/Save_PhotoAlbum/master/屏幕快照%202018-12-21%20上午11.51.52.png)

* [Google Analytics](https://analytics.google.com/analytics/web/#/report-home/a131142122w190749662p186858962)是著名互联网公司Google为网站提供的数据统计服务。可以对目标网站进行访问数据统计和分析，并提供多种参数供网站拥有者使用。

* [Real Time Reporting API](https://developers.google.cn/analytics/devguides/reporting/realtime/v3/)获取目前发生在媒体资源上的用户活动。实时报告每隔数秒钟就会更新，让您构建实时信息中心，监控任一时刻有多少用户正在与您的媒体资源互动。

* [Google API 控制台](https://console.developers.google.com/apis/dashboard?project=vaulted-dolphin-226105)Google 会提供您稍后需要用到的信息，例如客户端 ID 和客户端密钥。

* [Google APIs Client Library for Objective-C for REST](https://github.com/google/google-api-objectivec-client-for-rest)该库由Google编写，是一个灵活高效的Objective-C框架，用于访问JSON API。

* [Introduction to the Google APIs Client Library for Objective-C for REST](https://github.com/google/google-api-objectivec-client-for-rest/wiki)客户端库简介以及集成流程

<br>
<br>
<br>

## <div align=center>2018/12/19</div>
* ios lable中电话号码点击拨打电话 [点击前往](https://blog.csdn.net/feifeiwuxian/article/details/78595393)【==小常识==】
    
```
#pragma mark-<获取电话号码的坐标>
+ (CGRect)boundingRectForCharacterRange:(NSRange)range andLable:(UILabel *)lable lableSize:(CGSize)lableSize{
//    NSMutableAttributedString *attributeString = [[NSMutableAttributedString alloc] initWithString:contentStr];
//    NSMutableParagraphStyle *paraStyle = [[NSMutableParagraphStyle alloc] init];
//    paraStyle.lineSpacing = 6;
//    NSDictionary *attrs =@{NSFontAttributeName : [UIFont systemFontOfSize:12.0], NSParagraphStyleAttributeName : paraStyle};
//    [attributeString setAttributes:attrs range:NSMakeRange(0, contentStr.length)];
    
    NSTextStorage *textStorage = [[NSTextStorage alloc] initWithAttributedString:lable.attributedText];
    NSLayoutManager *layoutManager = [[NSLayoutManager alloc] init];
    [textStorage addLayoutManager:layoutManager];
    NSTextContainer *textContainer = [[NSTextContainer alloc] initWithSize:lableSize];
    textContainer.lineFragmentPadding = 0;
    [layoutManager addTextContainer:textContainer];
    
    NSRange glyphRange;
    
    [layoutManager characterRangeForGlyphRange:range actualGlyphRange:&glyphRange];
    
    CGRect rect = [layoutManager boundingRectForGlyphRange:glyphRange inTextContainer:textContainer];
//    CGFloat yOfset =  rect.origin.y;
//    rect.origin.y = yOfset + 3;
    
    return rect;
}
```

* iOS 识别文字中的手机号码高亮显示点击可拨打电话 [点击前往](https://www.aliyun.com/jiaocheng/360135.html)【==小常识==】

<br>
<br>
<br>

## <div align=center>2018/12/18</div>
* ios文字转语音后台（转，待验证）[点击前往](https://www.jianshu.com/p/5e773bcf13d6)【==框架==】

* iOS端使用replaykit录制屏幕的技术细节[点击前往](https://www.jianshu.com/p/401b5b632d5b)【==框架==】

* UIBezierPath绘制柱状图、折线图和饼状图[点击前往](https://www.jianshu.com/p/e37493cf093e)【==绘制==】

<br>
<br>
<br>

## <div align=center>2018/12/17</div>
* delegate和protocol(区别)[点击前往](https://blog.csdn.net/mad1989/article/details/8463460)【==基础知识==】


* iOS开发经验总结[点击前往](https://www.jianshu.com/p/d333cf6ae4b0)【==小常识==】
* iOS开发经验总结2[点击前往](https://www.jianshu.com/p/3ed55c2c2515)【==小常识==】
* iOS开发经验总结3[点击前往](https://www.jianshu.com/p/8ea636c8c612)【==小常识==】

<br>
<br>
<br>

## <div align=center>2018/12/12</div>
* iOS开发编码建议与编程经验[点击前往](https://www.jianshu.com/p/f33634d1ab5e)【==小常识==】

    `在开发过程中，我们不仅要去看别人的代码，也要让别人看我们的代码。那么，有一个良好的编码习惯将会非常重要。下面将会罗列使用Objective-C来开发iOS的编码建议。`
       
* iOS应用间跳转[点击前往](https://www.jianshu.com/p/732c5e1720d0)【==小常识==】
 ![](https://upload-images.jianshu.io/upload_images/987457-e04fcf9fbd2d67dc.png?imageMogr2/auto-orient/)

* iOS通讯录介绍和使用[点击前往](https://www.jianshu.com/p/732c5e1720d0)【==小常识==】

 ![通讯录的介绍](https://upload-images.jianshu.io/upload_images/987457-0e3476d43388a95e.png?imageMogr2/auto-orient/)
 
 ![通讯录的使用](https://upload-images.jianshu.io/upload_images/987457-a99ced4897708c01.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1000)

<br>
<br>
<br>


## <div align=center>2018/12/11</div>
* ios新特性：自动填充用户名密码UIRemoteKeyboardWindow[点击前往](https://www.jianshu.com/p/85b9f2524211)【==小常识==】
     ![](https://upload-images.jianshu.io/upload_images/2048812-c65de2b84c07639e.png?imageMogr2/auto-orient/)
     
* swift -- 系统自带分享功能[点击前往](https://www.jianshu.com/p/85b9f2524211)【==小常识==】

    ```let textToShare = "百度"
        let imageToShare = UIImage.init(named: "img_01")
        let urlToShare = NSURL.init(string: "http://www.baidu.com")
        let items = [textToShare,imageToShare ?? "WeShare",urlToShare ?? "WeShare"] as [Any]
        let activityVC = UIActivityViewController(
            activityItems: items,
            applicationActivities: nil)
       activityVC.completionWithItemsHandler =  { activity, success, items, error in 
       }
        self.present(activityVC, animated: true, completion: { () -> Void in
        })
        ```



<br>
<br>
<br>

-------
## <div align=center>2018/12/10</div>
* iOS-收集的不常用却实用的小方法和技巧[点击前往](https://www.jianshu.com/p/a492eb6ad7fa)【==小常识==】
    1. 颜色转变成图片
    2. app评分跳转
    3. 获取当前系统语言环境
    4. 计算字符串的高度
    5. 强行关闭app的方法
    6. 如何快速的查看一段代码的执行时间
    7. 在使用view的缩放的时候，layer.border.width随着view的放大，会出现锯齿化的问题，解决这个问题需要设置这个属性。
    8. instrument中time profile 中的self, #self,%self各代表什么 ?
    9. 神器计算图片位置的函数：AVMakeRectWithAspectRatioInsideRect（）
    10. 关于 如果一个矩形如果做了平移旋转缩放等一系列操作之后，上下左右的四个点（甚至矩形上任意一个点）的位置。
    11. tableViewCell上的button,点击获取所在row
    12. 设置粘贴内容
    13. iPhone为了节省电力所以有一个自动休眠机制，如果想让我们的APP不自动进入休眠只需要设置 UIApplication的idleTimerDisabled 属性为 YES 即可。（切勿滥用）
    14. UIApplicationUserDidTakeScreenshotNotification通知，当用户截屏时触发

    
* iOS中书写代码规范35条小建议:[点击前往](https://www.jianshu.com/p/a492eb6ad7fa)【==规范==】


* iOS常用正则表达式[点击前往](https://www.jianshu.com/p/ea10003d224a)【==基础知识==】
    `又称正规表示法、常规表示法（英语：Regular Expression，在代码中常简写为regex、regexp或RE），计算机科学的一个概念。正则表达式使用单个字符串来描述、匹配一系列符合某个句法规则的字符串。在很多文本编辑器里，正则表达式通常被用来检索、替换那些符合某个模式的文本;`
    
<br>
<br>
<br>

-------
## <div align=center>2018/12/09</div>
* OC与swift的数据传输[点击前往](https://www.jianshu.com/p/451f452bf588)【==混编==】

    `
    1、swift之间的页面跳转与返回
    2、oc监听swift推送的通知
    3、swift内部推送接收的通知
    4、oc调用swift的代理方法
    5、swift调用oc代码块
    6、oc对swift的属性传值、方法调用、代码块调用
    7、swift对oc的属性传值、方法调用、代码块调用
    8、swift之间的传值`

* ARKit和CoreLocation：第一部分[点击前往](https://www.jianshu.com/p/60f27dc574fa)【==框架==】
    
    `第一部分将介绍ARKit的基础知识，从MapKit获取方向以及触摸矩阵变换的基础知识。在第二部分将讨论计算两个位置，以及如何利用位置数据，并变换成在ARKit场景的位置之间的轴承。`

<br>
<br>
<br>

-------
## <div align=center>2018/12/06</div>
`SwiftLint 是 Realm 推出的一款 Swift 代码规范检查工具，Realm 就不用介绍了，他们家推出的移动端跨平台数据库在业内的名气还是很大的，就算没有用过，相信大多数人也是听过的。
SwiftLint 基于 Github 公布的 Swift 代码规范进行代码检查，并且能够很好的和 Xcode 整合。配置好所有的设置之后，在 Xcode 中执行编译时，SwiftLint 会自动运行检查，不符合规范的代码会通过警告或者 error 的形式指示出来，并且拥有丰富的配置项，可以进行大量的自定义，相当方便。`

* Xcode 配置 Swift Lint 规范代码风格[点击前往](https://www.jianshu.com/p/86c56ebc590c)【==规范==】 
* SwiftLint，规范代码，成为完美的偏执患者[点击前往](https://www.jianshu.com/p/40aa8695503f)【==规范==】
* 使用 SwiftLint 进行 Swift 代码规范检查[点击前往](https://www.jianshu.com/p/c8337160fcd4)【==规范==】


<br>
<br>
<br>

-------
## <div align=center>2018/12/05</div>
* iOS中打开的文件如何用其他应用打开选择自己的app[点击前往](https://www.jianshu.com/p/a950b411a8e7)【==基础知识==】
    1. 设置 Info.plist
    2. 设置 AppDelegate
    3. 接收通知

* 使用UIDocumentInteractionController和QLPreviewController预览文件[点击前往](https://www.jianshu.com/p/73048dbe6a7d)【==基础知识==】

* iOS 调起第三方程序打开文件 ( UIDocumentInteractionController )[点击前往](https://blog.csdn.net/lg767201403/article/details/77185181)【==基础知识==】

* iOS开发打开word、excel、ppt、txt、pdf文档(可在线浏览)[点击前往](https://www.jianshu.com/p/4277a81c0798)【==基础知识==】


 `打开文件的方法：
1.获取文件的沙盒路径path
2.将path路径转化URL
3.用webView显示出来`

<br>
<br>
<br>

-------
## <div align=center>2018/12/04</div>
* GIT版本管理看这一篇就够了[点击前往](https://www.jianshu.com/p/0e9d07ec76f9)【==版本管理==】


    `GIT基本上是目前最为先进的分布式版本控制系统，通过GIT能够非常方便的管理文件多个版本，能够实现版本的回滚，比对等功能，并且支持分布式也就是多人协同工作。`
    1. init
    2. clone
    3. status
    4. add
    5. commit
    6. rm
    7. reset
    8. diff
    9. log
    10. tag
    11. branch
    12. checkout
    13. merge
    14. remote
    15. fetch
    16. pull
    17. push

* iOS开发经验总结[点击前往](https://www.jianshu.com/p/d333cf6ae4b0)【==小常识==】
    1. iPhone Size
    2. 给navigation Bar 设置 title 颜色
    3. 如何把一个CGPoint存入数组里
    4.  UIColor 获取 RGB 值
    5. 修改textField的placeholder的字体颜色、大小
    6. 两点之间的距离
    7. IOS开发－关闭/收起键盘方法总结
    8. 在使用 ImagesQA.xcassets 时需要注意
    9. UIPickerView 判断开始选择到选择结束
    10. iOS模拟器 键盘事件
    11. 在ios7上使用size classes后上面下面黑色
    12. 设置不同size在size classes
    13. 线程中更新 UILabel的text
    14. 使用UIScrollViewKeyboardDismissMode实现了Message app的行为
    15. 报错 "_sqlite3_bind_blob", referenced from:
    16. ios7 statusbar 文字颜色
    17. 获得当前硬盘空间
    18. 给UIView 设置透明度，不影响其他sub views
    19. 将color转为UIImage
    20. NSTimer 用法
    21. Bundle identifier 应用标示符
    22. NSDate 获取几年前的时间
    23. iOS加载启动图的时候隐藏statusbar
    24. iOS 开发，工程中混合使用 ARC 和非ARC
    25. iOS7 中 boundingRectWithSize:options:attributes:context:计算文本尺寸的使用
    26. NSDate使用 注意
    27. 在UIViewController中property的一个UIViewController的Present问题
    28. UITableViewCell indentationLevel 使用
    29. ActivityViewController 使用AirDrop分享
    30. 获取CGRect的height
    31. 打印 %
    32. 在工程中查看是否使用 IDFA
    33. APP 屏蔽 触发事件
    34. 设置Status bar颜色
    35. NSDictionary 转 NSString
    36. iOS7 中UIButton setImage 没有起作用
    37. User-Agent 判断设备
    38. UIPasteboard 屏蔽paste 选项
    39. class_addMethod 使用
    40. AFNetworking 传送 form-data
    41. 非空判断注意
    42. iOS 8.4 UIAlertView 键盘显示问题
    43. 模拟器中文输入法设置
    44. iPhone number pad
    45. UIView 自带动画翻转界面
    46. KVO 监听其他类的变量
    47. ios9 crash animateWithDuration
    48. 对NSString进行URL编码转换
    49. Xcode iOS加载图片只能用PNG
    50. 保存全屏为image
    51. 判断定位状态 locationServicesEnabled
    52. 微信分享的时候注意大小
    53. 图片缓存的清空
    54. TableView Header View 跟随Tableview 滚动
    55. TabBar的title 设置
    56. UITabBar,移除顶部的阴影
    57. 当一行中，多个UIKit 都是动态的宽度设置
    58. JSON的“<null>” 转换为nil

<br>
<br>
<br>

-------
## <div align=center>2018/12/03</div>
* iOS 代码注释[点击前往](https://www.jianshu.com/p/c44867b2c3f1)【==小常识==】


* OC-简单粗暴理解Block的本质[点击前往](https://www.jianshu.com/p/976fe9a3c9a1)【==基础知识==】


* iOS-weakSelf和strongSelf[点击前往](https://www.jianshu.com/p/ca094cb7ab28)【==基础知识==】

<br>
<br>
<br>

-------
## <div align=center>2018/11/29</div>
* iOS应用流畅度辨析[点击前往](https://www.jianshu.com/p/f4adce56166f)【==性能==】
    * 用 Instruments 来检验你的app
    
    `iOS界面处理是在主线程下进行的，系统图形服务通过 CADisplayLink 等机制通知 App，App 主线程开始在 CPU 中计算显示内容，比如视图的创建、布局计算、图片解码、文本绘制等。随后 CPU 会将计算好的内容提交到 GPU 去，由 GPU 进行变换、合成、渲染。随后 GPU 会把渲染结果提交到帧缓冲区去，等待下一次刷新信号到来时显示到屏幕上。显示器通常以固定频率进行刷新，如果在一个刷新时间内，CPU 或者 GPU 没有完成内容提交，则那一帧就会被丢弃，等待下一次机会再显示，而这时显示屏会保留之前的内容不变。这就是界面卡顿的原因。CPU 和 GPU 不论哪个阻碍了显示流程，都会造成掉帧现象。`
    
* 如何去除Xcode中的警告⚠️[点击前往](https://www.jianshu.com/p/e80bb47f0444)【==小常识==】

      `开发一个项目时，难免会产生很多无关紧要的警告，很多是第三方或是老代码不再被支持造成的，但并不影响使用，花大力气去解决警告也不合时宜，偷个懒，把一些隐藏掉吧！`
      
* iOS开发——Category在项目中的实际运用[点击前往](https://www.jianshu.com/p/8f2b173263f9)【==小常识==】
    1. 扩展类的方法
    2. 扩展类的属性（结合runtime）
    3. 在没有源代码的情况下可以用来修复BUG
    4. 整体替换
      

<br>
<br>
<br>

-------
## <div align=center>2018/11/28</div>
* iOS 如何防止https抓包(中间人攻击),及charles抓包原理[点击前往](https://www.jianshu.com/p/4682aecf162d?open_source=weibo_search)【==安全==】
      ![](https://upload-images.jianshu.io/upload_images/5505686-68a34f7acfa8ebf3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/825)
      
* iOS Charles 抓包指南 - 从入门到精通[点击前往](https://blog.csdn.net/u013538542/article/details/79107106)【==安全==】
    1. 安装 Charles
    2. 注册 License 
    3. 添加 SSL 配置 
    4. 配置手机代理 
    5. 安装 Charles 证书 

* [iOS]iOS中网络请求判断是否设置代理[点击前往](https://www.jianshu.com/p/c3b950dbf86a)【==安全==】 
        
    ```
    NSDictionary *proxySettings = (__bridge NSDictionary *(CFNetworkCopySystemProxySettings());
    
    NSArray *proxies = (__bridge NSArray *)(CFNetworkCopyProxiesForURL((__bridge CFURLRef _Nonnull)([NSURL URLWithString:@"http://www.baidu.com&quot;]), (__bridge CFDictionaryRef _Nonnull)(proxySettings)));
    NSLog(@"\n%@",proxies);
    
    NSDictionary *settings = proxies[0];
    NSLog(@"%@",[settings objectForKey:(NSString *)kCFProxyHostNameKey]);
    NSLog(@"%@",[settings objectForKey:(NSString *)kCFProxyPortNumberKey]);
    NSLog(@"%@",[settings objectForKey:(NSString *)kCFProxyTypeKey]);
    
    if ([[settings objectForKey:(NSString *)kCFProxyTypeKey] isEqualToString:@"kCFProxyTypeNone"])
    {
    NSLog(@"没代理");
    }
    else
    {
    NSLog(@"设置了代理");
    }
    ```

<br>
<br>
<br>

-------
## <div align=center>2018/11/27</div>
* UITableView/UICollectionView调用reloadData刷新时界面闪烁[点击前往](https://blog.csdn.net/potato512/article/details/78550125)【==小常识==】
    * 造成闪烁的原因，主要是因为CALayer有一个隐式动画，只要在调用reloadData刷新时，关闭隐式动画就可以避免了。代码示例如下：
    
    ``` 
    [CATransaction setDisableActions:YES];
    [self.collectionView reloadData];
    [CATransaction commit];
    ```
    
* Xcode 快速开发 代码块[点击前往](https://www.jianshu.com/p/76def4cbe39d)【==小常识==】
    * Xcode的代码片段(Code Snippets)创建自定义的代码片段，当你重用这些代码片段时，会给你带来很大的方便。

* Runtime的运用和减少应用崩溃[点击前往](https://www.jianshu.com/p/35971a7e8bf6)【==基础知识==】
    * Objective-C 是一个动态语言，它需要一个运行时系统来动态的创建类和对象、进行消息传递和转发。

<br>
<br>
<br>

-------
## <div align=center>2018/11/26</div>
* iOS图片设置圆角性能优化[点击前往](https://www.cnblogs.com/junhuawang/p/5652220.html)【==性能==】
    * 第一种:设置CALayer的cornerRadius
    
    `注意：ios9.0之后对UIImageView的圆角设置做了优化，UIImageView这样设置圆角
不会触发离屏渲染，ios9.0之前还是会触发离屏渲染。而UIButton还是都会触发离屏渲染。`
    * 第二种:shouldRasterize=YES设置光栅化
    * 通过Core Graphics重新绘制带圆角的视图
    
     `这种方式性能最好，但是UIButton上不知道怎么绘制，可以用UIimageView添加个 点击手势当做UIButton使用`
    * 通过混合图层
    
* “抖音”式的酷炫短视频开发进阶[点击前往](https://blog.csdn.net/vn9plgzvnps1522s82g/article/details/79124926)【==视频==】

* iOS实现波浪效果[点击前往](http://www.cocoachina.com/ios/20181113/25454.html)【==绘制==】

* 简易的iOS导航栏颜色渐变方案[点击前往](https://www.jianshu.com/p/10c71cb19b5e)【==小常识==】

<br>
<br>
<br>

-------
## <div align=center>2018/11/22</div>
* 一行代码实现 UIView 镂空效果[点击前往](https://juejin.im/post/5bed41df6fb9a04a0163e34a)【==小常识==】

     `本质上是 UIView 的 maskView 效果的「取反」。`

* Python的iOS自动化打包[点击前往](https://juejin.im/post/5bed3657518825604e0e4289)【==小常识==】

    `使用xcodebuild来控制Xcode进行一系列的操作,从而完成打包的操作.
    1.找到对应的项目
    2.clean项目
    3.archive项目
    4.export IPA
    5.上传蒲公英
    6.发送邮件
    7.收工
    `
    
* iOS 内存管理研究[点击前往](https://juejin.im/post/5bec0efcf265da61273cf333)【==性能==】

    `网上的绝大多数关于 iOS 内存管理的文章，大多是围绕 ARC/MRC、循环引用的原理或者是如何找寻内存泄漏来展开的，而这些内容更准确的说应该是 ObjC 或者 Swift 的内存管理，是语言层面带来的特性，而不是操作系统本身的内存管理。`
    * 物理内存
    * 虚拟内存(VM for Virtual Memory)
       * 页
       * Page In/Out
       * Wired memory
       * VM Region
       * VM Object
       * Resident Page
    
    

<br>
<br>
<br>

-------
## <div align=center>2018/11/21</div>
* UINavigationBar添加渐变的背景颜色[点击前往](https://blog.csdn.net/longshihua/article/details/78564273)【==小常识==】

* iOS 高德地图 路径规划[点击前往](https://www.jianshu.com/p/79b455c74679)【==地图==】

* iOS高德地图自定义定位小蓝点[点击前往](https://www.jianshu.com/p/9cfce5303acc)【==地图==】

* 【iOS】高德地图MAMapKit的使用：导航功能。[点击前往](https://www.jianshu.com/p/ee1c6e034409)【==地图==】

* 高德地图[点击前往](https://www.jianshu.com/p/f09a7011ffc4)【==地图==】

<br>
<br>
<br>

-------
## <div align=center>2018/11/14</div>
* iOS中堆和栈的使用[点击前往](https://www.jianshu.com/p/6f7cbe63f177)【==基础知识==】

    `堆和栈都是一种数据项按序排列的数据结构，只能在一端(称为栈顶(top))对数据项进行插入和删除。堆，队列优先,先进先出（FIFO—first in first out）；栈，先进后出(FILO—First-In/Last-Out)。一般情况下，如果有人把堆栈合起来说，那它的意思是栈，而不是堆。`
    
* 以SDWebImage为例谈论源码[点击前往](https://www.jianshu.com/p/f14b17467dd9)【==基础知识==】 

     `SDWebImage是一个图片缓存的框架。相较于AFNetworking集成的UIImageView+AFNetworking.h，对于图片的缓存实际应用的是NSURLCache自带的cache机制。而NSURLCache每次都要把缓存的raw data 再转化为UIImage，就带来了数据处理和内存方面的更多操作。SDWebImage的缓存由SDImageCache类来实现，这是一个单例类，该类负责处理内存缓存及一个可选的磁盘缓存，其中磁盘缓存的写操作是异步的，这样就不会对UI操作造成影响。`
     
     `SDWebImage有沙盒缓存机制，主要由三块组成
     1.内存图片缓存
     2.内存操作缓存
     3.磁盘沙盒缓存
     `
     
     ![](https://upload-images.jianshu.io/upload_images/1170656-8c5e61bb0b11d4e0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/604)

<br>
<br>
<br>

-------
## <div align=center>2018/11/13</div>
* AFNetworking到底做了什么？[点击前往](https://www.jianshu.com/p/856f0e26279d)【==三方框架==】

    `作为一个iOS开发，也许你不知道NSUrlRequest、不知道NSUrlConnection、也不知道NSURLSession...（说不下去了...怎么会什么都不知道...）但是你一定知道AFNetworking。`
    
* iOS-UIBezierPath和各种layer把我玩坏了[点击前往](https://www.jianshu.com/p/9ac372683735)【==绘制==】

     `UIBezierPath对象是CGPathRef数据类型的封装。path如果是基于矢量形状的，都用直线和曲线段去创建。我们使用直线段去创建矩形和多边形，使用曲线段去创建弧（arc），圆或者其他复杂的曲线形状。每一段都包括一个或者多个点，绘图命令定义如何去诠释这些点。每一个直线段或者曲线段的结束的地方是下一个的开始的地方。每一个连接的直线或者曲线段的集合成为subpath。一个UIBezierPath对象定义一个完整的路径包括一个或者多个subpaths。`
    
    
<br>
<br>
<br>

-------
## <div align=center>2018/11/13</div>
* iOS 集成友盟分享图片链接为http时无法加载问题解决[点击前往](https://www.cnblogs.com/liuzhuan155/p/8073977.html)【==小常识==】

 `问题描述
UMShareWebpageObject *obj = [UMShareWebpageObject shareObjectWithTitle:title descr:shareText thumImage:imgUrl];里面thumImage如果是本地图片，分享的时候就能够显示图片，但是如果换成http的网络图片地址，就无法显示`

* HTTP、TCP、UDP以及SOCKET之间的区别/联系[点击前往](https://www.cnblogs.com/jing99/p/6181488.html)【==基础知识==】

    `在网络层:有IP协议、ICMP协议、ARP协议、RARP协议和BOOTP协议。
    在传输层:中有TCP协议与UDP协议。
    在应用层:有FTP、HTTP、TELNET、SMTP、DNS等协议。`
    ![](https://images2015.cnblogs.com/blog/1010726/201612/1010726-20161214232544808-154772042.png)
    
* iOS开发 | 自定义不规则label[点击前往](labelhttps://www.jianshu.com/p/fade8341c316)【==绘制==】

<br>
<br>
<br>

-------
## <div align=center>2018/11/12</div>
* HealthKit Swift 教程: 开始[点击前往](https://blog.csdn.net/kmyhy/article/details/78328927)【==框架==】

    `HealthKit 从 iOS 8 开始出现。它实际上是一个关于所有健康数据的集中式存储库，允许用户构建一个生物数据库并存储健康数据。
    在这篇 HealthKit 教程中，你将创建一个简单的跟踪健康数据的 App，同时学习：
    如何请求 HealthKit 访问权限
    如何读取 HealthKit 数据并显示到 UITableView中
    如何将数据写入到 HealthKit 的核心数据库
`

* iOS HealthKit 健康应用[点击前往](https://www.jianshu.com/p/020e62b581ad)【==框架==】

* iOS中GIF图片的分解、合成与显示[点击前往](https://www.jianshu.com/p/4771e9ca65af)【==相册==】



<br>
<br>
<br>

-------
## <div align=center>2018/11/11</div>
* 10 个 iOS 开发实用小技巧[点击前往](https://mp.weixin.qq.com/s?__biz=MzA5NzMwODI0MA==&mid=2647760473&idx=1&sn=ef09d4eb4963f3168928e899b6523c24&chksm=8887e566bff06c70d485428b47dcbbb6863c558b963afb9449f72747b813662fab9c9b3ae25e&scene=21#wechat_redirect)【==小常识==】
    1. 控件的局部圆角问题
    2. navigationBar 的透明问题
    3. 全局设置 navigationBar 标题的样式和 barItem 的标题样式
    4. navigationBar 隐藏显示的过度
    5. 侧滑手势返回
    6. 给 webView 添加头视图
    7. 模态跳转的动画设置
    8. 图片处理只拿到图片的一部分
    9. 给 UIView 设置图片
    10.  给 TableView 或者 CollectionView 的 cell 添加简单动画

* valueForKeyPath:的妙用[点击前往](https://www.jianshu.com/p/501b8f4f8ae5)【==小常识==】
    * valueForKeyPath:针对集合的使用（Array Set）
    * 集合运算符
    * 简单集合操作符
    * 对象操作符
    * 嵌套集合操作符
    
* Protocol Buffer 入门使用: iOS[点击前往](https://www.jianshu.com/p/501b8f4f8ae5)【==小常识==】
  `Protocol Buffer是google于2008推出的一种数据交换的格式，它独立于语言，独立于平台。`

<br>
<br>
<br>

-------
## <div align=center>2018/11/08</div>
* iOS中static，const，extern相关的问题[点击前往](https://www.jianshu.com/p/123570248502)【==基础知识==】

* iOS--随机数rand、random、arc4random[点击前往](https://www.jianshu.com/p/106475cbd3da)【==小常识==】

    ```iOS 有如下三种随机数方法：
    1.srand((unsigned)time(0)); //不加这句每次产生的随机数不变
    int i = rand() % 5;
    
    2.srandom(time(0));
    int i = random() % 5;
    
    3.int i = arc4random() % 5 ;
    ```

* iOS保存App中的照片到系统相册或自建相册的方法[点击前往](https://www.jb51.net/article/82250.htm)【==相册==】

* iOS-使用WKWebview实现新闻详情页(JS和OC交互)[点击前往](https://www.jianshu.com/p/75f3abd40cc1)【==基础控件==】


-------
## <div align=center>2018/11/07</div>
* iOS计算机视觉—人脸识别[点击前往](https://www.jianshu.com/p/106475cbd3da)【==框架==】
    `人脸识别是计算机视觉的一种应用，iOS中常用的有四种实现方式：CoreImage、Vision、OpenCV、AVFoundation。`

* iOS 时间处理(仿朋友圈、微博发布时间)[点击前往](https://www.jianshu.com/p/e42431045177)【==时间==】
    ![](https://upload-images.jianshu.io/upload_images/2906617-30ca670a2a1d6e1b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/634)
    
* NSNumberFormatter介绍和用法[点击前往](https://www.jianshu.com/p/95952b145a8e)    
    * NSNumberFormatter可以用来处理NSString和NSNumber之间的转化，可以满足基本的数字形式的转化。
        * 四舍五入到整数
        * 货币数字形式
        * 货币的形式，带本地化的货币符号
        * 百分数形式,并且四舍五入到百分比的整数部分
        * 科学计数形式
        * 本地化拼写形式
        * 序数形式
        * 货币形式 显示ISO分配的货币符号
        * 货币形式
        * 会计形式
<br>
<br>
<br>

-------
## <div align=center>2018/11/06</div>
* 学习绘制iOS雷达图[点击前往](https://www.jianshu.com/p/1f5c4e13cd5e)【==绘制==】
    * 用UIBezierPath + CAShaperLayer绘制
    
* iOS | 小收获：自动埋点[点击前往](https://www.jianshu.com/p/ae8d45e10ac5)【==小常识==】
    `用户行为统计，俗称埋点，是一个成熟项目中必不可少的环节。埋点的常规做法是在项目中所有需要埋点的地方插入埋点，但随着项目不断壮大，埋点的地方越来越多，埋点代码散落在项目中不同角落，不易于管理和后期维护，出于简化埋点开发的目的，针对自动埋点做了小小的总结。`

* iOS自适应cell行高的那点破事儿[点击前往](http://www.cocoachina.com/ios/20181101/25353.html)【==小常识==】
  * iOS8之后就更简单了，直接使用：（这里要注意delegate中的返回高度方法就不用在写了）

    ```
    self.tableView.estimatedRowHeight = 666;
    self.tableView.rowHeight = UITableViewAutomaticDimension;
    ```
    
* 如何精确度量 iOS App 的启动时间[点击前往](https://www.jianshu.com/p/c14987eee107)【==小常识==】
<br>
<br>
<br>

-------
## <div align=center>2018/11/05</div>
* iOS 性能调优,成为一名合格iOS程序员必须掌握的技能[点击前往](https://www.jianshu.com/p/05b68c84913a)【==性能==】
    * Instuments
        * Activity Monitor
        * Allocations
    * Core Animation
        * Color Blended Layers（混合过度绘制）
        * Color Hits Green and Misses Red(光栅化缓存图层的命中情况)
        * Color Copied Image (拷贝的图片)
        * Color Immediately (颜色立即更新)
        * Color Misaligned Image (图片对齐方式)
        * Color Offscreen- Rendered Yellow (离屏渲染)
        * Color Compositing Fast-Path Blue
        * Flash Updated Regions (Core Graphics 绘制的图层)
    * Leaks
    * Time Profiler

* CoreBluetooth- iOS蓝牙开发[点击前往](https://www.jianshu.com/p/31da7966467a)【==基础知识==】
<br>
<br>
<br>


-------
## <div align=center>2018/11/01</div>
* iOS动画总结(Core Animation&POP&贝塞尔&Transform)[点击前往](https://www.jianshu.com/p/7e2d71ff702d)【==动画==】

* iOS 模拟器调试大法了解一下?[点击前往](https://juejin.im/post/5bd99ca7e51d4568383e80ea)【==基础知识==】

* iOS自动布局——Masonry详解[点击前往](https://juejin.im/post/5bd7d1cbe51d454372525f2f)【==三方框架==】

* iOS 关于全面屏适配的方案及UI在不同尺寸下适配方案[点击前往](https://juejin.im/post/5bd2a094518825289f7f3d17)【==基础知识==】


<br>
<br>
<br>

-------
## <div align=center>2018/10/30</div>
* iOS 富文本风格NSMutableParagraphStyle、定制UITextView插入图片和定制复制[点击前往](https://www.jianshu.com/p/52bdd2e41b11) 【==基础知识==】

* iOS UIButton之UIEdgeInsets详解[点击前往](https://www.jianshu.com/p/b4cb35c41bf0) 【==基础知识==】

* App预览制作，看我就够了[点击前往](https://www.jianshu.com/p/b7750683218a) 【==审核==】

<br>
<br>
<br>

-------
## <div align=center>2018/10/29</div>
* iOS性能优化（一）[点击前往](https://www.jianshu.com/p/848567ff9884) 【==性能==】

* iOS性能优化（二）[点击前往](https://www.jianshu.com/p/d569f3a6eb20) 【==性能==】

* iOS性能优化（三）[点击前往](https://www.jianshu.com/p/e3bd6a62ecae) 【==性能==】

<br>
<br>
<br>

-------
## <div align=center>2018/10/25</div>
* iOS套接字连接小票打印机[点击前往](https://www.jianshu.com/p/52bdd2e41b11) 【==基础知识==】

* iOS Bluetooth 打印小票(一)[点击前往](https://www.jianshu.com/p/2d624044a27b) 【==基础知识==】

* iOS Bluetooth 打印小票(二)[点击前往](https://www.jianshu.com/p/90cc08d11b5a) 【==基础知识==】
<br>
<br>
<br>

-------
## <div align=center>2018/10/23</div>
* CocoaAsyncSocket[点击前往](https://www.jianshu.com/p/9ea0f0c84990) 【==三方框架==】

* 关于使用GCDAsyncSocket[点击前往](https://www.jianshu.com/p/bccc8d8fcc9c) 【==三方框架==】

* iOS Socket封包、粘包、拆包处理[点击前往](https://www.jianshu.com/p/9ea0f0c84990) 【==三方框架==】

* iOS 使用GCDAsyncSocket及粘包、半包处理[点击前往](https://www.jianshu.com/p/9ccb8ad2d22f) 【==三方框架==】

* iOS 使用CocoaAsyncSocket自定义协议的byte方式传输[点击前往](https://blog.csdn.net/u012852597/article/details/81951592) 【==三方框架==】

* 利用CocoaAsyncSocket实现socket客户端（swift4）[点击前往](https://www.jianshu.com/p/21f0f189842f) 【==三方框架==】

* Swift 中的位操作[点击前往](https://www.jianshu.com/p/88d30477b1f6) 【==基础知识==】

<br>
<br>
<br>


-------
## <div align=center>2018/10/22</div>
* iOS 快捷修改文件名[点击前往](https://www.jianshu.com/p/232912095c9e) 【==小常识==】

* iOS App内评分[点击前往](https://www.jianshu.com/p/4f9fe2e1879e) 【==小常识==】

<br>
<br>
<br>

-------
## <div align=center>2018/10/21</div>
* iOS界面渲染流程分析[点击前往](https://www.jianshu.com/p/39b91ecaaac8) 【==基础知识==】
  `iOS渲染视图的核心是Core Animation
  其渲染层次依次为：图层树->呈现树->渲染树
  1.CPU阶段
    布局（Frame）
    显示（Core Graphics）
    准备（QuartzCore/Core Animation）
    通过IPC提交(打包好的图层树以及动画属性)
  2.OpenGL ES阶段
    生成(Generate)
    绑定(Bind)
    缓存数据(Buffer Data)
    启用(Enable)
    设置指针(Set Pointers)
    绘图(Draw)
    清除(Delete)
   3.GPU阶段
   接收提交的纹理（Texture）和顶点描述（三角形）
    应用变换（transform）
    合并渲染（离屏渲染等）
    其iOS平台渲染核心原理的重点主要围绕前后帧缓存、Vsync信号、CADisplayLink
`


* iOS 快速从OC过渡到Swift，由理论到实战[点击前往](https://www.jianshu.com/p/54b9fe310167)【==混编==】

* OC和Swift混编 - 在Swift中实现OC中静态常量和宏的效果[点击前往](https://www.jianshu.com/p/057986c8897b)【==混编==】 

* 从 OC 到 Swift 的快速入门与专业实践[点击前往](https://www.jianshu.com/p/dcf208268caf)【==混编==】

  `1.数据
   1.1 简单使用
   1.2 数据类型
   1.3 可选与非可选数据类型
   1.4 结构体
   1.5 枚举
   `
   `2.方法到函数
   `
   `3.类
   3.1 简单的定义
   3.2 特殊方法
   3.3 setter 与 getter 方法
   3.4 属性监听
  `
  `4.协议（代理）
  `
  `5.控制器中的代码布局
  `
  `6.@objc
   6.1 协议中使用
   6.2 函数中使用
  `
  
<br>
<br>
<br>

-------
## <div align=center>2018/10/18</div>
* iOS 后台无UI交互打印[点击前往](https://www.jianshu.com/p/1775b2be871b) 【==基础知识==】

* iOS打印功能详解 UIPrint​Interaction​Controller[点击前往](https://blog.csdn.net/gavin__fan/article/details/53520593) 【==基础知识==】

* iOS UIPrintInteractionController打印[点击前往](https://www.cnblogs.com/Milo-CTO/p/6856815.html) 【==基础知识==】

* 使用iOS AirPrint 让你的APP轻松实现打印功能[点击前往](http://ios.jobbole.com/85020/) 【==基础知识==】 

* AirPrint：无交互的后台打印实现[点击前往](http://www.cocoachina.com/ios/20160121/14965.html) 【==基础知识==】 

<br>
<br>
<br>

-------
## <div align=center>2018/10/17</div>

* 检测设备是否为 iPhone X/XS/XR 的几种方式 [点击前往](https://kangzubin.com/iphonex-detect/) 【==小常识==】

    `方式一：通过获取设备的 device model 来判断
     方式二：通过获取屏幕的宽高来判断
     方式三：通过底部安全区域的高度来判断
     方式四：通过是否支持 FaceID 判断
     方式五：通过 UIStatusBar 的高度判断`
     
* Swift基于CocoaAsyncSocket开发Socket通信 [点击前往](https://www.jianshu.com/p/ef466b55ba34) 【==三方框架==】

     `基于Scoket原生：代表框架 CocoaAsyncSocket。
基于WebScoket：代表框架 SocketRocket。
基于MQTT：代表框架 MQTTKit。
基于XMPP：代表框架 XMPPFramework。`


* iOS：基于Socket的第三方框架CocoaAsyncSocket的使用[点击前往](http://www.cnblogs.com/XYQ-208910/p/5169209.html) 【==三方框架==】

     `CocoaAsyncSocket无疑是目前封装得最完善的Socket库了：支持异步TCP/UDP，支持GCD，Objective-C接口封装,同时还有日志跟踪功能，使用此日志跟踪，程序员可以很方便的进行调试。`
     
* iOS开发--APP调用打印机（非蓝牙）[点击前往](https://www.jianshu.com/p/75703aa10633)【==框架==】

     `利用苹果iOS系统内置AirPrint功能WiFi无线打印照片，Word，PDF等各种文件到你的Air Printer打印机，但有个前提是你的打印机必须支持苹果Air Print功能，即AirPrint-Enable Printer。`
 
<br>
<br>
<br>

-------
## <div align=center>2018/10/16</div>

* iOS游戏引擎 [点击前往](https://www.jianshu.com/p/25e6b793b1c7) 【==基础知识==】

    | 名称 | 效果 | 平台 |
    | --- | --- | --- |
    | cocos2dx | 2D | 跨平台 |
    | unity3d | 3D | 跨平台 |
    | Spritekit | 2D | iOS |
    | SceneKit | 3D | iOS |

* iOS中忽略警告 [点击前往](https://www.jianshu.com/p/34c2aa625aba) 【==小常识==】

* OC 多线程之 GCD知识从基础到进阶 （1）[点击前往](https://www.jianshu.com/p/31b810b7986b) 【==多线程==】
 
<br>
<br>
<br>

-------
## <div align=center>2018/10/15</div>
* 适合写api接口文档的管理工具有哪些？[点击前往](https://www.jianshu.com/p/d7b13670e0eb) 【==小常识==】
   1.MinDoc [网址](https://www.iminho.me/)
   2.eoLinker [网址](https://www.eolinker.com/)
   3.apizza [网址](http://apizza.cc/)
   4.RAML [网址](https://raml.org/)
   5.Swagger [网址](https://swagger.io/)
   6.Showdoc [网址](https://www.showdoc.cc/)
   7.apidoc [网址](http://apidocjs.com/)  
   8.RAP     [网址](http://rap.taobao.org/org/index.do)
   9.APIJSON [网址](http://jsonapi.org/)
   
* iOS-MRC与ARC区别以及五大内存区[点击前往](https://www.jianshu.com/p/5eac83471b23) 【==基础知识==】

    ```
    1.五大内存区域
    1.1 栈区
    1.2 堆区
    1.3 全局区
    1.4 常量区
    1.5 代码区
    1.6 自由存储区
    1.7 static静态变量
    1.8 extern全局变量
    1.9 const常量
    -
    2.属性标识符
    2.1 @property、@synthesize、@dynamic
    2.2 nonatomic与atomic
    2.3 strong、weak、retain、assgin、copy、unsafe_unretained
    2.4 readOnly、readWrite、getter=、setter=
    2.5 __unsafe_unretained、__weak、__strong
    -
    3.MRC与ARC区别
    3.1 MRC手动内存管理
    3.2 ARC自动内存管理
    3.3 autoreleasepool自动释放池
    -
    4.NSString单独说
    ```
 
 * iOS-八大基本排序 [点击前往](https://www.jianshu.com/p/5eac83471b23) 【==算法==】
 
       `1.冒泡排序
        2.选择排序
        3.堆排序
        4.快速排序
        5.(插入排序)直接插入排序
        6.(插入排序)希尔排序
        7.归并排序
        8.基数排序
       `

<br>
<br>
<br>

-------
## <div align=center>2018/10/13</div>
* IOS加载本地html5及修改[点击前往](https://www.jianshu.com/p/07723613295d) 【==小常识==】
 `document.getElementsByClassName() //根据class属性
document.getElementsByName() //根据name属性
document.getElementById()//根据id属性
document.getElementsByTagName()//根据标签名
`
* iOS 【Objective-C 微博发布日期格式化】[点击前往](https://blog.csdn.net/Felicity294250051/article/details/52144511) 【==时间==】

* iOS---防止UIButton重复点击的三种实现方式[点击前往](https://blog.csdn.net/icetime17/article/details/51782983) 【==小常识==】

* iOS UIView 和 CALayer 的关系 [点击前往](https://blog.csdn.net/flover5724059/article/details/54943284) 【==基础知识==】

<br>
<br>
<br>


-------
## <div align=center>2018/10/12</div>
* iOS UITextView 高度随文字自动增加，并跟随键盘移动（一）[点击前往](https://blog.csdn.net/lwjok2007/article/details/47401293) 【==基础控件==】
* iOS UITextView 高度随文字自动增加，并跟随键盘移动（二）[点击前往](https://blog.csdn.net/lwjok2007/article/details/47403511) 【==基础控件==】
* iOS:如何优雅的让UITextView根据输入文字实时改变高度[点击前往](https://www.jianshu.com/p/9e960757de86) 【==基础控件==】
* 史上最全的iOS之UITextView实现placeHolder占位文字的N种方法[点击前往](https://www.jianshu.com/p/9edb8be75e0b) 【==基础控件==】

* iOS 使用IQKeyboardManager出现导航栏电池条变白、变透明问题处理[点击前往](https://blog.csdn.net/mr17liu/article/details/80712049) 【==小常识==】

* iOSTableview 禁止下拉,允许上拉[点击前往](http://www.cnblogs.com/sunfuyou/p/7131474.html) 【==小常识==】 
<br>
<br>
<br>

-------
## <div align=center>2018/10/10</div>
* iOS App提交指南(二)-协议、税务和银行业务[点击前往](https://www.jianshu.com/p/c7cf65911bc1) 【==审核==】

 `由于App属于收费应用，还需要填写协议、税务和银行信息
 流程如上连接
 `
 
* 用 Tesseract 开发一个你自己的文字识别应用[点击前往](https://www.sohu.com/a/211567336_487516) 【==三方框架==】

    `文字识别，缩写叫做 OCR，全称 Optical character recognition，译为光学字符识别`
    
* APP推广实战技能—— iOS100字符关键词覆盖！[点击前往](https://www.sohu.com/a/238424298_546355) 【==推广==】

 `关键词也称关键词覆盖，可以简单的理解为当你在IOS上想到的任何词类，这个App都会出现在你眼前，那说明这个关键词你的产品就覆盖上了（当然，有些大咖给出专业化的术语，即用户在 App Store 搜索一些词时，如果一款 App 出现在搜索结果中，那么该 App 就覆盖了这些词。）。
 关键词覆盖范围越广，App 就有越多的机会展示给用户，自然用户的下载量当然也会随波逐涨，这对于App推广运营大有好处。`
 
* 数据安全及各种加密算法对比[点击前往](https://www.jianshu.com/p/b44927161081) 【==算法==】
 
    * Base64编码（基础）
    * 单项散列函数 MD5、SHA1、SHA256、SHA512等
    * 消息认证码 HMAC-MD5、HMAC-SHA1
    * 对称加密 DES|3DES|AES（高级加密标准）
    * 非对称加密 RSA
    * 数字签名
    * 证书

* iOS绘图教程[点击前往](http://www.cocoachina.com/industry/20140115/7703.html) 【==绘制==】

  `iOS支持两套图形API族：Core Graphics/QuartZ 2D 和OpenGL ES。OpenGL ES是跨平台的图形API，属于OpenGL的一个简化版本。QuartZ 2D是苹果公司开发的一套API，它是Core Graphics Framework的一部分。`

<br>
<br>
<br>


-------
## <div align=center>2018/10/09</div>
* iOS 相机拍照、相册获取照片(仿微信) 一一 拍照、图片裁剪[点击前往](https://blog.csdn.net/a44496913/article/details/72934955 "快点前去查看详情") 【==相册==】

* iOS Xcode工程目录的 folder 和 group的区别(蓝色和黄色文件夹的区别)[点击前往](https://blog.csdn.net/fanjunxi1990/article/details/9352917 "快点前去查看详情") 【==基础知识==】
`group 一般只在你的工程中是文件夹的形式，但是在本地的目录中还是以散乱的形式放在一起的，除非你是从外部以group的形式引用进来的。
folder 只能作为资源，整个引用进项目，不能编译代码，也就是说，以folder形式引用进来的文件，不能被放在complie sources列表里面。`

* iOS view被导航条遮挡[点击前往](https://blog.csdn.net/u010545480/article/details/51149552 "快点前去查看详情") 【==小常识==】
 
```
1. 设置edgesForExtendedLayout
self.edgesForExtendedLayout = UIRectEdgeNone; //view不需要拓展到整个屏幕
2. 设置导航条的透明度
self.navigationController.navigationBar.translucent = NO;
```
  
* UIViewContentMode 图片显示模式(iOS)[点击前往](https://www.jianshu.com/p/8c3bc470ee7a "快点前去查看详情")【==基础知识==】
![](https://upload-images.jianshu.io/upload_images/1483801-939aa9f30c377571.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/441)



* iOS开发中遇到过的坑[点击前往](http://www.cocoachina.com/ios/20170221/18735.html "快点前去查看详情")【==小常识==】
    * 手机录音或通话时，app界面整体下移
    * 点击导航栏下方也会触发导航栏按钮的点击事件
    * 输入中文时限制字符长度
    * 修改导航栏颜色
    * 界面莫名其妙下移
    * GCD组函数
    * UISearchController
    * 自定义相机照片截取
 
<br>
<br>
<br>

-------
## <div align=center>2018/10/08</div>
* iOS 简约加载动画详解[点击前往](https://www.jianshu.com/p/3d62a6d9fdaf "快点前去查看详情") 【==动画==】
  ![](https://upload-images.jianshu.io/upload_images/1401103-f016cbb06c803c30.gif?imageMogr2/auto-orient/strip%7CimageView2/2/w/368)


* UITableView ReloadData那些坑[点击前往](https://www.jianshu.com/p/4ffdd772c864 "快点前去查看详情")【==小常识==】

    `调用reloadData 之后,立即调用numberOfRowsInSection,但是cellForRowAt和heightForRow 是异步调用,回到当前RunLoop,布局cell时才会被调用.
    reloadData 这样的特性就导致了没有及时调用相对应的代理方法,如果在reloadData之后,我们想要执行某些操作,就会导致出现不可预见的结果.
    `
* iOS时间格式化输出技巧[点击前往](https://www.jianshu.com/p/8f68fe8be4f4 "快点前去查看详情")【==时间==】    
![](https://upload-images.jianshu.io/upload_images/2229730-e2d5192debec537c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/622)    

* IOS性能优化篇[点击前往](https://juejin.im/post/5b7a9c466fb9a019eb43b0d5 "快点前去查看详情")【==性能==】
    
<br>
<br>
<br>


-------
## <div align=center>2018/10/07</div>
* iOS --苹果自带的UIMenuController功能扩展[点击前往](https://www.jianshu.com/p/ddd59867909a "快点前去查看详情")【==基础控件==】
 ![](https://upload-images.jianshu.io/upload_images/831339-a9615cb6c1677e2c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1000)

* 做一个 App 前需要考虑的几件事[点击前往](http://limboy.me/tech/2016/07/06/starting-an-app.html "快点前去查看详情")【==框架==】
    * 完善的日志系统
    * Commit Message 规范
    * 代码规范
    * 准备一份编程守则
    * 页面布局规范
    * 统计埋点
    * App 架构
    * 页面跳转机制
    * 在线配置
    * 选择合适的 Crash 平台
    * Code Review
    * 选择合适的开发模式
    * 持续集成
    * Bug 管理系统
    * 项目管理工具
    * Checklist



* ReactiveCocoa基本用法[点击前往](https://www.jianshu.com/p/bae2eeba118d "快点前去查看详情") 【==三方框架==】
> 在我们iOS开发过程中，经常会响应某些事件来处理某些业务逻辑，例如按钮的点击，上下拉刷新，网络请求，属性的变化（通过KVO）或者用户位置的变化（通过CoreLocation）。但是这些事件都用不同的方式来处理，比如action、delegate、KVO、callback等。
> <br>
> 其实这些事件，都可以通过RAC处理，ReactiveCocoa为事件提供了很多处理方法，而且利用RAC处理事件很方便，可以把要处理的事情，和监听的事情的代码放在一起，这样非常方便我们管理，就不需要跳到对应的方法里。非常符合我们开发中高聚合，低耦合的思想。

<br>
<br>
<br>

-------
## <div align=center>2018/10/06</div>
* 重识iOS之Property[点击前往](https://www.jianshu.com/p/21db1fe50ebf "快点前去查看详情")【==基础知识==】

    * 简介：属性（property）是Objective-C的一项特性，用于封装对象中的数据。这一特性可以令编译器自动编写与属性相关的存取方法，并且保存为各种实例变量。
    * 本质：属性的本质是实例变量与存取方法的结合。@property = ivar + getter + setter
    
    <br>
    
    `strong：表示指向并拥有该对象。其修饰的对象引用计数会 +1 ，该对象只要引用计数不为 0 就不会销毁，强行置空可以销毁它。一般用于修饰对象类型、字符串和集合类的可变版本。
   `
   
   ` 
copy：与 strong类似，设置方法会拷贝一份副本。一般用于修饰字符串和集合类的不可变版以及block （历史遗留问题）。
   `
   
   `
weak：表示指向但不拥有该对象。其修饰的对象引用计数不会增加，属性所指的对象销毁时属性值会清空。ARC环境下一般用于修饰可能会引起循环引用的对象，delegate 、xib 控件用 weak 修饰。
   `
   
   `
assign：主要用于修饰基本数据类型，如 NSIteger 、CGFloat 等，这些数值主要存在于栈中。
    `
    
  <br>
    
* iOS常用正则表达式[点击前往](https://www.jianshu.com/p/13774c6bbdaa "快点前去查看详情")【==基础知识==】
    > 我们先来举个例子分析一个可以匹配几种格式的电话号码，像(010)88886666，或022-22334455，或02912345678等的表达式
    表达式: \\(?0\d{2}[) -]?\d{8}
    首先是一个转义字符\(,它能出现0次或1次(?),然后是一个0，后面跟着2个数字(\d{2})，然后是)或-或空格中的一个，它出现1次或不出现(?)，
    最后是8个数字(\d{8})


* UICollectionView（一）——整体总结[点击前往](https://www.jianshu.com/p/c59a5c92f859 "快点前去查看详情")【==基础控件==】
    * 包括基本使用，自定义布局，自定义插入删除动画，自定义转场动画等几部分。
* iOS实现多个可变cell复杂界面的制作 [点击前往](https://www.jianshu.com/p/9fc838d46f5e "快点前去查看详情")【==基础控件==】
![多个可变cell复杂界面](https://upload-images.jianshu.io/upload_images/3611309-3a3dafacf25018a4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/274)

<br>
<br>
<br>


-------
## <div align=center>2018/10/05</div>
* iOS Native混编Flutter交互实践[点击前往](https://juejin.im/post/5bb033515188255c5e66f500 "快点前去查看详情")【==开发模式==】
![](https://user-gold-cdn.xitu.io/2018/9/30/1662848993a32e41?imageView2/0/w/1280/h/960/ignore-error/1)

* 流言终结者- Flutter和RN谁才是更好的跨端开发方案？[点击前往](https://juejin.im/post/5b9606055188255c7c6541c3 "快点前去查看详情")【==开发模式==】

* contentSize、contentOffset和contentInset的图解辨别[点击前往](https://www.jianshu.com/p/9091e5f34df5 "快点前去查看详情")【==基础知识==】
> contentSize:即内容,就是scrollview可以滚动的区域,比如frame = (0 ,0 ,100 ,200) contentSize = (100 ,400)，代表你的scrollview可以上下滚动，滚动区域为frame大小的两倍。其中常用的是contentSize.height = 内容的高度。
> <br>
> contentOffset: 即偏移量,其中分为contentOffset.y=内容的顶部和frame顶部的差值,contentOffset.x=内容的左边和frame左边的差值,下面重点阐述contentOffset.y,因为contentOffset.y最为常用。
> <br>
> contentInset:即内边距,contentInset = 在内容周围增加的间距(粘着内容),contentInset的单位是UIEdgeInsets,默认值为UIEdgeInsetsZero。


* iOS自定义裁剪区域，正方形圆形图片头像裁剪，仿QQ头像裁剪，圆形遮罩，矩型遮罩[点击前往](https://www.jianshu.com/p/856979c44b42 "快点前去查看详情")【==绘制==】
    * 矩形遮罩 
    ```
        //矩形裁剪区域
    - (void)transparentCutSquareArea{
        //圆形透明区域
        UIBezierPath *alphaPath = [UIBezierPath bezierPathWithRect:CGRectMake(0, 0, _selfWidth, _selfHeight)];
        UIBezierPath *squarePath = [UIBezierPath bezierPathWithRect:_cropFrame];
        [alphaPath appendPath:squarePath];
        CAShapeLayer *shapeLayer = [CAShapeLayer layer];
        shapeLayer.path = alphaPath.CGPath;
        shapeLayer.fillRule = kCAFillRuleEvenOdd;
        self.overLayView.layer.mask = shapeLayer;
        
        //裁剪框
        UIBezierPath *cropPath = [UIBezierPath bezierPathWithRect:CGRectMake(_cropFrame.origin.x-1, _cropFrame.origin.y-1, _cropFrame.size.width+2, _cropFrame.size.height+2)];
        CAShapeLayer *cropLayer = [CAShapeLayer layer];
        cropLayer.path = cropPath.CGPath;
        cropLayer.fillColor = [UIColor whiteColor].CGColor;
        cropLayer.strokeColor = [UIColor whiteColor].CGColor;
        [self.overLayView.layer addSublayer:cropLayer];
    }
    ```
    
    * 圆形裁剪遮罩 
    ```
        //圆形裁剪区域
    -(void)transparentCutRoundArea{
        CGFloat arcX = _cropFrame.origin.x + _cropFrame.size.width/2;
        CGFloat arcY = _cropFrame.origin.y + _cropFrame.size.height/2;
        CGFloat arcRadius;
        if (_cropSize.height > _cropSize.width) {
            arcRadius = _cropSize.width/2;
        }else{
            arcRadius  = _cropSize.height/2;
        }
        
        //圆形透明区域
        UIBezierPath *alphaPath = [UIBezierPath bezierPathWithRect:CGRectMake(0, 0, _selfWidth, _selfHeight)];
        UIBezierPath *arcPath = [UIBezierPath bezierPathWithArcCenter:CGPointMake(arcX, arcY) radius:arcRadius startAngle:0 endAngle:2*M_PI clockwise:NO];
        [alphaPath appendPath:arcPath];
        CAShapeLayer  *layer = [CAShapeLayer layer];
        layer.path = alphaPath.CGPath;
        layer.fillRule = kCAFillRuleEvenOdd;
        self.overLayView.layer.mask = layer;
        
        //裁剪框
        UIBezierPath *cropPath = [UIBezierPath bezierPathWithArcCenter:CGPointMake(arcX, arcY) radius:arcRadius+1 startAngle:0 endAngle:2*M_PI clockwise:NO];
        CAShapeLayer *cropLayer = [CAShapeLayer layer];
        cropLayer.path = cropPath.CGPath;
        cropLayer.strokeColor = [UIColor whiteColor].CGColor;
        cropLayer.fillColor = [UIColor whiteColor].CGColor;
        [self.overLayView.layer addSublayer:cropLayer];
    }
    ```
    
    * 裁剪矩形图片
    ```
        -(UIImage *)getSubImage{
        //裁剪区域在原始图片上的位置
        CGRect myImageRect = CGRectMake(leftTopPoint.x * scaleRatio, leftTopPoint.y*scaleRatio, width, height);
        
        //裁剪图片
        CGImageRef imageRef = self.image.CGImage;
        CGImageRef subImageRef = CGImageCreateWithImageInRect(imageRef, myImageRect);
        UIGraphicsBeginImageContext(myImageRect.size);
        CGContextRef context = UIGraphicsGetCurrentContext();
        CGContextDrawImage(context, myImageRect, subImageRef);
        UIImage* smallImage = [UIImage imageWithCGImage:subImageRef];
        CGImageRelease(subImageRef);
        UIGraphicsEndImageContext();
        
        //是否需要圆形图片
        if (self.isRound) {
            //将图片裁剪成圆形
            smallImage = [self clipCircularImage:smallImage];
        }
        return smallImage;
    }
    ```
    
    * 裁剪圆形图片
    ```
        //将图片裁剪成圆形
    -(UIImage *)clipCircularImage:(UIImage *)image{
        CGFloat arcCenterX = image.size.width/ 2;
        CGFloat arcCenterY = image.size.height / 2;
        UIGraphicsBeginImageContext(image.size);
        CGContextRef context = UIGraphicsGetCurrentContext();
        CGContextBeginPath(context);
        CGContextAddArc(context, arcCenterX, arcCenterY, image.size.width/2, 0.0, 2*M_PI, NO);
        CGContextClip(context);
        CGRect myRect = CGRectMake(0 , 0, image.size.width ,  image.size.height);
        [image drawInRect:myRect];
        
        UIImage *newImage = UIGraphicsGetImageFromCurrentImageContext();
        UIGraphicsEndImageContext();
        
        return  newImage;
    }
    ```
    
    
<br>
<br>
<br>

-------
## <div align=center>2018/09/30</div>
* iOS-Json字符串转字典，字典转Json字符串、以及Json字符串去掉空格、换行符等[点击前往](https://www.jianshu.com/p/1e242df1335b "快点前去查看详情")【==基础知识==】

<br>

* iOS 中间镂空效果的View[点击前往](https://www.jianshu.com/p/50c46c72e3dd "快点前去查看详情")【==绘制==】

<br>

* ios实现颜色渐变的几种方法[点击前往](https://www.jianshu.com/p/3e0e25fd9b85 "快点前去查看详情")【==颜色==】

<br>

* CABasicAnimation的使用方法（移动，旋转，缩放）[点击前往](https://blog.csdn.net/chenyongkai1/article/details/75307674 "快点前去查看详情")【==动画==】

<br>

* iOS开发_原生二维码生成与读取[点击前往](https://www.jianshu.com/p/b0c21ea1f4b2 "快点前去查看详情")【==二维码==】


<br>

* ios 二维码生成（带图标）以及相册识别二维码跳转[点击前往](https://www.jianshu.com/p/84c4b33221f9 "快点前去查看详情")【==二维码==】

<br>

* ios 二维码扫描（原生，可限制扫描区域）[点击前往](http://www.360doc.com/content/16/0503/19/27253262_555982864.shtml "快点前去查看详情")【==二维码==】


<br>
<br>
<br>

-------
## <div align=center>2018/09/29</div>
* iOS 生成Excel文件[点击前往](https://www.jianshu.com/p/b4efb5762e1e "快点前去查看详情")【==基础知识==】

    ```
    // 创建存放XLS文件数据的数组
    NSMutableArray  *xlsDataMuArr = [[NSMutableArray alloc] init];
    // 第一行内容
    [xlsDataMuArr addObject:@"Time"];
    [xlsDataMuArr addObject:@"Address"];
    [xlsDataMuArr addObject:@"Person"];
    [xlsDataMuArr addObject:@"Reason"];
    [xlsDataMuArr addObject:@"Process"];
    [xlsDataMuArr addObject:@"Result"];
    // 100行数据
    for (int i = 0; i < 100; i ++) {
        [xlsDataMuArr addObject:@"2016-12-06 17:18:40"];
        [xlsDataMuArr addObject:@"GuangZhou"];
        [xlsDataMuArr addObject:@"Mr.Liu"];
        [xlsDataMuArr addObject:@"Buy"];
        [xlsDataMuArr addObject:@"TaoBao"];
        [xlsDataMuArr addObject:@"Debt"];
    }
    // 把数组拼接成字符串，连接符是 \t（功能同键盘上的tab键）
    NSString *fileContent = [xlsDataMuArr componentsJoinedByString:@"\t"];
    // 字符串转换为可变字符串，方便改变某些字符
    NSMutableString *muStr = [fileContent mutableCopy];
    // 新建一个可变数组，存储每行最后一个\t的下标（以便改为\n）
    NSMutableArray *subMuArr = [NSMutableArray array];
    for (int i = 0; i < muStr.length; i ++) {
        NSRange range = [muStr rangeOfString:@"\t" options:NSBackwardsSearch range:NSMakeRange(i, 1)];
        if (range.length == 1) {
            [subMuArr addObject:@(range.location)];
        }
    }
    // 替换末尾\t
    for (NSUInteger i = 0; i < subMuArr.count; i ++) {
        if ( i > 0 && (i%6 == 0) ) {
            [muStr replaceCharactersInRange:NSMakeRange([[subMuArr objectAtIndex:i-1] intValue], 1) withString:@"\n"];
        }
    }
    // 文件管理器
    NSFileManager *fileManager = [[NSFileManager alloc]init];
    //使用UTF16才能显示汉字；如果显示为#######是因为格子宽度不够，拉开即可
    NSData *fileData = [muStr dataUsingEncoding:NSUTF16StringEncoding];
    // 文件路径
    NSString *path = NSHomeDirectory();
    NSString *filePath = [path stringByAppendingPathComponent:@"/Documents/export.xls"];
    NSLog(@"文件路径：\n%@",filePath);
    // 生成xls文件
    [fileManager createFileAtPath:filePath contents:fileData attributes:nil];
    ```

* 一份走心的iOS开发规范[点击前往](https://www.jianshu.com/p/c818c00e0690 "快点前去查看详情")【==规范==】

* Objective-C实现链式编程语法（DSL）[点击前往](https://www.jianshu.com/p/82012265e882 "快点前去查看详情")【==语法==】 

* Swift和OC互调 [点击前往](https://www.jianshu.com/p/119dfefae6cc "快点前去查看详情") 【==混编==】
* iOS-导航栏变透明的几种方法[点击前往](https://www.jianshu.com/p/2fad7965f114 "快点前去查看详情")【==小常识==】 
    * 第一种 
    
    ```
    [self.navigationController.navigationBar setBackgroundImage:[UIImage new] forBarMetrics:UIBarMetricsDefault];
        //去掉导航栏底部的黑线
        self.navigationController.navigationBar.shadowImage = [UIImage new];
    ```
    * 第二种 
  
    ```
    [[self.navigationController.navigationBar subviews] objectAtIndex:0].alpha = 0;
    ```
    
    * 第三种 

    ```
    for (UIView *aView in self.navigationController.navigationBar.subviews) {
        if ([aView isKindOfClass:NSClassFromString(@"_UINavigationBarBackground")]) {
            aView.hidden = YES;
        }
    }
    ```

* iOS 中 UIView 的 clipsTobounds 属性[点击前往](https://www.jianshu.com/p/2fad7965f114 "快点前去查看详情")【==小常识==】
    * clipsToBounds 决定了子视图的显示范围。
具体的说，就是当它取值为 YES 时，剪裁超出父视图范围的子视图部分；当它取值为 NO 时，不剪裁子视图。
默认值为 NO，但是在 UIScrollView 中，它的默认值是 YES，也就是说默认裁剪的。

* iOS 如何让button上的字体居左居右对齐[点击前往](https://www.jianshu.com/p/737553cd8eb5 "快点前去查看详情")【==小常识==】
    ```
    首先，这里使用button.titleLabel.textAlignment = NSTextAlignmentLeft; 这行代码是没有效果的，这只是让标签中的文本左对齐，但并没有改变标签在按钮中的对齐方式。
    
    所以我们使用button.contentHorizontalAlignment = UIControlContentHorizontalAlignmentLeft;
    ```

<br>
<br>
<br>

-------
## <div align=center>2018/09/28</div>
* ios中给view添加圆角并指定位置[点击前往](https://blog.csdn.net/meiyulong518/article/details/63686040 "快点前去查看详情")【==绘制==】

 比较推荐使用第三种，内存消耗少，速度快。
    * 设置图层的属性 
    * 第二种使用贝塞尔曲线UIBezierPath,开启图形上下文画出一个圆
    * 第三种使用UIBezierPath和CAShareLayer设置圆角


* iOS 日常工作之常用宏定义大全[点击前往](https://www.jianshu.com/p/213b3b96cafe "快点前去查看详情")【==定义==】

* iOS 枚举的巧用[点击前往](https://www.jianshu.com/p/97e582fe89f3 "快点前去查看详情")【==基础知识==】
     * 如果我们在枚举值中看见<<那我们就可以通过|(位运算符:或)进行组合使用
     ![](https://upload-images.jianshu.io/upload_images/2353624-476df8d2cb3f2524.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/551)
     * 如下图枚举值中没有<<,这就是普通的NSInteger类型的枚举, 所以不能组合使用:
     ![](https://upload-images.jianshu.io/upload_images/2353624-87cc026229c4ccc0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/596)
    
  
        ```
        NS_OPTIONS 与 NS_ENUM 和 enum 是有什么区别呢?
        ```
        
        1. 通过上面介绍我们可以看出enum可以声明一般类型和位掩码(bitmasked)类型
            
        2. NS_ENUM声明一般类型, NS_OPTIONS声明掩码(bitmasked)类型
                
        3. 那么问题又来了, 直接用enum不就可以了? 答案不是这样的, 苹果建议我们在OC中使用NS_ENUM与NS_OPTIONS, 为什么呢? 因为他们除了推断出不同类型的枚举,再就是当编译Objective-C++模式，它们产生的代码是不同的, 就是因为不同所以混编的时候使用enum会报错!
        
<br>

* iOS实现应用外自带地图、高德地图、百度地图导航[点击前往](https://www.jianshu.com/p/183f66da9d9c "快点前去查看详情")【==地图==】

```
- (void)actionSheet:(UIActionSheet *)actionSheet clickedButtonAtIndex:(NSInteger)buttonIndex
{
    
    NSLog(@"numberOfButtons == %ld",actionSheet.numberOfButtons);
     NSLog(@"buttonIndex == %ld",buttonIndex);
    
    if (buttonIndex == 0) {
        
        NSLog(@"自带地图触发了");
        
        MKMapItem *currentLocation =[MKMapItem mapItemForCurrentLocation];
        
        MKMapItem *toLocation = [[MKMapItem alloc] initWithPlacemark:[[MKPlacemark alloc] initWithCoordinate:self.coordinate addressDictionary:nil]];
        
        [MKMapItem openMapsWithItems:@[currentLocation,toLocation] launchOptions:@{MKLaunchOptionsDirectionsModeKey:MKLaunchOptionsDirectionsModeDriving,
            MKLaunchOptionsShowsTrafficKey:[NSNumber numberWithBool:YES]}];

    }
    //既安装了高德地图，又安装了百度地图
    if (actionSheet.numberOfButtons == 4) {
        
        if (buttonIndex == 2) {
            
            NSLog(@"高德地图触发了");
            
            NSString *urlsting =[[NSString stringWithFormat:@"iosamap://navi?sourceApplication= &backScheme= &lat=%f&lon=%f&dev=0&style=2",self.coordinate.latitude,self.coordinate.longitude]stringByAddingPercentEscapesUsingEncoding:NSUTF8StringEncoding];
            [[UIApplication  sharedApplication]openURL:[NSURL URLWithString:urlsting]];
        }
        if (buttonIndex == 3) {
            
            NSLog(@"百度地图触发了");
            NSString *urlsting =[[NSString stringWithFormat:@"baidumap://map/direction?origin={{我的位置}}&destination=latlng:%f,%f|name=目的地&mode=driving&coord_type=gcj02",self.coordinate.latitude,self.coordinate.longitude] stringByAddingPercentEscapesUsingEncoding:NSUTF8StringEncoding];
            [[UIApplication sharedApplication] openURL:[NSURL URLWithString:urlsting]];
        }
 
    }
    //安装了高德地图或安装了百度地图
    if (actionSheet.numberOfButtons == 3) {
        
        if (buttonIndex == 2) {
            
            if ( [[UIApplication sharedApplication] canOpenURL:[NSURL URLWithString:@"iosamap://"]]) {
                
                NSLog(@"只安装的高德地图触发了");
                NSString *urlsting =[[NSString stringWithFormat:@"iosamap://navi?sourceApplication= &backScheme= &lat=%f&lon=%f&dev=0&style=2",self.coordinate.latitude,self.coordinate.longitude]stringByAddingPercentEscapesUsingEncoding:NSUTF8StringEncoding];
                [[UIApplication  sharedApplication]openURL:[NSURL URLWithString:urlsting]];
               
            }
            if ([[UIApplication sharedApplication] canOpenURL:[NSURL URLWithString:@"baidumap://"]]) {
                 NSLog(@"只安装的百度地图触发了");
                NSString *urlsting =[[NSString stringWithFormat:@"baidumap://map/direction?origin={{我的位置}}&destination=latlng:%f,%f|name=目的地&mode=driving&coord_type=gcj02",self.coordinate.latitude,self.coordinate.longitude] stringByAddingPercentEscapesUsingEncoding:NSUTF8StringEncoding];
                [[UIApplication sharedApplication] openURL:[NSURL URLWithString:urlsting]];
            }

           
        }
        
    }
    
}

```
   

<br>
<br>
<br>

-------
## <div align=center>2018/09/27</div>
* iOS 拨打电话三种方式总结[点击前往](https://www.jianshu.com/p/73872e332b24 "快点前去查看详情")【==小常识==】
    * 这种方法,拨打完电话回不到原来的应用,会停留在通讯录里,而且是直接拨打,不弹出提示
        ```
        NSMutableString* str=[[NSMutableString alloc]initWithFormat:@"tel:%@",@"186xxxx6979"];
        [[UIApplication sharedApplication] openURL:[NSURL URLWithString:str]];
        
        ```
    * 这种方法,打完电话后还会回到原来的程序,也会弹出提示,推荐这种
        ```
        NSMutableString* str=[[NSMutableString alloc] initWithFormat:@"tel:%@",@"186xxxx6979"];
        
        UIWebView * callWebview = [[UIWebView alloc] init];
        
        [callWebview loadRequest:[NSURLRequest requestWithURL:[NSURL URLWithString:str]]];
        
        [self.view addSubview:callWebview];
        
        ```
        
    * 这种方法也会回去到原来的程序里（注意这里的telprompt）,也会弹出提示
    
            ``` 
            NSMutableString *str=[[NSMutableString alloc] initWithFormat:@"telprompt://%@",@"186xxxx6979"];
            [[UIApplication sharedApplication] openURL:[NSURL URLWithString:str]]
            
            ```
* iOS动画篇：下拉刷新动画[点击前往](https://www.jianshu.com/p/3c51e4896632 "快点前去查看详情")【==动画==】

* iOS GCD详细介绍[点击前往](https://www.jianshu.com/p/174199ceac04 "快点前去查看详情")【==多线程==】

* UILabel设置圆角无效是不是少了这个？[点击前往](https://www.jianshu.com/p/2e3ce8694f3d "快点前去查看详情")【==小常识==】
    ```
    label.layer.cornerRadius = 2.f;
    
    同时需要设置
    label.clipsToBounds = YES; 
    或者        
    label.layer.masksToBounds = YES;
    
    ```
* iOS阴影设置详解[点击前往](https://www.jianshu.com/p/575ce7d7b68f "快点前去查看详情")【==小常识==】

    
<br>
<br>
<br>

-------
## <div align=center>2018/09/26</div>
* iOS下的实际网络连接检测:RealReachability[点击前往](http://www.cocoachina.com/special/20160222/15374.html "快点前去查看详情")【==网络==】 
![RealReachability架构图](http://7xr2v8.com1.z0.glb.clouddn.com/111.png)

* iOS【WKWebView转PDF、图片】[点击前往](https://www.jianshu.com/p/4924d00bafc1 "快点前去查看详情") 【==基础控件==】

* iOS 12正式版新特性总结[点击前往](https://juejin.im/post/5ba1c825e51d450e63220c42 "快点前去查看详情") 【==小常识==】

* 十分钟接入iOS 12新特性——Siri Shortcuts[点击前往](https://www.jianshu.com/p/edda18023a7b "快点前去查看详情") 【==框架==】
    * Siri Shortcuts的API有两大类：NSUserActivity和Intents
    * 接入步骤
    
        ```
       1. plist添加activity type（Define Shortcut）
       2. 配置NSUserActivity并通知Siri（Donate Shortcut）
       3. 在AppDelegate中处理Siri打开APP请求 （Handle Shortcut）
        ```
* iOS 快速从OC过渡到Swift，由理论到实战 [点击前往](https://blog.csdn.net/LOLITA0164/article/details/82017800 "快点前去查看详情")【==混编==】
   1. 常量let和变量var  
   2. 输出print 
   3. 数据类型（布尔值、数组、字典、元组、可选类型）
   4. 几种运算符（区间运算符、空合运算符、溢出运算符）
   5. 控制语句
   6. 函数和闭包
   7. 类和结构体
   8. 属性（计算属性、延迟属性（懒加载）、属性观察器、类型属性）
   9. 枚举（枚举语法、关联值）
   10. 扩展
   11. 协议（协议语法、可选协议）
   12. 循环引用（弱引用（weak）、无主引用（unowned））
   13. 类型转换
        


<br>
<br>
<br>

-------
## <div align=center>2018/09/25</div>
* iOS下将照片保存到相册的三种方法[点击前往](https://www.jianshu.com/p/bf20733ba19b "快点前去查看详情")【==相册==】  
    * 使用UIImageWriteToSavedPhotosAlbum函数将图片保存到相册
    * 使用AssetsLibrary框架中的ALAssetsLibrary类来实现
    * 使用Photos框架的PHPhotoLibrary类来实现保存到相册功能
* 针对WKWebView进行内容的截屏[点击前往](https://www.jianshu.com/p/28c70420977c "快点前去查看详情") 【==基础控件==】 
    * 推荐使用第三方框架DDGScreenShot（swift）
    * 原理：
    
        ```
        UIGraphicsBeginImageContextWithOptions(<#CGSize size#>, <#BOOL opaque#>, <#CGFloat scale#>)
        ```
size——绘制图片的大小
opaque—透明开关,如果图形完全不用透明,设置为YES以优化位图的存储。
scale—–缩放因子，[UIScreen mainScreen].scale保持原图分辨率
    
* iOS 10打开设置中的指定模块[点击前往](https://www.jianshu.com/p/f9731d82e6de "快点前去查看详情")【==小常识==】 
    * 使用url scheme。photos-redirect://
但这个scheme是私有的，有风险，而且也没有文档阐述怎么传递参数，你可以试一下。 【为通过审核，对 "photos-redirect://" 进行base64编码混淆后再解码】

* iOS开发之Base64编码与解码[点击前往](https://www.jianshu.com/p/06089c140452 "快点前去查看详情")【==安全==】 
    * 1>ASCII码是8个二进制位一编码
    * 2>Base64编码是6个二进制位一编码,所以转换成字符串后会比ASCII内容要多
        * 64编码
        
        ```
        - (NSString *)encode:(NSString *)string
        {
            //先将string转换成data
            NSData *data = [string dataUsingEncoding:NSUTF8StringEncoding];
            
            NSData *base64Data = [data base64EncodedDataWithOptions:0];
            
            NSString *baseString = [[NSString alloc]initWithData:base64Data encoding:NSUTF8StringEncoding];
            
            return baseString;
        }
        ```
        * 64解码
                
        ```
            - (NSString *)dencode:(NSString *)base64String
          {
              //NSData *base64data = [string dataUsingEncoding:NSUTF8StringEncoding];

              NSData *data = [[NSData alloc]initWithBase64EncodedString:base64String options:NSDataBase64DecodingIgnoreUnknownCharacters];

              NSString *string = [[NSString alloc]initWithData:data encoding:NSUTF8StringEncoding];

              return string;
          }
        ```



<br>
<br>
<br>

-------
## <div align=center>2018/09/24</div>
* iOS如何将父视图透明，而内容不透明的方法[点击前往](https://www.jianshu.com/p/768641b847c1 "快点前去查看详情") 【==小常识==】 
    * self.view.backgroundColor = [[UIColor whiteColor]colorWithAlphaComponent:0.7f];
* iOS开发你可能不知道的细节一：UITextField清空按钮[点击前往](https://www.jianshu.com/p/6d123a8d43d8 "快点前去查看详情") 【==小常识==】 
    * textField.clearButtonMode=UITextFieldViewModeWhileEditing; 
    * UITextFieldViewModeNever,  清空按钮永不出现
    * UITextFieldViewModeUnlessEditing,  不编辑的时候出现
    * UITextFieldViewModeAlways 只要输入框有内容就出现
    * 
* 在iOS开发中使用iconfont图标[点击前往](https://www.jianshu.com/p/3b10bb95b332 "快点前去查看详情")【==基础知识==】  
          使用iconfont的可以达到以下目的
    * 减小应用体积，字体文件比图片要小；
    * 图标保真缩放，解决2x/3x乃至将来nx图问题；
    * 方便更改图标颜色大小，图片复用。   
* iOS开发技巧-国际化(Localization)，只看一篇就够了[点击前往](https://www.jianshu.com/p/f8edd7b7a217 "快点前去查看详情") 【==基础知识==】
    * App名称国际化
    * 图片、文字国际化
    * 强制默认显示某种语言
    * 启动图国际化
    * iOS10所需的权限配置国际化
    * xib/storyboard国际化
   
*  UIBezierPath介绍 [点击前往](https://www.jianshu.com/p/6c9aa9c5dd68 "快点前去查看详情") 【==绘制==】 
    *  iOS的绘图框架有多种，我们平常最常用的就是UIKit，其底层是依赖CoreGraphics实现的，而且绝大多数的图形界面也都是由UIKit完成，并且UIImage、NSString、UIBezierPath、UIColor等都知道如何绘制自己，也提供了一些方法来满足我们常用的绘图需求。除了UIKit，还有CoreGraphics、Core Animation，Core Image，OpenGL ES等多种框架，来满足不同的绘图要求。各个框架的大概介绍如下：
        * UIKit：最常用的视图框架，封装度最高，都是OC对象
        * CoreGraphics：主要绘图系统，常用于绘制自定义视图，纯C的API，使用Quartz2D做引擎
        * CoreAnimation：提供强大的2D和3D动画效果
        * CoreImage：给图片提供各种滤镜处理，比如高斯模糊、锐化等
        * OpenGL-ES：主要用于游戏绘制，但它是一套编程规范，具体由设备制造商实现 
        
         ![绘图系统](http://cc.cocimg.com/api/uploads/20170809/1502248071320268.png)
  
* IOS 常用动画的实现方式整理（主讲：CoreAnimation）[点击前往](https://www.jianshu.com/p/9aead7675221 "快点前去查看详情")【==动画==】
![](https://upload-images.jianshu.io/upload_images/1642760-85e2c9a00b4c8cde.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/800)
<br>
<br>
<br>


-------
## <div align=center>2018/09/23</div>
*  面向对象设计的六大设计原则（附 Demo 及 UML 类图）  [点击前往](https://juejin.im/post/5b9526c1e51d450e69731dc2 "快点前去查看详情") 【==基础知识==】 

| 缩写 | 英文名称 | 中文名称 | 定义 |
| --- | --- | --- |  --- | 
| SRP | Single Responsibility Principle | 单一职责原则 | 一个软件实体如类、模块和函数应该对扩展开放，对修改关闭。|
| OCP | Open Close Principle | 开闭原则 | 一个类只允许有一个职责，即只有一个导致该类变更的原因。 |
| LSP | Liskov Substitution Principle | 里氏替换原则 | 针对接口编程，而不是针对实现编程。尽量不要从具体的类派生，而是以继承抽象类或实现接口来实现。关于高层模块与低层模块的划分可以按照决策能力的高低进行划分。业务层自然就处于上层模块，逻辑层和数据层自然就归类为底层。 |
| LoD | Law of Demeter （ Least Knowledge Principle） | 迪米特法则（最少知道原则） | 多个特定的客户端接口要好于一个通用性的总接口。 |
| ISP | Interface Segregation Principle | 接口分离原则 |一个对象应该对尽可能少的对象有接触，也就是只接触那些真正需要接触的对象。 |
| DIP | Dependency Inversion Principle | 依赖倒置原则 |所有引用基类的地方必须能透明地使用其子类的对象，也就是说子类对象可以替换其父类对象，而程序执行效果不变。|


*  iOS数组排序(倒叙 生序 降序) [点击前往](https://www.jianshu.com/p/e9d561140f5b "快点前去查看详情")【==算法==】
    * 倒序
        `
        NSMutableArray *temp = [NSMutableArray arrayWithObjects:@"5",@"1",@"4",@"2",nil];
        temp = (NSMutableArray *)[[temp reverseObjectEnumerator] allObjects];
        `
    * 升序／ 降序
        * 字符串  sortedArrayUsingSelector
        * 字典  sortedArrayUsingSelector 和 sortedArrayUsingComparator
        * 数据模型 sortedArrayUsingDescriptors 和 sortUsingDescriptors
<br>
<br>
<br>


-------
## <div align=center>2018/09/22</div>
*  iOS 中集合遍历方法的比较和技巧  [点击前往](http://blog.sunnyxx.com/2014/04/30/ios_iterator/ "快点前去查看详情")  【==算法==】
   
| 遍历方法 | 100对象遍历操作（耗时） |  1000000对象遍历操作（耗时） | 100对象遍历执行一个很费时的操作（耗时） |
| --- | --- | --- | --- |
| 经典for循环  | 0.001355 | 1.246721 | 1.106567 |
| for in (NSFastEnumeration) | 0.002308 | 0.025955 | 1.102643 | 
|  makeObjectsPerformSelector   | 0.001120 | 0.068234 | 1.103965 | 
|  kvc集合运算符   | 0.004272 | 21.677246 | N/A | 
|  enumerateObjectsUsingBlock   | 0.001145 | 0.586034 | 1.104888 | enumerateObjectsWithOptions(NSEnumerationConcurrent)   | 0.001605 | 0.722548 | 0.554670 | 
|  dispatch_apply   | 0.001380 | 0.607100 | 0.554858 | 





*  iOS的几种定时器及区别 [点击前往](https://www.jianshu.com/p/5e3784d3ac80 "快点前去查看详情")【==定时器==】
*  iOS三种定时器的用法NSTimer、CADisplayLink、GCD [点击前往](http://www.cocoachina.com/ios/20160919/17595.html "快点前去查看详情")【==定时器==】
* iOS定时器，你真的会使用吗？[点击前往](https://www.jianshu.com/p/c167ca4d1e7e "快点前去查看详情")【==定时器==】 

| 定时器 | 定义 |  
| --- | --- | 
| NSTimer | iOS中最基本的定时器，在Swift中称为Timer。其通过RunLoop来实现，一般情况下较为准确，但当当前循环耗时操作较多时，会出现延迟问题。同时，也受所加入的RunLoop的RunLoopMode影响，具体可以参考RunLoop的特性。 | 
| CADisplayLink | CADisplayLink是基于屏幕刷新的周期，所以其一般很准时，每秒刷新60次。其本质也是通过RunLoop，所以不难看出，当RunLoop选择其他模式或被耗时操作过多时，仍旧会造成延迟。 |  
| GCD | GCD定时器是dispatch_source_t类型的变量，其可以实现更加精准的定时效果 |  
| NSThread(performSelector:afterDelay:) |  |  




<br>
<br>
<br>


-------
## <div align=center>2018/09/21</div>
*  如何用最快速度撸个最简单的markdown编辑器  [点击前往](https://www.jianshu.com/p/b6ae8c2d5f05 "快点前去查看详情") 【==开发==】 

*  iOS 12 中的 Siri Shortcuts 简介 （Siri Shortcuts 是由前 WWDC 奖学金获得者开发的 iOS 自动化应用程序 Workflow 演变而来的。） [点击前往](https://juejin.im/post/5ba33afd5188255c600416fa "快点前去查看详情")【==框架==】
<br>
<br>
<br>

-------
## <div align=center>2018/09/20</div>

*  iPhoneXS 屏幕分辨率终极指南  [点击前往](https://kangzubin.com/iphone-resolutions/ "快点前去查看详情") 【==定义==】 

*  iOS小技巧总结，绝对有你想要的 [点击前往](https://www.jianshu.com/p/4523eafb4cd4 "快点前去查看详情")【==小常识==】
