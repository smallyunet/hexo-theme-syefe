
### 简介

这是一款模仿[百度EFE](http://efe.baidu.com)的hexo主题。

演示地址: https://smallyunet.github.io/hexo-theme-syefe 

### 开始使用

```
git clone https://github.com/smallyunet/hexo-theme-syefe.git
```

默认的theme分支为包含主题文件的分支。master分支下是整个演示站点的资源文件。

### 头像

配置文件中avator属性为true或者false决定侧栏是否显示头像。

自定义头像请替换source/img/avatar.png文件。

### Front-matter:

  - author: 文章作者

### RSS功能

参见: https://github.com/hexojs/hexo-generator-feed

### 一些说明

- syefe基本还原了EFE的版式，但没有实现其之外的功能，如归档和标签云。~~后续完善~~。

- 页面展示的文章列表，如果有摘要部分则显示摘要，否则只显示文章标题。如若需要在列表页显示文章全部内容，请在文章最底部添加`<!-- more -->`。

- 目前副标题和文章作者信息的链接无法点击，因为EFE的功用和个人博客稍有出入，所以在功能的取舍上也遇到了一些问题。如果你有更好的想法，请随意修改。
