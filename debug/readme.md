目录结构
---
```
- org.inlinc.inhttp.dll    // dll文件
- org.inlinc.inhttp.json   // 插件说明文件，ANSI编码。
```
说明
---
* 此文件夹下的文件为开发者模式使用的文件，同时放置在酷Q的app目录下即可。
* json文件为插件说明文件，可用于自定义插件权限，接收的事件类型。

> 如何启用开发者模式?
* 请打开酷Q目录下的/conf/CQP(CQA).cfg，加入以下代码：

```
[Dev]
Enable=1
```
或
* 双击`应用管理`的版本号(如`5.11.14`)，勾选`[开发]`→`[开发模式]`，然后点击`[重启酷Q]`