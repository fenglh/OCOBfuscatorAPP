# OCObfuscator

OCObfuscator 是一个Objective-C混淆工具， 基于LLVM Clang 中的LibTooling 模块开发。

原理详见:[基于LLVM的Objective-C代码混淆实现](http://www.banmalu.top/tag/llvm/)


#### 混淆支持

- [x] 类名混淆
- [x] 协议名混淆
- [x] 分类名
- [x] 方法名
- [x] 属性名
- [x] 实例变量名
- [x] 消息表达式
- [x] xib、Storyboard
- [ ] 云端词库

说明：
如果被混淆的代码有在静态库或动态库中被使用，请在混淆前剔除该文件勾选，否则会导致找不到方法或者未定义符号

#### 应用截图


![初始界面](http://www.banmalu.top/content/images/2020/09/image-12.png)

![即将构建](http://www.banmalu.top/content/images/2020/09/image-3.png)


![构建中](http://www.banmalu.top/content/images/2020/09/image-4.png)

![构建完成](http://www.banmalu.top/content/images/2020/09/image-13.png)

#### 混淆结果截图

![混淆前](http://www.banmalu.top/content/images/2020/09/image-8.png)

![混淆后](http://www.banmalu.top/content/images/2020/09/image-6.png)

![混淆前](http://www.banmalu.top/content/images/2020/09/image-9.png)

![混淆后](http://www.banmalu.top/content/images/2020/09/image-7.png)
