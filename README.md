# NetworkPanel-Lite
原始作者：Whoami @ljxi
修改者 @cxplay
源仓库 https://github.com/ljxi/NetworkPanel
本站基于原始作者的版本做了一些调整, 仅保留前端网络测试功能.

移除了依赖于第三方的:
QQ 登录与排行榜
百度统计
51la 统计
IP 地址查询功能

移除了依赖于后端的:
用户管理
测速日志上传
测速入口

其他方面:
调整页面元素
将前端静态资源端点从 cdn.iocdn.cc (一为云, 括彩云提供) 替换为 cdnjs.cloudflare.com (Cloudflare 提供).

# 网络面板

测试您的网速，多地查询您的IP地址，同时具备网络延迟实时检测，流量杀手，流量消耗器，流量消失器

支持定量完成，支持多线程，适配iOS后台运行。

如果你不了解如何打包vite项目，请[点此下载](https://github.com/ljxi/NetworkPanel/archive/refs/heads/gh-pages.zip)解压文件部署到服务器根目录即可

[Demo](https://ljxi.github.io/NetworkPanel/)

这是vue3重写版本，旧版本在old分支，这次重写，主要增加了以下特性：

1.支持添加自定义节点

2.启动之后更改节点与线程数立即生效（旧版本需要重新启动）

3.线程数和后台开关状态保存

4.更友好的界面

5.榜单功能(需要后端支持)
