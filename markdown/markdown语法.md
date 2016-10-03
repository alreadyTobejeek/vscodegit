># 一级标题

## 二级标题

### 三级标题（#依次递增字体依次减小，#后有空格）

#### 四级标题

##### 五级标题

###### 六级标题

># 列表
### 在 Markdown 下，列表的显示只需要在文字前加上 - 或 * 即可变为无序列表，有序列表则直接在文字前加1. 2. 3. 符号要和文字之间加上一个字符的空格。
#### 无序列表

* 1
* 2
* 3
- 4
- 5

#### 有序列表

1. 1
2. 2
3. 3

># 引用
- 只需要在文本前加入 > 这种尖括号（大于号）即可
- ">#"可以组合使用，要使这些符号显示出来，用引号包围

# 插入链接和图片
> 插入链接与插入图片的语法很像，区别在一个 !号

图片为：![]()

链接为：[]()

[百度](http://baidu.com)

![图片](http://cdn.sspai.com/attachment/thumbnail/2014/04/15/d38aa229b1c8c9119b6a03a61ba113b810f9a_mw_800.jpg)

># **粗体和斜体**
- 用两个 * 包含一段文本就是粗体的语法，用一个 * 包含一段文本就是斜体的语法。

**cjh**

*cjh*

># 代码
* 用三个 ` 把中间的代码包裹起来

```
var gulp = require('gulp'),
    plugins = require('gulp-load-plugins')();
```

``` python
@requires_authorization
def somefunc(param1='', param2=0):
    '''A docstring'''
    if param1 > param2: # interesting
        print 'Greater'
    return (param2 - param1 + 1) or None
class SomeClass:
    pass
>>> message = '''interpreter
... prompt'''
```

># 表格
* 用||包围，第二行为格式，: 位置为对齐方向，默认左对齐

|wuhan     |fuzhou      |xianyou   |
|:---------|:----------:|---------:|
|col1.1    |col1.2      |col1.3    |
|col2.1    |col2.2      |col2.3    |
|col3.1    |col3.2      |col3.3    |

># 分割线
* 分割线的语法只需要三个 * 号或-号

***

># 带有超链接文字

- Markdown 是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档，然后转换成格式丰富的HTML页面。    —— [维基百科](http://www.baidu.com)

># LaTeX公式

- 可以创建行内公式，例如$\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$
- 块级公式：$$ x=\dfrac{-b\pm\sqrt{b^2-4ac}}{2a} $$

># 流程图
- 必须带有```flow  ```(flow为关键字)
```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```
># 时序图

```sequence
Alice->Bob: Hello Bob!
Note right of Bob: Bob thinks
Bob-->Alice: I am a thinker!
```
># 笔记本和标签

**马克飞象**增加了`@(笔记本)[标签A|标签B]`语法, 以选择笔记本和添加标签。 **绑定账号后**， 输入`(`自动会出现笔记本列表，请从中选择。



<table style="border: 1px solid red">
    <thead>
        <tr>
            <td >表格1</td>
            <td>表格2</td>
        </tr>
    </thead>
</table>

<dl>
    <dt>dt内容</dt>
    <dd>内容1</dd>
    <dd>内容2</dd>
</dl>

