# 依音 (Yiyin Music)

<p align="center">
  <img src="./resources/icon.png" width="180">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue" />
  <img src="https://img.shields.io/badge/license-MIT-green" />
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20macOS-orange" />
</p>

> **依音（Yiyin Music）** —— 专注本地音乐的跨平台播放器。  
> 无广告、无评论、无推荐算法干扰，让听歌回归纯粹。

---

## 📥 软件下载

本仓库目前仅作为安装包发布渠道，源代码暂未开放。请前往 **[Releases 页面](https://github.com/chaoahyl/Yiyin/releases)** 下载对应平台的最新版本：

* **Windows**: 下载 `.exe` 安装程序。
* **macOS**: 暂未发布，敬请期待。
* **Linux**: 暂未发布，敬请期待。

---

## 📸 应用截图

<p align="center">
  <b>精美播放界面与逐字歌词</b><br><br>
  <img src="./resources/home.png" width="600">
  <br><br>
  <img src="./resources/lyc.png" width="600">
</p>

<p align="center">
  <b>远程控制（明亮 / 深色模式）</b><br><br>
  <img src="./resources/control_light.png" width="300"> &nbsp;&nbsp;
  <img src="./resources/control_dark.png" width="300">
</p>

---

## ✨ 产品理念与特色

* **纯净本地体验**：专注本地音乐播放，不接入在线音乐平台，保护隐私，拒绝算法干扰。
* **全格式支持**：完整读取 ID3、FLAC、APE 等标签信息，支持封面、歌手、专辑自动分类。
* **沉浸式歌词**：支持读取嵌入音频标签（Tag）的歌词，提供流畅的逐字滚动效果。
* **局域网远控**：手机扫码即可控制电脑端播放、切歌，无需注册，完全本地化运行。
* **现代技术栈**：基于 Electron + Vue 3 + TypeScript 打造，界面美观且性能优秀。

---

## 🛠 功能模块一览

| 功能模块 | 说明 |
| :--- | :--- |
| **本地音乐扫描** | 扫描并导入本地文件夹，智能解析媒体库 |
| **标签信息读取** | 自动提取歌曲标题、歌手、专辑封面、年份等元数据 |
| **歌手/专辑视图** | 基于标签信息自动归类，提供直观的浏览体验 |
| **歌单管理** | 支持创建、编辑自定义歌单及收藏系统 |
| **远程控制** | 局域网内通过手机浏览器直接控制播放器（播放、切歌等） |
| **界面模式** | 内置明亮、深色及沉浸式三种视觉模式 |

---

## 📖 使用指南

### 1. 关于歌词显示
建议使用 [LDDC](https://github.com/chenmozhijin/LDDC) 或 **MusicTag** 等工具将歌词直接写入音频文件的标签（Metadata）中。依音播放器会优先读取标签内的歌词，无需额外的 `.lrc` 文件。

### 2. 远程控制
1. 确保电脑与手机处于**同一局域网**。
2. 在播放器中进入“远程控制”页面，扫描显示的二维码。
3. 连接成功后，即可在手机上远程操作播放器的基本功能。

---

## ⚖️ 免责声明

* 本软件完全免费，仅供本地音乐播放使用。
* 软件不提供任何在线音乐资源，所有音乐文件需用户自行获取。
* 用户需确保音乐文件的使用符合相关法律法规，作者不对因使用本软件而产生的版权或法律问题承担责任。
* **当前状态**：本项目目前由作者个人维护，精力有限，Bug 修复或新功能建议可能无法及时处理，敬请谅解。

---

## ⭐️ 支持作者

如果依音播放器提升了你的听歌体验，欢迎为本项目点击 **Star**。你的支持是作者持续优化最大的动力！

```text
MIT License
© 2026 依音（Yiyin Music）
