# 宝藏船 Windows 桌面版

本仓库提供宝藏船的安装包、版本说明及应用内更新清单。

首次使用请从 [最新版本](https://github.com/yangyangyangQAQ/treasure-ship-releases/releases/latest) 下载 Windows x64 安装包并安装。已经安装支持更新的版本后，点击应用顶部的更新入口，检查新版、后台下载，再选择“安装并重启”。

下载支持取消和重试；未保存内容与正在运行的任务会阻止重启。已保存的本地比赛数据与模型目录在升级时保留。

安装包使用 Tauri updater 完整性签名，应用会验证更新包；此签名与 Windows Authenticode 发布者证书不同。每版提供 EXE、对应 SIG、SHA256 清单及 latest.json。版本包发布到固定版本 tag，更新清单通过 HTTPS 提供匿名访问，客户端无需 GitHub token。

这里发布交付所需客户端资源及二进制文件。源码仓库独立管理。
