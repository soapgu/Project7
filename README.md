# Project7 Swit 学习项目

参考资料
 - [Project 7教程](https://www.hackingwithswift.com/100/35)

说明：
- 有部分代码由于iOS升级关系需要调整，AppDelegate不能操作window?.rootViewController，需要到SceneDelegate里面处理，怀疑SceneDelegate是AppDelegate“分家”分出来的
- Challenge 部分才是真正好玩的地方，使用filter又能用尾随闭包啦
- UITabBarController和UINavigationController一样都是容器型Controller，它们都有自己的View的“外观”，现在UIKit编程的观感，StoryBoard，Controller，以及他们之间的联系是重头戏
