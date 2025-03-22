# HaloWeekly 博客

> 不定期分享一个有趣的技术话题

这是一个基于 Hexo 构建的个人博客项目，使用 Async 主题，旨在分享技术见解和有趣话题。

## 特性

- 基于 Hexo 7.3.0 构建
- 使用现代化的 Async 主题
- 支持文章字数统计
- 支持分类、标签和归档
- 响应式设计，支持移动端访问
- 集成 highlight.js 代码高亮

## 快速开始

### 环境要求

- Node.js
- npm 或 yarn

### 安装

1. 克隆项目

```bash
git clone [your-repository-url]
cd week_article
```

2. 安装依赖

```bash
npm install
```

### 本地开发

启动本地服务器：

```bash
npm run server
```

访问 `http://localhost:4000` 预览博客。

### 写作

创建新文章：

```bash
hexo new "文章标题"
```

### 生成静态文件

```bash
npm run build
```

## 项目结构

```
.
├── _config.yml      # 站点配置文件
├── _config.async.yml # Async主题配置文件
├── source           # 文章源文件
│   ├── _posts      # 博客文章
│   └── about       # 关于页面
└── themes          # 主题文件
```

## 主要依赖

- hexo: ^7.3.0
- hexo-theme-async: ^2.2.4
- hexo-wordcount: ^6.0.1
- 更多依赖请查看 package.json

## 自动更新

本项目使用 GitHub Dependabot 进行依赖自动更新，确保项目依赖始终保持最新状态。

## 许可证

[MIT License](LICENSE)