# AI-Kit

一个聚合多种 AI 工具的工具箱，基于 Next.js App Router 构建，继续保持 Apple 黑白商务风格。

![AI-Kit](https://img.shields.io/badge/AI--Kit-Tools-blue)
![Next.js](https://img.shields.io/badge/Next.js-App_Router-black)
![Apple Style](https://img.shields.io/badge/Style-Apple-gray)

---

## 工具列表

### 1. AI 早报 📰
**AI 资讯聚合页面**

- 多 RSS 源动态获取（机器之心、OpenAI、Google AI 等）
- 支持源筛选
- RSS 地址一键复制
- 响应式卡片布局

访问：`/ai-news`

---

### 2. 在线翻译 🌐
**多行文本批量翻译工具**

- 支持多行文本批量翻译
- 百度翻译 API 驱动，快速准确
- 支持多种语言互译

访问：`/translate`

---

### 3. 海龟汤生成器 🐢
**推理游戏题目生成工具**

- 智能生成海龟汤推理题目
- 支持自定义题目难度和类型（清汤/红汤/黑汤）
- 答案逐层揭示功能
- 适合聚会、团建活动

访问：`/turtle-soup`

---

## 快速开始

### 本地开发

```bash
# 克隆仓库
git clone https://github.com/Excalibur0818/AI-Kit.git
cd AI-Kit

# 安装依赖
npm install

# 启动 Next.js 开发服务器
npm run dev
```

访问 `http://localhost:3000`

### 生产构建

```bash
npm run build
npm run start
```

### GitHub Pages 部署

1. Fork 本仓库
2. 进入 Settings → Pages
3. Source 选择 `Deploy from a branch`，Branch 选择 `main`
4. 等待部署完成

---

## 技术栈

- **前端框架**: Next.js App Router + React + TypeScript
- **样式**: Tailwind CSS
- **图标**: lucide-react
- **样式**: Apple 黑白商务风格
- **字体**: DM Sans + Playfair Display
- **托管**: Vercel

---

## 项目结构

```
AI-Kit/
├── app/                    # Next.js App Router（页面与 API 路由）
├── components/             # 共享组件与客户端逻辑
├── lib/                    # 共享数据和工具函数
├── README.md               # 本文档
└── LICENSE                 # MIT 协议
```

---

## 配置说明

### API 路由

- RSS 代理：`/api/rss-proxy?url=https://example.com/feed`
- 百度翻译代理：`/api/translate`

---

## 注意事项

1. 项目已全面迁移至 Next.js，所有页面与 API 均基于 App Router。

---

## 开源协议

[MIT License](./LICENSE)

---

## 联系

- GitHub: [@Excalibur0818](https://github.com/Excalibur0818)
- 邮箱: excalibur0818@gmail.com

---

如果觉得这个工具箱有用，欢迎 Star ⭐ 支持！
