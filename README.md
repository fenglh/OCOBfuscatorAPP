# OCObfuscator

OCObfuscator 是一个Objective-C混淆工具， 基于LLVM Clang 中的LibTooling 模块开发。原理详见:[基于LLVM的Objective-C代码混淆实现](http://www.banmalu.top/tag/llvm/)

博客同步: [OCObfuscator](http://www.banmalu.top/ocobfuscator/)




### 混淆支持

- [x] 类名混淆
- [x] 协议名混淆
- [x] 分类名
- [x] 方法名
- [x] 属性名
- [x] 实例变量名
- [x] 消息表达式
- [x] xib、Storyboard
- [ ] 云端词库
- [ ] OC Swift 混编

----

### 1.1.0

1. 修复@selector混淆问题
2. 修复method混淆问题
3. 修复个别情况混淆后无法覆盖文件问题
4. 提升混淆速度

### 1.0.1

1. 修复一些Bug
2. UI代码重构
3. 支持Xcode12
4. 丰富输出日志，包括普通日志、警告、错误等。
5. 临时内置词库约有300+单词。（PS:是少了点，快马加鞭完善中）

##### 测试代码混淆效果使用的Demo 

[DemoViewController](https://github.com/fenglh/DemoViewController.git)
[ObfuscateTestDemo](https://github.com/fenglh/ObfuscateTestDemo)

##### 应用截图


![初始界面](http://www.banmalu.top/content/images/2020/09/image-14.png)

![即将构建](http://www.banmalu.top/content/images/2020/09/image-3.png)


![构建中](http://www.banmalu.top/content/images/2020/09/image-4.png)

![构建完成](http://www.banmalu.top/content/images/2020/09/image-13.png)

#### 混淆结果截图

![混淆前](http://www.banmalu.top/content/images/2020/09/image-8.png)

![混淆后](http://www.banmalu.top/content/images/2020/09/image-6.png)

![混淆前](http://www.banmalu.top/content/images/2020/09/image-9.png)

![混淆后](http://www.banmalu.top/content/images/2020/09/image-7.png)
