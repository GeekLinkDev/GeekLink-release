<p align="center">
  <img src="https://raw.githubusercontent.com/GeekLinkDev/GeekLink-release/main/assets/icon.png" width="128" alt="极客连字幕工厂">
</p>

<h1 align="center">极客连字幕工厂</h1>
<h3 align="center">GeekLink Subtitle Factory</h3>

<p align="center">
  <strong>拖入 50 个视频，导出 50 个带字幕的视频。一键搞定。</strong>
</p>

<p align="center">
  <a href="https://github.com/GeekLinkDev/GeekLink-release/releases/latest">
    <img src="https://img.shields.io/github/v/release/GeekLinkDev/GeekLink-release?label=%E4%B8%8B%E8%BD%BD&style=for-the-badge" alt="最新版本">
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/%E5%B9%B3%E5%8F%B0-macOS-black?style=for-the-badge&logo=apple" alt="macOS">
  &nbsp;
  <img src="https://img.shields.io/badge/%E8%BF%90%E8%A1%8C-100%25%20%E6%9C%AC%E5%9C%B0-green?style=for-the-badge" alt="100% 本地">
</p>

<p align="center">
  <strong>中文</strong> | <a href="./README.md">English</a>
</p>

---

<p align="center">
  <a href="https://www.bilibili.com/video/BV1oWfnBYEUH/">
    <img src="https://raw.githubusercontent.com/GeekLinkDev/GeekLink-release/main/assets/video_cover.jpg" width="600" alt="观看演示">
    <br>
    <strong>在 Bilibili 观看演示视频</strong>
  </a>
</p>

---

## 这是什么？

极客连字幕工厂是一条 macOS 上的**批量字幕生产线**。

市面上的字幕工具几乎都是一次处理一个视频。极客连可以**一次性处理所有视频** —— 语音识别、翻译、编辑、样式调整、导出，一条龙完成。

导入 2 个视频也行，200 个也行。设置一次，点击运行，等着收工。

## 核心功能

**批量优先的工作流**
- 一次性导入整个视频库（MP4、MOV、MKV、M4V、WebM）
- 一条进度条贯穿所有视频 —— 不再看着进度条每个视频归零重来
- 批量字幕编辑器：在同一个界面里审阅和修改所有视频的字幕

**AI 语音识别**
- Whisper（多语言，支持 14 种语言）+ FunASR（中文专项优化）
- Silero VAD 静音预处理，消除背景音乐产生的幻觉字幕

**多引擎翻译**
- 谷歌翻译（免费）/ DeepSeek AI（上下文理解更强）
- 支持 14 种语言互译
- 可为每个项目自定义 AI 翻译提示词

**两种导出模式**
- 烧录字幕 —— 永久嵌入画面，任何播放器都能看
- 可开关字幕 —— 观众可以自行开启或关闭

**所见即所得的样式编辑器**
- 字体、字号、颜色、描边、阴影、位置
- 毛玻璃背景条
- 导出前实时预览效果

**100% 本地运行，保护隐私**
- 你的视频不会离开你的电脑
- 不上传云端，不按分钟收费
- 在 Apple Silicon（M1/M2/M3/M4）上原生运行

## 截图

| 仪表盘 | 字幕编辑器 |
|:-:|:-:|
| ![仪表盘](https://raw.githubusercontent.com/GeekLinkDev/GeekLink-release/main/assets/dashboard.png) | ![编辑器](https://raw.githubusercontent.com/GeekLinkDev/GeekLink-release/main/assets/editor.png) |

## 快速开始

1. 从 [Releases](https://github.com/GeekLinkDev/GeekLink-release/releases/latest) 下载最新的 `.dmg` 安装包
2. 将 `GeekLink.app` 拖入「应用程序」文件夹
3. 打开应用，把视频拖进去
4. 选择语言设置，点击「运行」
5. 在编辑器中审阅字幕，然后导出

## 支持的语言

| 语言 | 语音识别 | 翻译 |
|------|:-:|:-:|
| 中文（简体/繁体） | Whisper + FunASR | 谷歌 / DeepSeek |
| 英语 | Whisper | 谷歌 / DeepSeek |
| 日语 | Whisper | 谷歌 / DeepSeek |
| 韩语 | Whisper | 谷歌 / DeepSeek |
| 法语 | Whisper | 谷歌 / DeepSeek |
| 德语 | Whisper | 谷歌 / DeepSeek |
| 西班牙语 | Whisper | 谷歌 / DeepSeek |
| 意大利语 | Whisper | 谷歌 / DeepSeek |
| 葡萄牙语 | Whisper | 谷歌 / DeepSeek |
| 俄语 | Whisper | 谷歌 / DeepSeek |
| 阿拉伯语 | Whisper | 谷歌 / DeepSeek |
| 泰语 | Whisper | 谷歌 / DeepSeek |
| 越南语 | Whisper | 谷歌 / DeepSeek |

## 系统要求

- macOS 12.0+（Monterey 或更高版本）
- 推荐 Apple Silicon（M1/M2/M3/M4）
- 也支持 Intel Mac（处理速度较慢）
- 最低 8 GB 内存，批量处理推荐 16 GB

## 反馈与问题

发现 Bug 或有功能建议？欢迎提交 [Issue](https://github.com/GeekLinkDev/GeekLink-release/issues)。

---

<p align="center">
  由 <strong>极客连</strong>（GeekLink）用心打造
</p>
