---
comments: true
---

# Markdown 扩展

Material for MkDocs 在标准 Markdown 之上提供了丰富的扩展，让文档更具表现力。

## 删除线与下划线

```markdown
~~删除线~~
++下划线++
==高亮==
```

效果：~~删除线~~、++下划线++、==高亮==。

## 上下标

```markdown
H~2~O
A^T^
```

效果：H~2~O、A^T^。

## 键盘按键

```markdown
++ctrl+shift+n++
```

效果：++ctrl+shift+n++。

## 任务列表

```markdown
- [x] 已完成
- [ ] 未完成
```

效果：

- [x] 已完成
- [ ] 未完成

## Emoji

```markdown
:smile: :rocket: :tada:
```

效果：:smile: :rocket: :tada:

## 脚注

```markdown
这里有一个脚注[^1]。

[^1]: 脚注内容。
```

## 数学公式

行内公式：$E = mc^2$

块级公式：

$$
\frac{n!}{k!(n-k)!} = \binom{n}{k}
$$

更多语法请参考 [LaTeX 数学公式指南](https://www.latex-project.org/)。
