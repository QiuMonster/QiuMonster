# Mineradio 登录助手

基于 Manifest V3 的 Chrome 浏览器扩展，帮助 Mineradio 读取 [music.163.com](https://music.163.com) 的登录 Cookie，实现一键登录。
下载请点击[mineradio_web_extension v0.1.0](https://github.com/QiuMonster/QiuMonster/releases/download/v0.1.0/mineradio_web_extension.zip)，或到当前仓库的发布版本处下载。
## 功能

- 读取网易云音乐域名下的登录 Cookie
- 通过 content script 桥接扩展后台与 Mineradio 页面
- 验证 Cookie 有效性（检查 `MUSIC_U` 是否存在）
- 配合 Mineradio 前端实现免扫码一键登录

## 安装

1. 打开 Chrome / Edge 浏览器，进入 `chrome://extensions`
2. 开启「开发者模式」
3. 点击「加载已解压的扩展程序」，选择本目录

## 使用

1. 先在 [music.163.com](https://music.163.com) 登录你的网易云账号
2. 打开 Mineradio 应用
3. 在登录弹窗中选择「浏览器扩展登录」
4. 扩展会自动读取 Cookie 并完成登录

## 版权与授权

Copyright (C) 2026 QiuMonster.

本项目为独立开发，采用 **GNU General Public License v3.0 (GPLv3)** 发布。详见 [LICENSE](./LICENSE)。

第三方依赖和第三方服务分别遵循其各自授权与服务条款。
