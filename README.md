# 🪄 Image Background Remover

纯浏览器端的图片背景移除工具，无需服务器，图片处理在本地浏览器完成。

## Features

- 🚀 **纯前端** - 无需上传文件到任何服务器
- 🔒 **隐私安全** - 图片永远不会离开你的设备
- 🤖 **AI 驱动** - 使用 @imgly/background-removal 模型
- 📱 **响应式** - 支持桌面和移动端
- 🎨 **即时下载** - 处理完直接下载 PNG

## Tech

- [@imgly/background-removal](https://www.npmjs.com/package/@imgly/background-removal) - 浏览器端 ML 模型
- 原生 HTML/CSS/JS - 零框架依赖

## Usage

打开 `index.html` 即可使用（无需任何构建步骤）。

支持的浏览器：Chrome 90+, Firefox 90+, Safari 15+, Edge 90+

## Deploy

一键部署到 Cloudflare Pages（免费）：

```bash
# 安装 Wrangler CLI
npm install -g wrangler

# 部署
wrangler pages deploy dist --project-name=image-background-remover
```

或直接在 GitHub 连接 Cloudflare Pages 实现 CI/CD 自动部署。
