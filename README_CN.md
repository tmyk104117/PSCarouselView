# PSCarouselView 
扔进你的项目就可以用了！实现了很多app都需要的首页广告轮播功能。

#### **版本更新**

`enhancement` 从`1.1.0`版本开始，支持故事板直接编辑属性，不用再写那么多初始化代码啦！

![image](https://raw.githubusercontent.com/DeveloperPans/PSCarouselView/master/Inspector.png)

### 预览图 
![image](https://raw.githubusercontent.com/DeveloperPans/PSCarouselView/master/PSCarouselView.gif)

### 导入库
##### `推荐`使用CocoaPods导入
在你的podfile文件中加入如下一行

    pod 'PSCarouselView'
    
##### 下载并手动导入
下载zip，解压并把`PSCarouselView`文件夹以及里面的文件添加到你的工程。


### 使用方法
1. Storyboard拖拽一个`UICollectionView`到你要放轮播的位置，约束好大小
2. Storyboard中将这个`CollectionView`的类设置为`PSCarouselView`
3. 连接`IBOutlet`到`ViewController`
4. 给carouselView的*`imageURL`*赋值。

### 注意：
1. 如果你想做个pageControl，请实现代理方法。
2. 控件需要使用SDWebImage，不使用CocoaPods的情况下，请确保你的工程中导入了SDWebImage。

### 文档

API文档详见 [shengpan.net](http://doc.shengpan.net/Classes/PSCarouselView.html) 或者 [CocoaPods Doc](http://cocoadocs.org/docsets/PSCarouselView/1.3.0)

详情请参阅Demo

