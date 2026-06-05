# English Reading Assistant 英语阅读助手

> **一个基于 AI 的沉浸式英语阅读工具** — 点击查词、AI 翻译、OCR 识别、生词本管理，让英文阅读流畅无阻。

<div align="center">

![GitHub](https://img.shields.io/badge/license-MIT-blue)
![Language](https://img.shields.io/badge/language-HTML%2FCSS%2FJS-orange)
![AI](https://img.shields.io/badge/AI-DeepSeek-brightgreen)

</div>

---

## ✨ 功能亮点

| 功能 | 描述 |
| --- | --- |
| **📖 英文阅读模式** | 粘贴英文文章，点击任意单词即时查词典（音标 + 中文释义） |
| **🌐 中译英模式** | 粘贴中文文本，AI 自动翻译成英文 |
| **🖼️ 图片 OCR** | 从截图或图片中提取英文文字，自动转为可交互文章 |
| **📂 多格式导入** | 支持 TXT、DOCX、PDF、图片文件拖拽或上传 |
| **📚 生词本** | 自动收藏查过的单词，支持导出 TXT / CSV（可导入 Anki） |
| **🤖 AI 驱动** | 接入 DeepSeek API，查词翻译质量高、语境准确 |
| **💾 本地持久化** | API Key 和生词本自动保存在浏览器中，关闭不丢失 |

---

## 🚀 快速开始

### 方式一：直接打开（推荐）

1. 下载 English Reading Assistant.html 到本地
2. 双击用浏览器打开即可使用
3. 在页面右上角输入你的 DeepSeek API Key
4. 开始阅读！

### 获取 API Key

本工具需要 DeepSeek API Key 才能工作：

1. 访问 platform.deepseek.com 注册账号
2. 在 API Keys 页面创建一个新的 Key（以 sk- 开头）
3. 复制 Key 粘贴到工具的 API Key 输入框中
4. Key 会保存在浏览器本地，下次打开无需重新输入

---

## 📖 使用指南

### 英文阅读模式

① 粘贴/导入英文文章 → ② 自动渲染为可交互文本 → ③ 点击任意单词查词

- **点击单词**：弹出浮动窗口显示音标和中文释义，单词下方绿色标记表示已缓存
- **自动分段**：按段落和句子分割，排版清晰

### 中译英模式

切换到"中译英"标签 → 粘贴中文 → AI 自动翻译为英文

### 文件导入

支持四种方式：

- **拖拽文件**：将文件直接拖入上传区域
- **点击选择**：点击上传区域选择文件
- **Ctrl+V 粘贴**：直接粘贴截图到页面中
- **手动粘贴**：将文本粘贴到文本框中

---

## 📁 文件导入支持

| 格式 | 说明 |
| --- | --- |
| **TXT** | 纯文本文件，直接读取内容 |
| **DOCX** | Word 文档，自动提取纯文本 |
| **PDF** | PDF 文件，逐页提取文字内容 |
| **图片 (PNG/JPG/WebP)** | 通过 Tesseract.js OCR 引擎识别英文文字 |

---

## 📚 生词本

- 点击文章中任意单词自动加入生词本
- 右侧边栏显示单词和中文释义
- 支持导出 TXT / CSV，可导入 Anki 等记忆软件
- 支持一键清空所有生词

---

## ❓ 常见问题

### 需要联网吗？
需要。查词和翻译依赖 DeepSeek API，需要网络连接。

### API Key 安全吗？
Key 只保存在浏览器 localStorage 中，不会上传到任何服务器。

### 支持移动端吗？
支持。页面自适应布局。

---

## 🛠 技术栈

- **前端**：HTML5 + CSS3 + JavaScript，单页应用
- **AI 接口**：DeepSeek API（查词 + 翻译）
- **OCR 引擎**：Tesseract.js（浏览器端识别）
- **PDF 解析**：pdf.js
- **DOCX 解析**：mammoth.js
- **存储**：浏览器 localStorage

---

## 📄 许可

MIT License

