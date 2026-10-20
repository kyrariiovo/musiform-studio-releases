# Musiform studio

Music Formation studio · 舞蹈与行进管乐队形编排软件。

此仓库只用于公开分发安装包与更新信息。源码在独立私有仓库维护。

## 下载 Mac 版本

[最新版本和安装包](https://github.com/kyrariiovo/musiform-studio-releases/releases/latest)

| Mac 芯片 | 安装包 |
| --- | --- |
| Apple Silicon（M 系列） | [arm64 DMG](https://github.com/kyrariiovo/musiform-studio-releases/releases/latest/download/Musiform-studio-0.7.0-mac-arm64.dmg) |
| Intel | [x64 DMG](https://github.com/kyrariiovo/musiform-studio-releases/releases/latest/download/Musiform-studio-0.7.0-mac-x64.dmg) |

最低系统：macOS 13 Ventura。支持 macOS 14 Sonoma、15 Sequoia、26 Tahoe、27。macOS 12 及以前暂不支持。Release 同时提供两种架构的 ZIP 和 SHA256SUMS.txt。

打开 DMG，将 **Musiform studio** 拖到 **应用程序**。已有旧版本时，请先保存工程、退出软件，再替换。工程后缀为 `.mfs`。

当前版本采用本地 ad-hoc 签名，尚无 Developer ID 分发签名和 Apple 公证。macOS 可能要求在“系统设置 → 隐私与安全性”确认打开。请核对本仓库来源与 SHA256SUMS.txt，无需关闭 Gatekeeper 或 SIP。

Apple Silicon 原生应用和通过 Rosetta 运行的 Intel 包已验证；各旧版 macOS 及实体 Intel Mac 尚未逐一实机测试。

## 软件内更新

应用菜单 **Musiform studio → 检查更新…**。默认启动时检查稳定版，可关闭。软件会按芯片类型选择安装包、下载并核对大小与 SHA-256，再由用户打开 DMG 安装。更新不会自动关闭工程。

[稳定版更新清单](https://github.com/kyrariiovo/musiform-studio-releases/releases/latest/download/update.json)

## 使用与版权

项目类型在新建时选择舞蹈或行进管乐；支持音乐、按秒或拍数编排、队形页面 PDF/图片导出。第三方组件许可随应用提供。本仓库公开提供下载，不代表开放软件源码或授予开源许可。
