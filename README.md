# 留白 · Liubai

原生 macOS 待办与专注计时器。黑白灰界面、专注圆环、休息切换与本地保存。

## 下载

- [最新版和更新说明](https://github.com/Raphaelque/liubai-releases/releases/latest)
- 选择对应版本的 **DMG**，打开后将“留白”拖到 Applications（应用程序），再从应用程序打开。
- 系统要求：**macOS 14 或以上**，支持 Apple 芯片和 Intel Mac。
- 留白常驻屏幕顶部的菜单栏，不在程序坞显示；可从菜单栏打开主窗口、设置或退出。

## 应用内更新

从 0.2.0 起，状态栏菜单和设置均可“检查更新”，由 Sparkle 完成下载、签名校验、安装和重启。自动检查、自动下载可在设置中开关。0.1.0 用户需要手动安装 0.2.0 一次。

- [Sparkle 更新索引](https://github.com/Raphaelque/liubai-releases/releases/latest/download/appcast.xml)
- [版本清单](https://github.com/Raphaelque/liubai-releases/releases/latest/download/latest.json)
- 更新归档使用 Ed25519 签名；私钥不包含在此仓库或应用中。

## 数据与权限

任务、设置和计时状态保存在本机用户目录，不包含在安装包中。日历仅在用户主动启用后请求系统授权。

## 社区分发说明

本项目采用社区分发方式，不通过 Mac App Store。当前安装包未经过 Apple 公证，macOS 可能显示安全提示；本项目不会修改系统的安全设置。

此仓库仅用于分发安装包、更新索引和更新说明，不托管应用源码。
