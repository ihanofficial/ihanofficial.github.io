# 提示与警告框

Admonition（提示框）用于突出显示重要信息。基本语法：

```markdown
!!! note "标题"
    这里是内容。
```

## 内置类型

!!! note "Note"
    一般性提示信息。

!!! abstract "Abstract"
    摘要、总结性信息。

!!! info "Info"
    补充说明信息。

!!! tip "Tip"
    有用的小技巧。

!!! success "Success"
    成功完成的操作。

!!! question "Question"
    常见问题。

!!! warning "Warning"
    需要注意的事项。

!!! failure "Failure"
    失败或错误情况。

!!! danger "Danger"
    危险操作，可能导致数据丢失。

!!! bug "Bug"
    已知问题。

!!! example "Example"
    示例代码或用法。

!!! quote "Quote"
    引用内容。

## 可折叠提示框

使用 `???` 创建默认折叠的提示框，使用 `???+` 创建默认展开的：

```markdown
??? note "点击展开"
    这里是隐藏的内容。

???+ note "默认展开"
    这里是内容。
```

效果：

??? note "点击展开"
    这里是隐藏的内容。

???+ note "默认展开"
    默认展开，点击标题可折叠。

## 嵌套提示框

提示框可以嵌套使用：

!!! note "外层"
    外层内容。

    !!! warning "内层警告"
        内层警告内容。
