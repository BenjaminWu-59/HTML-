# HTML标签


### 一些必备的英语

|   英文    |    翻译    |    英文     |    翻译    |
| :-------: | :--------: | :---------: | :--------: |
|  heading  |    标题    |    order    | 顺序、秩序 |
|   body    | 身体、正文 |   ordered   |  有顺序的  |
| paragraph |    段落    |  unordered  |   无序的   |
|  section  |   章、节   | description |    描述    |
|  article  |    文章    |    term     |    术语    |
|   main    |    主要    |    data     |    数据    |
|   aside   |   旁边的   |    quota    |    引用    |
|  anchor   |  锚、定点  |    block    |     块     |
|  strong   |  重要、强  |   inline    | 内联、行内 |
| emphasis  |    强调    |    break    |    打断    |



### 辅助教材

一个用于教学及参考手册作用的网站：[网道](wangdoc.com)



### 插件的推荐

1. vscode中的：**prettier** 自动格式化
2. 分享代码的**JSbin** ：

- 可以保存快照；
- 可以设置偏好；
- 可以使用ctrl+/对齐代码；
3. 代码沙盒：**codesanbox.io**

   

### html起手式

`<!DOCTYPE html>`   

**文档类型**

`<html lang="en">`   

**html标签，lang表示语言类型，可以将其改为zh-cn**

`<head>` 

**表示头部位置（通常写一些看不见的东西）**

       ` <meta charset="UTF-8">`  

​        **文件的字符编码**

        `<meta name="viewport" content="width=device-width, initial-scale=1.0">`

​         **禁用缩放，兼容手机**

​        `<meta http-equiv="X-UA-Compatible" content="ie=edge">`

​         **告诉IE使用最新内核**

​         <font face="黑体" color=green>注意：这段代码有可能你的VScode是没有的，可以使用[自定义模板](https://www.jianshu.com/p/fe027008dacf)进行设置</font>

​         `     <title>Document</title>`

​         **标题**


   ``` 

</head>

<body>

</body>

</html>
   ```

### html章节标签

其意义在于像书或文章一样表示其层级

- 标题 h1~h6
- 章节 section
- 文章 article
- 段落 p
- 头部 header <font face="黑体" color="green">通常用于广告</font>
- 脚部 footer  <font face="黑体" color="green">通常用来注释版权所有等信息</font>
- 主要内容 main
- 旁支内容 aside
- 划分 div

### 全局属性

本属性即可以在所有html标签都可以使用的属性，如:
                                                               `<div class="middle">`

- class     <font face="黑体" color="green">用来对网页元素进行分类。如果不同元素的`class`属性值相同，就表示它们是一类的</font>
- contenteditable    <font face="黑体" color="green">使任何一个元素变得可以直接编辑,如可以让style元素进入body区，直接进行调试</font>
- hidden   <font face="黑体" color="green">隐藏任何一个元素，可通过css调出</font>
- id   <font face="黑体" color="green">在网页内的唯一标识符,万不得已不要用，用class</font>
- style  <font face="黑体" color="green">用来指定当前元素的 CSS 样式,style效力对比：js>html>css</font>
- tabindex   <font face="黑体" color="green">制定tab键跳动焦点及是否可以遍历，正数表示顺序访问，0表示最后访问，-1表示不访问</font>
- title   <font face="黑体" color="green">用来为元素添加附加说明</font>

### 默认样式

- **什么事默认样式？**
   <font face="黑体" color="800080" size="3">在css未出世前，html本身就有的一些样式，如标题自动加粗等</font> 
- **如何查看默认样式？**
   <font face="黑体" color="800080" size="3">首先打开Chrome</font>
   <font face="黑体" color="800080" size="3">Elements->Styles->user agent stylesheet</font>
- **User Agent是什么？**
   <font face="黑体" color="800080" size="3">即浏览器的意思</font>
- **为何使用CSS reset？**
   <font face="黑体" color="800080" size="3">由于html本身的默认样式已经不符合我们的需求，所以使用css reset将其覆盖掉，使用我们喜欢的样式</font>

### 常见的CSS reset

- 个人使用的[CSS reset](https://github.com/BenjaminWu-59/HTML-/blob/main/reset.css)
- 还可以在大厂等网页进行抄写

