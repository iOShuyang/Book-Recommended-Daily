# <div align=center>每日优秀文章推荐</div>

### 作者会每天推荐一篇优秀文章给大家
### 每天会不定时更新，以下文章均是平时累计 转载请联系文章原作者。
### 麻烦给小编一颗🌟，让小编更有动力总结出更多优秀文章和作品。
<br>
<br>
<br>

-------
## <div align=center>2018/09/22</div>
* iOS如何将父视图透明，而内容不透明的方法[点击前往](https://www.jianshu.com/p/768641b847c1 "快点前去查看详情")  
    * self.view.backgroundColor = [[UIColor whiteColor]colorWithAlphaComponent:0.7f];
* iOS开发你可能不知道的细节一：UITextField清空按钮[点击前往](https://www.jianshu.com/p/6d123a8d43d8 "快点前去查看详情")  
    * textField.clearButtonMode=UITextFieldViewModeWhileEditing; 
    * UITextFieldViewModeNever,  清空按钮永不出现
    * UITextFieldViewModeUnlessEditing,  不编辑的时候出现
    * UITextFieldViewModeAlways 只要输入框有内容就出现
    * 
* 在iOS开发中使用iconfont图标[点击前往](https://www.jianshu.com/p/3b10bb95b332 "快点前去查看详情")  
          使用iconfont的可以达到以下目的
    * 减小应用体积，字体文件比图片要小；
    * 图标保真缩放，解决2x/3x乃至将来nx图问题；
    * 方便更改图标颜色大小，图片复用。   
* iOS开发技巧-国际化(Localization)，只看一篇就够了[点击前往](https://www.jianshu.com/p/f8edd7b7a217 "快点前去查看详情") 
    * App名称国际化
    * 图片、文字国际化
    * 强制默认显示某种语言
    * 启动图国际化
    * iOS10所需的权限配置国际化
    * xib/storyboard国际化
   
*  UIBezierPath介绍 [点击前往](https://www.jianshu.com/p/6c9aa9c5dd68 "快点前去查看详情")  
    *  iOS的绘图框架有多种，我们平常最常用的就是UIKit，其底层是依赖CoreGraphics实现的，而且绝大多数的图形界面也都是由UIKit完成，并且UIImage、NSString、UIBezierPath、UIColor等都知道如何绘制自己，也提供了一些方法来满足我们常用的绘图需求。除了UIKit，还有CoreGraphics、Core Animation，Core Image，OpenGL ES等多种框架，来满足不同的绘图要求。各个框架的大概介绍如下：
        * UIKit：最常用的视图框架，封装度最高，都是OC对象
        * CoreGraphics：主要绘图系统，常用于绘制自定义视图，纯C的API，使用Quartz2D做引擎
        * CoreAnimation：提供强大的2D和3D动画效果
        * CoreImage：给图片提供各种滤镜处理，比如高斯模糊、锐化等
        * OpenGL-ES：主要用于游戏绘制，但它是一套编程规范，具体由设备制造商实现 
        
         ![绘图系统](http://cc.cocimg.com/api/uploads/20170809/1502248071320268.png)
  

<br>
<br>
<br>


-------
## <div align=center>2018/09/22</div>
*  面向对象设计的六大设计原则（附 Demo 及 UML 类图）  [点击前往](https://juejin.im/post/5b9526c1e51d450e69731dc2 "快点前去查看详情")  

| 缩写 | 英文名称 | 中文名称 | 定义 |
| --- | --- | --- |  --- | 
| SRP | Single Responsibility Principle | 单一职责原则 | 一个软件实体如类、模块和函数应该对扩展开放，对修改关闭。|
| OCP | Open Close Principle | 开闭原则 | 一个类只允许有一个职责，即只有一个导致该类变更的原因。 |
| LSP | Liskov Substitution Principle | 里氏替换原则 | 针对接口编程，而不是针对实现编程。尽量不要从具体的类派生，而是以继承抽象类或实现接口来实现。关于高层模块与低层模块的划分可以按照决策能力的高低进行划分。业务层自然就处于上层模块，逻辑层和数据层自然就归类为底层。 |
| LoD | Law of Demeter （ Least Knowledge Principle） | 迪米特法则（最少知道原则） | 多个特定的客户端接口要好于一个通用性的总接口。 |
| ISP | Interface Segregation Principle | 接口分离原则 |一个对象应该对尽可能少的对象有接触，也就是只接触那些真正需要接触的对象。 |
| DIP | Dependency Inversion Principle | 依赖倒置原则 |所有引用基类的地方必须能透明地使用其子类的对象，也就是说子类对象可以替换其父类对象，而程序执行效果不变。|


*  iOS数组排序(倒叙 生序 降序) [点击前往](https://www.jianshu.com/p/e9d561140f5b "快点前去查看详情")
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
*  iOS 中集合遍历方法的比较和技巧  [点击前往](http://blog.sunnyxx.com/2014/04/30/ios_iterator/ "快点前去查看详情")  
   
| 遍历方法 | 100对象遍历操作（耗时） |  1000000对象遍历操作（耗时） | 100对象遍历执行一个很费时的操作（耗时） |
| --- | --- | --- | --- |
| 经典for循环  | 0.001355 | 1.246721 | 1.106567 |
| for in (NSFastEnumeration) | 0.002308 | 0.025955 | 1.102643 | 
|  makeObjectsPerformSelector   | 0.001120 | 0.068234 | 1.103965 | 
|  kvc集合运算符   | 0.004272 | 21.677246 | N/A | 
|  enumerateObjectsUsingBlock   | 0.001145 | 0.586034 | 1.104888 | enumerateObjectsWithOptions(NSEnumerationConcurrent)   | 0.001605 | 0.722548 | 0.554670 | 
|  dispatch_apply   | 0.001380 | 0.607100 | 0.554858 | 





*  iOS的几种定时器及区别 [点击前往](https://www.jianshu.com/p/5e3784d3ac80 "快点前去查看详情")

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
*  如何用最快速度撸个最简单的markdown编辑器  [点击前往](https://www.jianshu.com/p/b6ae8c2d5f05 "快点前去查看详情")  

*  iOS 12 中的 Siri Shortcuts 简介 （Siri Shortcuts 是由前 WWDC 奖学金获得者开发的 iOS 自动化应用程序 Workflow 演变而来的。） [点击前往](https://juejin.im/post/5ba33afd5188255c600416fa "快点前去查看详情")
<br>
<br>
<br>

-------
## <div align=center>2018/09/20</div>

*  iPhoneXS 屏幕分辨率终极指南  [点击前往](https://kangzubin.com/iphone-resolutions/ "快点前去查看详情")  

*  iOS小技巧总结，绝对有你想要的 [点击前往](https://www.jianshu.com/p/4523eafb4cd4 "快点前去查看详情")
