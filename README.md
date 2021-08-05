# ios_calculator

## 1.项目简介

使用Swift编写的IOS APP，实现了计算器的常见功能。

## 2.环境简介

语言：Swift 5.4

UI框架：UIKit

包管理工具：CocoaPods

布局框架：SnapKit 5.0.0

## 3.项目截图

<img src="https://img-blog.csdnimg.cn/img_convert/d9cf4a90e8f9e659fa7cf93ea5e01626.png" style="zoom: 50%;" />

## 4.开发流程与代码逻辑简述

- 打开Xcode创建IOS APP项目。
- 引入包管理工具和框架。
- 编写布局类，继承UIView。编写Button组件，继承UIButton。
- 封装计算逻辑工具类。
- 在ViewController中引入布局文件，通过布局类中的按钮点击协议完成计算器的计算逻辑。

## 5.技术准备

- [Swift基础语法](https://docs.swift.org/swift-book/GuidedTour/GuidedTour.html)

- [UIKit使用](https://developer.apple.com/documentation/uikit/)

- [SnapKit使用](http://snapkit.io/docs/)

- [CocoaPods使用](https://cocoapods.org/)

  ```
  sudo gem install cocoapods
  pod init
  pod install
  ```

  M1 mac安装有[问题](https://github.com/CocoaPods/CocoaPods/issues/10723)

- [Swift中的协议](https://docs.swift.org/swift-book/LanguageGuide/Protocols.html)

## 6.总结

学习IOS开发也有一段时间了，学习途径包括哔哩哔哩视频教程，YouTube视频教程，Apple官网文档，阅读相关书籍。因为拥有Flutter和Android的开发经验，学习过程中没有什么大的阻碍，唯一觉得不好的一点是中文社区的匮乏，面向初学者的文章和书籍都比较少，随着IOS相关技术的破坏性更新，导致很多教程不适用，耽误了不少时间。编写UI有拖拽storyboard和纯代码两种方式，个人还是比较喜欢纯代码的方式。开发语言有Swift,objective-c，UI框架有UIkit和SwiftUI，选择了资料比较多的SWift和UIkit学习，技术选择的多样性在最初也造成了一些困惑，因为精力有限，不可能全都学。后续使用IOS技术写一些复杂点的APP，提升技术水平。



# android_calculator

## 1.项目简介

使用java编写的Android APP，实现了计算器的常见功能。

## 2.环境简介

语言：java 1.8

依赖库：详见android_calculator/app/build.gradle下的dependencies

## 3.项目截图

<img src="https://img-blog.csdnimg.cn/030dc2799f8b4d9cb0bc7d985ddc01bd.png" style="zoom: 67%;" />

## 4.开发流程与代码逻辑简述

- 编写布局xml，使用`constraintlayout`布局
- `activity`中注册控件，监听点击事件
- 点击=号时执行计算逻辑

## 5.技术准备

- java基础语法
- [安卓开发官网](https://developer.android.com/)
- [`constraintlayout`布局](https://developer.android.com/reference/androidx/constraintlayout/widget/ConstraintLayout)

## 6.总结

三种技术写一个项目，感觉给自己挖了一大坑，本意是熟悉一下学习过的技术，可能最近工作和学习的状态都有所下滑，感觉没有什么动力了。

写之前看了一下其他的开源项目，参考了一下布局，学习了[`constraintlayout`布局](https://developer.android.com/reference/androidx/constraintlayout/widget/ConstraintLayout)，其实本来想用jetpack试一下，不过自己kotlin还没学，而且学到太多也有点记不住，就放弃了。

可能需要歇一歇再继续。



# dart语言编写的计算器FLutter APP
