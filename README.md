# 为B站播放器添加媒体键支持

### 安装
[Greasy Fork](https://greasyfork.org/zh-CN/scripts/371107-%E4%B8%BAb%E7%AB%99%E6%92%AD%E6%94%BE%E5%99%A8%E6%B7%BB%E5%8A%A0%E5%AA%92%E4%BD%93%E9%94%AE%E6%94%AF%E6%8C%81)

### Bug
- 现只支持媒体键控制播放/暂停和播放下一个视频操作，播放上一个视频时存在bug。

- 脚本假定播放器对象为全局变量`player`，若之后B站更改了播放器实例名，代码会失效。
