---
comments: true
---

# 简介

[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) 是一个基于 MkDocs 的静态站点生成器主题，
专为技术文档、知识库和个人笔记设计。它开箱即用、外观现代，并且拥有丰富的扩展功能。

## 为什么选择 Material for MkDocs

| 特性 | 说明 |
|------|------|
| Markdown 优先 | 用 Markdown 写作，无需关心 HTML/CSS |
| 开箱即用 | 零配置即可获得美观的文档站点 |
| 强大搜索 | 内置全文搜索，支持高亮与建议 |
| 主题切换 | 内置明暗双主题 |
| 丰富扩展 | 支持代码高亮、图表、数学公式、提示框等 |
| 版本控制 | 文档即代码，用 Git 管理一切 |
| 自动部署 | 配合 GitHub Actions 实现 CI/CD |

## 站点架构

```
ihanofficial.github.io/
├── .github/
│   └── workflows/
│       └── ci.yml          # GitHub Actions 工作流
├── docs/                   # 文档源文件
│   ├── index.md            # 首页
│   ├── getting-started/    # 开始指南
│   ├── guide/              # 使用指南
│   └── about/              # 关于
├── mkdocs.yml              # MkDocs 配置
└── requirements.txt        # Python 依赖
```

接下来，前往 [安装与本地预览](installation.md) 了解如何在本地运行站点。
