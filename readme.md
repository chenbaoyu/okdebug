

# 适用于Android的调试神器

调试神器，是一个app运行时候的调试菜单库，旨在帮助填补设计，开发和质量保证之间的空白。app运行的时候可以直接在app上查看属性，查看视图间距与位置，查看数据库，以及各种方便我们调试的功能。

## 属性检查功能 
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200826152555209.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTE1MTk4Mjg=,size_16,color_FFFFFF,t_70#pic_center)


仅凭我们的眼睛难以有效的判断当时View的具体状态。而属性检查器可以轻松准确的浏览视图中的各种状态。某些属性也可以通过属性检查器进行更改。例如，这允许用户运行时直接更改TextView的text属性以检查布局的反应。

## 测量功能![在这里插入图片描述](https://img-blog.csdnimg.cn/20200826152958771.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTE1MTk4Mjg=,size_16,color_FFFFFF,t_70#pic_center)


测量器让您可以检查视图层次结构中与其他视图相关视图的度量信息。验证视图之间的边距或填充与规范相匹配变得容易。

## 崩溃信息展示功能
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200826153414172.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTE1MTk4Mjg=,size_16,color_FFFFFF,t_70#pic_center)

崩溃器正常情况下无法进入，只有app崩溃时才会自动出现。出现后，它将显示一个屏幕，其中包含异常调用堆栈以及与测试相关的设备元数据

## 查看数据库功能![在这里插入图片描述](https://img-blog.csdnimg.cn/20200826153742945.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTE1MTk4Mjg=,size_16,color_FFFFFF,t_70#pic_center)
可以让你轻松的在app中查看数据库信息，app中所有的数据库和表和具体信息一览无遗。
## 查看和更改Shared Preferences
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200826154044406.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTE1MTk4Mjg=,size_16,color_FFFFFF,t_70#pic_center)
可以让你轻松的在app中查看Shared Preferences信息，并且可以立即更改数据查看效果。

## 更多功能
1. 可以直接查看data/data/包名下的数据，并且支持拷贝
2. 可以一键擦除数据，这样可以让我们模拟用户第一次使用，而无需卸载重装
3. 还有其他帮助我们调试的功能，赶快来尝鲜吧。
4. 后续调试神器的扩展会做成插件化，让更多的开发者做出更多好用的调试功能，可以直接插入进调试神器中供更多的人使用

## 调试神器如何使用
1. 只需一行依赖接入，即可让您app拥有强大的调试功能。无需任何编码
` implementation 'com.chenbaoyu:debuggerartifact:1.0.7`

2. 运行你的app后，直接摇晃手机即可唤起调试神器菜单。然后在里面选择你要使用的功能即可。![在这里插入图片描述](https://img-blog.csdnimg.cn/20200826155342433.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTE1MTk4Mjg=,size_16,color_FFFFFF,t_70#pic_center)



## 还等什么，赶快来尝鲜吧！

### 加微信沟通问题：come_to_play1







      
