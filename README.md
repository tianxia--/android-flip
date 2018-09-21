android-flip
============

Aphid FlipView是一个UI组件，可以像[Flipboard](http://www.flipboard.com)那样完成翻转动画。

Android操作系统2.2+的预构建演示APK文件可以在:

[https://github.com/openaphid/android-flip/tree/master/FlipView/Demo/APK](https://github.com/openaphid/android-flip/tree/master/FlipView/Demo/APK)

详情请参阅我们的博客:

[http://openaphid.github.com/blog/categories/flipview/](http://openaphid.github.com/blog/categories/flipview/)

# #版本说明

要获得完整的更改列表，请查看我们的[问题跟踪器](https://github.com/openaphid/android-flip/issues/milestones?state=closed)

### # [v0.9.8, 2013年5月7日](https://github.com/openaphid/android-flip/issue ?

修正了翻转时偶尔出现的闪光问题。((# 52)(https://github.com/openaphid/android-flip/issues/52))

-在演示应用程序中禁用标题栏的下降阴影。

### # [v0.9.7, 2012年1月1日](https://github.com/openaphid/android-flip/issue ?

核心控制流已经被重写，修复了适配器和异步内容支持的一些性能和可靠性问题。([#36](https://github.com/openaphid/android-flip/issues/36)， [#29](https://github.com/openaphid/android-flip/issue /29)， [#8])

-支持不同的位图格式的动画，可以用来减少峰值内存消耗。((# 34)(https://github.com/openaphid/android-flip/issues/34))

-修复严重的内存泄漏问题。([# 33](https://github.com/openaphid/android-flip/issues/33),[# 21](https://github.com/openaphid/android-flip/issues/21))

演示[FlipAsyncContentActivity](https://github.com/openaphid/android-flip/blob/master/FlipView/Demo/src/com/aphidmobile/flip/demo/FlipAsyncContentActivity.java)已经被重写，以说明处理异步内容的正确方法。((# 37)(https://github.com/openaphid/android-flip/issues/37))

一个新的演示[FlipDynamicAdapterActivity](https://github.com/openaphid/android- flipflip/blogview/demo/src/com/aphidmobile/flip/demo/flipdynamicadapteractivity.java)演示如何动态加载更多页面。((# 41)(https://github.com/openaphid/android-flip/issues/41))

-感谢[@siegfriedpammer](https://github.com/siegfriedpammer)的贡献。([拉# 40](https://github.com/openaphid/android-flip/pull/40))

### # [v0.9.6, 12月12日](https://github.com/openaphid/android-flip/issue ?

-增加抛投支持。([Pull #10](https://github.com/openaphid/android-flip/pull/10)

-添加XML配置支持。([问题# 13](https://github.com/openaphid/android-flip/issues/13))

-添加几个新的演示。

-修复几个错误时翻转。([议题17](https://github.com/openaphid/android-flip/issues/17)，[议题16](https://github.com/openaphid/android-flip/issues/15)，[议题14]

-特别感谢[@iPaulPro](https://github.com/iPaulPro)的杰出贡献。

### # v0.9.5, 2012年11月9日

-支持水平翻转。([6]拉请求(https://github.com/openaphid/android-flip/pull/6)。感谢[@axexmedearis](https://github.com/alexmedearis)的贡献)

(http://openaphid.github.com/images/flipview-horizontal-demo.gif“Aphid FlipView v0.9.5截图”)

-支持事件监听器在翻转完成时得到通知。# 3([问题](https://github.com/openaphid/android-flip/issues/3))

-支持内容重载时翻转。# 4([问题](https://github.com/openaphid/android-flip/issues/3))

-不正确的渲染阴影在水平模式。# 7([问题](https://github.com/openaphid/android-flip/issues/7))

### # v0.9, 2012年9月21日
第一个版本

(http://openaphid.github.com/images/flipview-demo.gif“Aphid FlipView v0.9截图”)

##版权和许可证

' ' '
Aphid移动电话版权所有

根据Apache许可证，2.0版本(“许可证”)获得许可;
除非符合许可证规定，否则您不得使用此文件。
你可以在

http://www.apache.org/licenses/license - 2.0

除非适用法律要求或书面同意，软件
在许可证下分发的是“按原样”分发的，
没有任何明示或默示的保证或条件。
有关特定语言管理权限和
许可证限制。
````
