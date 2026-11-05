# 歇刻 · 安装包与在线更新

歇刻是一款 macOS 休息提醒应用。本仓库仅用于分发安装包、签名与更新清单，不包含应用源码。

当前面向 macOS 13.3 及以上的 Apple Silicon 设备，仍处于预览阶段。

首次使用需手动安装支持更新的正式包；后续从应用“关于 → 在线更新”检查、下载并安装，完成后手动重启。开发包不参与正式更新。

更新包使用 Tauri Updater 签名校验；该签名不等于 Apple Developer ID 签名或公证。实际签名、公证与验收范围以每个版本的发布说明为准。

## 开源来源

基于 [Stretchly](https://github.com/hovancik/stretchly) 改造。Copyright (c) Jan Hovancik and contributors。歇刻改造 © haers。

采用 BSD-2-Clause 许可证，完整许可与免责声明随每次发布的 LICENSE 文件及应用资源分发。

本仓库不得包含源码仓库凭据、用户设置或更新签名私钥。
