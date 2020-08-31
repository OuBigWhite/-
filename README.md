# 开发问题汇总
### 1. iOS 13 TabBar文字替换颜色变为蓝色
* 跳转到某个控制器隐藏TabBar，再返回TabBar切换控制器的时候选中文字颜色变蓝色
* 解决： 
```
//这里的self是UITabBarController，代码根据各自的TabBar定义而定
self.tabBar.tintColor = selColor;
```

### 2. xcode10 编译报错 library not found for -lstdc .6.0.9
* 解决：
[Github](https://github.com/OuBigWhite/libstdc- "libstdc-")
