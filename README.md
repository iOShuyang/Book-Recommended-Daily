# <div align=center>每日优秀文章推荐</div>

### ⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️

### 作者会每天推荐一篇优秀文章给大家
### 每天会不定时更新，以下文章均是平时累计 转载请联系文章原作者。
### 麻烦给小编一颗🌟，让小编更有动力总结出更多优秀文章和作品。

### ⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️
<br>
<br>
<br>

-------
## <div align=center>2018/09/28</div>
* iOS 生成Excel文件[点击前往](https://www.jianshu.com/p/b4efb5762e1e "快点前去查看详情")

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

* 一份走心的iOS开发规范[点击前往](https://www.jianshu.com/p/c818c00e0690 "快点前去查看详情")

* Objective-C实现链式编程语法（DSL）[点击前往](https://www.jianshu.com/p/82012265e882 "快点前去查看详情") 

* Swift和OC互调 [点击前往](https://www.jianshu.com/p/119dfefae6cc "快点前去查看详情") 
* iOS-导航栏变透明的几种方法[点击前往](https://www.jianshu.com/p/2fad7965f114 "快点前去查看详情") 
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

* iOS 中 UIView 的 clipsTobounds 属性[点击前往](https://www.jianshu.com/p/2fad7965f114 "快点前去查看详情")
    * clipsToBounds 决定了子视图的显示范围。
具体的说，就是当它取值为 YES 时，剪裁超出父视图范围的子视图部分；当它取值为 NO 时，不剪裁子视图。
默认值为 NO，但是在 UIScrollView 中，它的默认值是 YES，也就是说默认裁剪的。

* iOS 如何让button上的字体居左居右对齐[点击前往](https://www.jianshu.com/p/737553cd8eb5 "快点前去查看详情")
    ```
    首先，这里使用button.titleLabel.textAlignment = NSTextAlignmentLeft; 这行代码是没有效果的，这只是让标签中的文本左对齐，但并没有改变标签在按钮中的对齐方式。
    
    所以我们使用button.contentHorizontalAlignment = UIControlContentHorizontalAlignmentLeft;
    ```

<br>
<br>
<br>

-------
## <div align=center>2018/09/28</div>
* ios中给view添加圆角并指定位置[点击前往](https://blog.csdn.net/meiyulong518/article/details/63686040 "快点前去查看详情")

 比较推荐使用第三种，内存消耗少，速度快。
    * 设置图层的属性 
    * 第二种使用贝塞尔曲线UIBezierPath,开启图形上下文画出一个圆
    * 第三种使用UIBezierPath和CAShareLayer设置圆角


* iOS 日常工作之常用宏定义大全[点击前往](https://www.jianshu.com/p/213b3b96cafe "快点前去查看详情")

* iOS 枚举的巧用[点击前往](https://www.jianshu.com/p/97e582fe89f3 "快点前去查看详情")
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

* iOS实现应用外自带地图、高德地图、百度地图导航[点击前往](https://www.jianshu.com/p/183f66da9d9c "快点前去查看详情")

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
* iOS 拨打电话三种方式总结[点击前往](https://www.jianshu.com/p/73872e332b24 "快点前去查看详情")
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
* iOS动画篇：下拉刷新动画[点击前往](https://www.jianshu.com/p/3c51e4896632 "快点前去查看详情")

* iOS GCD详细介绍[点击前往](https://www.jianshu.com/p/174199ceac04 "快点前去查看详情")

* UILabel设置圆角无效是不是少了这个？[点击前往](https://www.jianshu.com/p/2e3ce8694f3d "快点前去查看详情")
    ```
    label.layer.cornerRadius = 2.f;
    
    同时需要设置
    label.clipsToBounds = YES; 
    或者        
    label.layer.masksToBounds = YES;
    
    ```
* iOS阴影设置详解[点击前往](https://www.jianshu.com/p/575ce7d7b68f "快点前去查看详情")

    
<br>
<br>
<br>

-------
## <div align=center>2018/09/26</div>
* iOS下的实际网络连接检测:RealReachability[点击前往](http://www.cocoachina.com/special/20160222/15374.html "快点前去查看详情")  
![RealReachability架构图](http://7xr2v8.com1.z0.glb.clouddn.com/111.png)

* iOS【WKWebView转PDF、图片】[点击前往](https://www.jianshu.com/p/4924d00bafc1 "快点前去查看详情") 

* iOS 12正式版新特性总结[点击前往](https://juejin.im/post/5ba1c825e51d450e63220c42 "快点前去查看详情") 

* 十分钟接入iOS 12新特性——Siri Shortcuts[点击前往](https://www.jianshu.com/p/edda18023a7b "快点前去查看详情") 
    * Siri Shortcuts的API有两大类：NSUserActivity和Intents
    * 接入步骤
    
        ```
       1. plist添加activity type（Define Shortcut）
       2. 配置NSUserActivity并通知Siri（Donate Shortcut）
       3. 在AppDelegate中处理Siri打开APP请求 （Handle Shortcut）
        ```
* iOS 快速从OC过渡到Swift，由理论到实战 [点击前往](https://blog.csdn.net/LOLITA0164/article/details/82017800 "快点前去查看详情")
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
* iOS下将照片保存到相册的三种方法[点击前往](https://www.jianshu.com/p/bf20733ba19b "快点前去查看详情")  
    * 使用UIImageWriteToSavedPhotosAlbum函数将图片保存到相册
    * 使用AssetsLibrary框架中的ALAssetsLibrary类来实现
    * 使用Photos框架的PHPhotoLibrary类来实现保存到相册功能
* 针对WKWebView进行内容的截屏[点击前往](https://www.jianshu.com/p/28c70420977c "快点前去查看详情")  
    * 推荐使用第三方框架DDGScreenShot（swift）
    * 原理：
    
        ```
        UIGraphicsBeginImageContextWithOptions(<#CGSize size#>, <#BOOL opaque#>, <#CGFloat scale#>)
        ```
size——绘制图片的大小
opaque—透明开关,如果图形完全不用透明,设置为YES以优化位图的存储。
scale—–缩放因子，[UIScreen mainScreen].scale保持原图分辨率
    
* iOS 10打开设置中的指定模块[点击前往](https://www.jianshu.com/p/f9731d82e6de "快点前去查看详情") 
    * 使用url scheme。photos-redirect://
但这个scheme是私有的，有风险，而且也没有文档阐述怎么传递参数，你可以试一下。 【为通过审核，对 "photos-redirect://" 进行base64编码混淆后再解码】

* iOS开发之Base64编码与解码[点击前往](https://www.jianshu.com/p/06089c140452 "快点前去查看详情") 
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
## <div align=center>2018/09/23</div>
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
*  iOS三种定时器的用法NSTimer、CADisplayLink、GCD [点击前往](http://www.cocoachina.com/ios/20160919/17595.html "快点前去查看详情")
* iOS定时器，你真的会使用吗？[点击前往](https://www.jianshu.com/p/c167ca4d1e7e "快点前去查看详情") 

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
