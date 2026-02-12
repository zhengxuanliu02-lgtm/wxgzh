# 黑阿猫 - 微信公众号创作工作流工具

> 一个完全运行在浏览器中的微信公众号内容创作辅助工具，支持多种创作模式。

![Version](https://img.shields.io/badge/version-v3.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ 功能特性

### 📝 手动创作
- 根据选题和核心观点生成文章
- 支持 1-2 篇文章同时生成
- 自动生成 5 个公众号标题
- 提供排版建议

### 📋 文字粘贴改写
- 将已有文章改写适应不同读者群体
- 多种改写方向（简化、深化、精简、扩展）
- 智能适配目标读者风格

### 📷 OCR 图片/PDF 识别
- 支持图片和 PDF 文件上传
- 多语言 OCR 识别（中文、英文、日文、韩文）
- 识别后可复制、改写或粘贴

### 🔗 URL 文章抓取
- 跨域抓取网页文章内容
- 自动语言检测和翻译
- 智能改写适配目标读者

### ⚙️ 多 AI 模型支持
- DeepSeek
- 豆包（字节跳动）
- Kimi（月之暗面）
- 通义千问（阿里云）

## 👥 读者群体

工具内置 5 种读者画像，自动适配写作风格：

| 读者类型 | 特点 |
|---------|------|
| 普通大众 / 吃瓜群众 | 口语化、讲故事、生活化类比 |
| 自媒体 / 内容创作者 | 专业但不晦涩、强调可操作性 |
| 产品 / 运营 / 商业人 | 数据驱动、逻辑严密、商业视角 |
| 技术从业者 | 精确、严谨、专业度高 |
| 情绪共鸣型读者 | 感性、温柔、有温度 |

## 🚀 快速开始

### 直接使用

直接打开 `wechat-v4.html` 文件即可使用。

### 本地服务器（可选）

```bash
# 使用 Python 3
python -m http.server 8000

# 使用 Node.js (http-server)
npx http-server
```

然后在浏览器访问 `http://localhost:8000/wechat-creator-tool-enhanced-v4-final.html`

## ⚙️ 配置 API

1. 打开工具页面
2. 点击「API 配置」选项卡
3. 选择 AI 模型并填写 API Key
4. 点击「保存配置」

| 模型 | 获取地址 |
|-----|---------|
| DeepSeek | https://platform.deepseek.com/ |
| 豆包 | https://console.volcengine.com/ark |
| Kimi | https://platform.moonshot.cn/ |
| 通义千问 | https://dashscope.aliyuncs.com/ |

## 🛠️ 技术栈

- HTML5 + CSS3 + Vanilla JavaScript
- [Tesseract.js](https://github.com/naptha/tesseract.js) - OCR 文字识别
- [PDF.js](https://github.com/mozilla/pdf.js) - PDF 处理
- localStorage - 本地存储 API 配置
- Fetch API - HTTP 请求

## 📁 项目结构

```
黑阿猫公众号/
├── README.md
└── wechat-creator-tool-enhanced-v4-final.html
```

## 🔐 安全说明

- 所有 API 密钥存储在浏览器本地 localStorage 中
- 不会上传到任何服务器
- 请勿在公共设备上保存 API 密钥

## 📄 许可证

MIT License

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📮 联系方式

如有问题或建议，欢迎通过 Issue 联系。

---

Made with ❤️ by 黑猫
