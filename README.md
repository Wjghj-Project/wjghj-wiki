> 已废弃：MediaWiki Service 已转为 docker compose
>
> https://github.com/project-epb/mediawiki-service

# wjghj-wiki

**Wjghj Project** 网站 Wiki 站台部分的备份，该部分网站使用 MediaWiki 程序搭建，包含轻度自定义。

## 关于仓库

这里会备份一些非机密的配置文件、扩展文件以及媒体资源，同时包含一些原创小工具（Gadget）.

## 版权信息

除非特殊说明，本仓库代码均以 **CC BY-NC-SA 4.0** 协议提供。媒体资源若无特殊说明版权均归属原作者所有。其他特例请参阅各文件夹的说明文件。

## 相关站台

- 小鱼君和他的朋友们（主站台）：<https://www.wjghj.cn>
- 万界规划局静态资源数据库（Common）：<https://common.wjghj.cn>

## 结构介绍

- LocalSettings 包含 wiki 的自定义配置文件，例如 wiki farm 构架的自定义代码
- NOTE 笔记、备忘录
- extensions 包含 wiki 扩展功能的额外配置文件
- gadgets 原创小工具
  - 其中 InPageEdit 已作为独立插件提供，详见：[Wjghj-Project/InPageEdit](https://github.com/Wjghj-Project/InPageEdit)
- icons 站台标志
  - 请注意：该文件夹内媒体文件 Wjghj Project (机智的小鱼君) 版权所有
- nginx 网站 http 服务器配置文件，例如 http 重定向以及伪静态
- page 独立静态页面，早期的网站首页
- scripts 网站维护脚本
