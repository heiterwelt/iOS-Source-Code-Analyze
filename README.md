# iOS-Source-Code-Analyze

<p align='center'>
  <img src='images/banner.png'>
  <em>Banner designed by <a href="https://dribbble.com/levine" alt="iOS Source code analyze">Levine</a></em>
</p>

## 为什么要建这个仓库

世人都说阅读开源框架的源代码对于功力有显著的提升，所以我也尝试阅读开源框架的源代码，并对其内容进行详细地分析和理解。在这里将自己阅读开源框架源代码的心得记录下来，希望能对各位开发者有所帮助。我会不断更新这个仓库中的文章，如果想要关注可以点 `star`。

## 目录

+ ObjC 源代码
    + [从 NSObject 的初始化了解 isa](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/objc/从%20NSObject%20的初始化了解%20isa.md)
    + [深入解析 ObjC 中方法的结构](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/objc/深入解析%20ObjC%20中方法的结构.md)
    + [从源代码看 ObjC 中消息的发送](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/objc/从源代码看%20ObjC%20中消息的发送.md)
    + [你真的了解 load 方法么？](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/objc/你真的了解%20load%20方法么？.md)
    + [懒惰的 initialize](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/objc/懒惰的%20initialize%20方法.md)
    + [上古时代 Objective-C 中哈希表的实现](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/objc/上古时代%20Objective-C%20中哈希表的实现.md)
+ DKNightVersion（2.3.0）
    + [成熟的夜间模式解决方案](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/DKNightVersion/成熟的夜间模式解决方案.md)
+ AFNetworking（3.0.4）
	+ [AFNetworking 概述（一）](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/AFNetworking/AFNetworking%20概述（一）.md)
	+ [AFNetworking 的核心 AFURLSessionManager（二）](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/AFNetworking/AFNetworking%20的核心%20AFURLSessionManager（二）.md)
	+ [处理请求和响应 AFURLSerialization（三）](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/AFNetworking/处理请求和响应%20AFURLSerialization（三）.md)
	+ [AFNetworkReachabilityManager 监控网络状态（四）](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/AFNetworking/AFNetworkReachabilityManager%20监控网络状态（四）.md)
	+ [验证 HTTPS 请求的证书（五）](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/AFNetworking/验证%20HTTPS%20请求的证书（五）.md)
+ BlocksKit（2.2.5）
	+ [神奇的 BlocksKit（一）](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/BlocksKit/神奇的%20BlocksKit%20（一）.md) 遍历、KVO 和分类
	+ [神奇的 BlocksKit（二）](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/BlocksKit/神奇的%20BlocksKit%20（二）.md) 动态代理的实现
+ Alamofire
    + [iOS 源代码分析 --- Alamofire](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/Alamofire/iOS%20源代码分析%20----%20Alamofire.md)
+ SDWebImage
    + [iOS 源代码分析 --- SDWebImage](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/SDWebImage/iOS%20源代码分析%20---%20SDWebImage.md)
+ MBProgressHUD
    + [iOS 源代码分析 --- MBProgressHUD](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/MBProgressHUD/iOS%20源代码分析%20---%20MBProgressHUD.md)
+ Masonry
    + [iOS 源代码分析 --- Masonry](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/Masonry/iOS%20源代码分析%20---%20Masonry.md)

## 勘误

+ 如果在文章中发现了问题，欢迎提交 PR 或者 issue

## 转载

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />本<span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" rel="dct:type">作品</span>由 <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/Draveness/iOS-Source-Code-Analyze" property="cc:attributionName" rel="cc:attributionURL">Draveness</a> 创作，采用<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">知识共享署名 4.0 国际许可协议</a>进行许可。


