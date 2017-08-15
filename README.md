# ikanman-unlocker

这是一个Bookmarklet，用来帮助移动设备解锁ikanman.com的区域限制

用法非常简单，建立一个书签，在“地址”栏填入：

```JavaScript
javascript:document.cookie='country=US;domain=.ikanman.com;path=/;max-age=2147483647';undefined
```

之后打开网站，点击书签，刷新页面即可

目前已测试通过设备：Chrome（Windows），Samsung Browser（Android），Safari（iOS 8）

PC用户建议使用用户脚本，简单快捷：[解除ikanman.com上被屏蔽的漫画](https://greasyfork.org/zh-CN/scripts/30822-%E8%A7%A3%E9%99%A4ikanman-com%E4%B8%8A%E8%A2%AB%E5%B1%8F%E8%94%BD%E7%9A%84%E6%BC%AB%E7%94%BB){:target="_blank"}
