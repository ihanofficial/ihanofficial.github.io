---
comments: true
---

# 安装与本地预览

## 前置要求

- [Python](https://www.python.org/) 3.8+
- [pip](https://pip.pypab.io/en/stable/)（Python 包管理器）
- [Git](https://git-scm.com/)

## 安装依赖

克隆仓库后，在项目根目录执行：

```bash
# 创建虚拟环境（推荐）
python -m venv venv
source venv/bin/activate        # macOS / Linux
# venv\Scripts\activate         # Windows

# 安装依赖
pip install -r requirements.txt
```

## 本地预览

```bash
mkdocs serve
```

执行后，终端会输出类似信息：

```
INFO    -  Building documentation...
INFO    -  Cleaning site directory
INFO    -  Documentation built in 0.52 seconds
INFO    -  [11:09:04] Watching paths for changes: 'docs', 'mkdocs.yml'
INFO    -  [11:09:04] Serving on http://127.0.0.1:8000/
```

浏览器打开 **http://127.0.0.1:8000/** 即可预览。修改文档后页面会自动刷新。

## 构建静态站点

```bash
mkdocs build
```

生成的静态文件位于 `site/` 目录，可直接部署到任意静态托管服务。

!!! warning "注意"
    `site/` 目录已被 `.gitignore` 忽略，不应提交到仓库。

## 部署方式

本项目使用 GitHub Actions 自动部署，详见仓库中的 `.github/workflows/ci.yml`。
每次向 `main` 分支推送代码，GitHub Actions 会自动构建并发布到 GitHub Pages。
