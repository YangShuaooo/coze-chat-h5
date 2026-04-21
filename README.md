# AIPM面试小助手

这是一个专为AI产品经理面试准备的智能聊天助手，基于Coze API构建，提供面试问题、技术解析和面试模拟功能。

## 🎯 功能特点

- **随机面试问题** - 每次刷新页面都会显示不同的AI产品经理相关问题
- **实时流式输出** - 采用打字机效果，让回答过程更加生动
- **Markdown渲染** - 支持代码块、列表、粗体等Markdown格式
- **紧凑内容布局** - 优化了标题、段落和列表的间距，使内容更加紧凑美观
- **响应式设计** - 支持电脑和手机等各种设备访问
- **一键开始面试** - 快速进入面试模拟模式

## 🚀 快速开始

### 前置要求

- 安装 Node.js (版本 12 或更高)
- 有效的 Coze API 密钥

### 本地运行

1. 确保你在项目目录下
2. 运行服务器：
   ```bash
   node server.js
   ```
3. 在浏览器中访问：
   - 本地访问：http://localhost:3000
   - 局域网访问：查看终端显示的 IP 地址

## 🌐 部署方案

### 方案一：GitHub Pages (推荐)

1. 将项目推送到GitHub仓库
2. 进入仓库设置 -> Pages
3. 选择源为 main 分支，保存
4. 稍等几分钟，获得访问地址

### 方案二：Vercel

1. 注册 Vercel 账号：https://vercel.com
2. 安装 Vercel CLI：
   ```bash
   npm install -g vercel
   ```
3. 登录并部署：
   ```bash
   vercel login
   vercel
   ```

### 方案三：Netlify

1. 注册 Netlify 账号：https://netlify.com
2. 直接上传项目文件夹到 Netlify
3. 或者使用 Netlify CLI 部署：
   ```bash
   npm install -g netlify-cli
   netlify login
   netlify init
   netlify deploy --prod
   ```

## 📁 文件说明

- `index.html` - 主页面文件，包含所有前端代码和功能
- `package.json` - 项目配置文件
- `README.md` - 项目说明文档
- `.nojekyll` - GitHub Pages配置文件

## 🔧 技术栈

- **前端**：HTML5 + CSS3 + 原生 JavaScript
- **后端**：Node.js (本地服务器)
- **API**：Coze API
- **部署**：支持静态网站托管

## 🎨 界面特点

- **现代化设计** - 简洁美观的聊天界面
- **流畅的交互** - 实时流式输出和打字机效果
- **智能建议** - 每次刷新显示不同的面试问题
- **清晰的布局** - 优化的内容间距和排版

## 💡 使用场景

- **面试准备** - 练习AI产品经理常见面试问题
- **技术学习** - 了解RAG、Prompt Engineering等AI相关技术
- **模拟面试** - 通过"开始面试"功能进行完整的面试模拟

## 🔑 注意事项

1. 确保在 `index.html` 中配置了正确的 Coze API 密钥
2. 局域网访问需要设备在同一网络下
3. 公网部署前建议测试本地功能正常

## 📄 许可证

ISC

---

**祝你面试顺利！** 🎉