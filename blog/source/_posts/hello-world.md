---
title: Hello World
---
在教师节这天，教学研发前端博客正式上线啦！在正式开始写作之前，先来和我一起 Get 写作必须的技能吧。废话不多说，必需品只有一台电脑💻。我相信你已经装好 `node` 和 `git`(如果还没装，那这篇真是玩不转啊)

## 快速开始

### 安装hexo

``` bash
$ npm install hexo-cli -g
```

### 拉取代码

``` bash
$ git clone https://github.com/TALFE/blog.git
$ cd blog
$ npm i
```

### 启动预览

``` bash
$ hexo server
```
网站会在 http://localhost:4000/blog 下启动。在服务器启动期间，Hexo 会监视文件变动并自动更新，无须重启服务器。

更多信息: [预览服务](https://hexo.io/zh-cn/docs/server.html)


### 创建文章

``` bash
$ hexo new "我的新文章"
```

更多信息: [写作](https://hexo.io/zh-cn/docs/writing.html)


### 用 Markdown 写作

关于 Markdown 的语法请自己搜索并尝试


### 生成发布目录

``` bssh
$ hexo generate
```
更多信息: [生成器](https://hexo.io/zh-cn/docs/generating.html)


### 发布到服务器

``` bash
$ hexo deploy
```

更多信息: [发布](https://hexo.io/zh-cn/docs/deployment.html)

打开 https://talfe.github.io/blog/ 查看新文章是否推送到线上服务器

### 代码同步
``` bash
$ git push
```
