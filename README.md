# Shen's Music · 周深私人音乐播放器

[![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL--3.0-blue.svg)](https://www.gnu.org/licenses/agpl-3.0.html)  ![Made by Wang Nan](https://img.shields.io/badge/Made%20by-Wang%20Nan-brightgreen)  ![Cloudflare Workers](https://img.shields.io/badge/Cloudflare-Workers-orange)  ![Python](https://img.shields.io/badge/Python-3.x-blue)  ![Platform](https://img.shields.io/badge/Platform-Web%20%2F%20Android-blueviolet)

基于 **Cloudflare Python Worker** 的私人音乐播放器, 音频文件存放在 **R2 对象存储**, 歌库缓存使用 **KV**, 静态资源通过 **Workers Assets** 分发。无需自有服务器, 全程运行在 Cloudflare 边缘网络。

> **本项目为个人前端学习练习, 非盈利, 不提供音视频资源下载。歌曲、歌词版权归原著作权人所有。**

## UPDATE

当前版本：**1.0.1**

版本源 `static/version.json`, 使用 `python scripts/version.py --write`同步版本, `--check` 校验

新增 WebView + Media3 Android 壳：网站提供界面、歌库和鉴权, 原生前台媒体服务负责后台播放及完整队列自动切歌

## 功能特性

架构与技术说明参见 [`JokerMusic`](https://github.com/theFool-wn/JokerMusic)

## 免责声明

本项目仅用于个人学习和技术研究, 不用于任何商业用途。项目中涉及的音乐作品、歌词等内容的著作权归原权利人所有。使用者应确保其对存储的音乐文件拥有合法的使用权, 不得通过本项目向公众传播受版权保护的内容。如有侵权, 请联系删除。

## License

This project is licensed under the **[GNU Affero General Public License v3.0 (AGPL-3.0)](https://www.gnu.org/licenses/agpl-3.0.html)**.

You are free to **use, modify, and distribute** this project, including for commercial purposes, provided that:

* You **retain the copyright and license notices**.
* You **distribute modified versions under the same license**.
* You **make the corresponding source code available** as required by the AGPL-3.0, including when modified software is used to provide a network service.

See the [LICENSE](/LICENSE) file for details.

Copyright (c) 2026 Wang Nan
