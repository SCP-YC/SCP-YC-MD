# SCP-YC-MD
SCP-YC文章所采用的类Markdown语法。

想要撰写SCP-YC-MD文档？我们开发了基于Markdown的SCP-YC-MD语法，用于撰写SCP-YC分部的文档。我们的文档使用HTML进行展示，但是HTML的维护较为繁琐且不直观，我们使用了SCP-YC-MD语法来实现类Wiki语法的功能，并在书写完成后使用 [[SCP-YC-MD -> HTML 转换器]](SCP-YC.github.io/SCP-YC-MD/convert.html) 进行转换。另外，为了便于SCP-YC-MD的书写，我们开发了一款名为SCP-YC-MD的Sublime Text Package，来实现在Sublime Text里书写SCP-YC-MD的语法高亮。

### SCP-YC-MD语法：

> 基于Markdown开发的一款用于SCP文档书写的语法

因为基于Markdown，所以大多数的语法都一致，使用过Markdown的人能够很容易的学会此语法。

#### 语法讲解：

> 讲解格式：[:符号:]、<内容/变量>

- 标题：<1~6个#，分别对应1~6级标题>[:空格:]<标题>
- 粗体：\*\*<文字>\*\*
- 斜体：\*<文字>\*
- 粗斜体：\*\*\*<文字>\*\*\*
- 删除：\~\~<文字>\~\~
- 链接：\[<网页名称>\]\(<链接>\)
- 图片：\!\[<图片名称>\]\(<图片链接>\)

**以上与Markdown语法一致**

---

**以下为新增/修改语法**

- 引用：

  ```
  ​```
  <内容>
  ​```
  ```

- 折叠：

  ```
  [---]
  <展开信息>
  <折叠信息>
  <内容>
  [---]
  ```

### SCP-YC-MD包：

> 用于实现Sublime中SCP-YC-MD的编写的语法高亮

下载请转到 [[Release]](https://github.com/SCP-YC/SCP-YC-MD/releases) 。

仓库中的 [[SCP-YC-MD]](https://github.com/SCP-YC/SCP-YC-MD/blob/master/SCP-YC-MD) 文件夹内即为此Sublime Package的源代码。

**效果如下：**

![示例](https://s2.ax1x.com/2019/08/06/ehgrHe.png)

### SCP-YC-MD -> HTML 转换器：

> 用于将SCP-YC-MD语法的文档转换为可展示的HTML语法

转换器链接：[[SCP-YC-MD -> HTML 转换器]](SCP-YC.github.io/SCP-YC-MD/convert.html)

