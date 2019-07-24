# html标签

## 文本格式化标签


标签 | 显示效果 | 
---------|----------|
 `<b></b><strong></strong>` | 文字以**粗体**方式展示（xhtml推荐使用strong） | 
 `<i></i><em></em>` | 文字以**斜体**方式展示（xhtml推荐使用em） | 
 `<s></s><del></del>` | 文字以加~~删除线~~的方式展示（xhtml推荐使用del） | 
 `<u></u>和<ins></ins>` | 文字以加下划线的方式展示（xhtml不赞成使用u）

 ## 锚点定位

```html
<a href="#id"></a>

<div id="id"></div>

```
锚点定位的特点就是利用`href="#链接的id名称"` 就是锚点链接所对应跳转的地址

## 特殊字符


特殊字符名称 | 实体标识符 |
---------|----------|
 空格 | `&nbsp;` |
 小于号 | `&lt;` |
 大于号 | `&gt;` |
版权 | `&copy;` | 
人民币 | `&yen;`

## 列表标签

- 无序列表
- 有序列表
- 自定义列表

1. 无序列表

> 无序列表的各个列表项之间没有顺序级别之分，是并列关系的

```html
<ul>
    <li>列表项1</li>
    <li>列表项2</li>
    <li>列表项3</li>
</ul>

```

2. 有序列表

> 有序列表即为有排列顺序的列表，其每个列表按照一定的顺序排列，有序列表的基本语法格式

```html
<ol>
    <li>无序列表1</li>
    <li>无序列表2</li>
    <li>无效列表3</li>
</ol>

```

## 自定义列表