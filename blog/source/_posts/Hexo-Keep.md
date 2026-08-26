---
title: Hexo-Keep
date: 2020-03-22 21:22:16
tags:
---
Welcome to my blog by [Hexo](https://hexo.io)! If you want to have your own blog space, this article will teach it.

## Quick Start


### 1.安装Hexo
``` bash
$ npm install hexo-cli -g
```

### 2.初始化博客
``` bash
$ hexo init blog
```

### 3.安装keep主题
``` bash
$ cd blog
$ npm install hexo-theme-keep
$ npm update hexo-theme-keep // 更新主题
```

### 4.配置主题
``` bash
$ touch blog/source/_data/keep.yml
```
https://keep-docs.xpoet.cn/basis/get-start/starter-template.html

### 5.插件

#### 5.1搜索插件
* More info: [Search](https://github.com/theme-next/hexo-generator-searchdb)
``` bash
$ npm install hexo-generator-searchdb
// 在 Hexo 配置文件 _config.yml 里添加如下配置
search:
  path: search.json
  field: post
  content: true
  format: striptags
```

#### 5.2评论插件Giscus   
* More info: [Giscus](https://giscus.app)

#### 5.3RSS订阅
``` bash
$ cd blog
$ npm install hexo-generator-feed

// 在 Hexo 配置文件 _config.yml 里添加如下配置
feed:
  type: atom
  path: rss/atom.xml
  limit: 20
```

### 6.创建文章
``` bash
$ hexo new "Hexo-Keep"
```
  
### 7.启动服务预览
``` bash
$ hexo server
```

### 8.生成静态文件
``` bash
$ hexo clean
$ hexo generate
```

### 9.提交GitHub Pages
``` bash
$ git commit
```



### [参考链接]:
https://hexo.io

https://keep-docs.xpoet.cn
