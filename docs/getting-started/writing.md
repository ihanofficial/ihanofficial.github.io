# 编写文档

## 创建新页面

在 `docs/` 目录下创建 Markdown 文件即可。例如：

```
docs/
├── index.md
└── notes/
    └── my-note.md      # 新页面
```

然后在 `mkdocs.yml` 的 `nav` 中引用它：

```yaml
nav:
  - 首页: index.md
  - 笔记:
      - 我的笔记: notes/my-note.md
```

## Markdown 基础语法

### 标题

```markdown
# 一级标题
## 二级标题
### 三级标题
```

### 列表

```markdown
- 无序列表项
- 另一项

1. 有序列表项
2. 另一项
```

### 链接与图片

```markdown
[链接文字](https://example.com)
![图片描述](path/to/image.png)
```

### 表格

```markdown
| 列1 | 列2 | 列3 |
|-----|-----|-----|
| A   | B   | C   |
```

## 文件命名规范

- 使用小写英文与连字符：`my-page.md`，避免 `My Page.md`
- 目录结构保持扁平，避免过深嵌套
- 首页统一命名为 `index.md`

!!! tip "建议"
    每篇文档开头加一个一级标题（`#`），作为页面主标题。
