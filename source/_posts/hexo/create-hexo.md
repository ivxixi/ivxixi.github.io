---
title: 搭建自己的博客
categories:
- Hexo
tags:
- Hexo
- 博客
---


- 创建 `hexo` 项目

```bash
# 创建 hexo 项目
npm install hexo-cli -g
hexo init blog
cd blog
npm install
hexo server
```

- 添加主题

```bash
npm install hexo-theme-icarus
hexo config theme icarus
```

- 启动程序

```bash
hexo serve
```

> **注：** 如果出现如图错误
>
> [![bhbJQU.md.png](https://s1.ax1x.com/2022/03/10/bhbJQU.md.png)](https://imgtu.com/i/bhbJQU)
>
> - 执行以下命令
>
>   `npm install --save bulma-stylus@0.8.0 hexo-pagination@^2.0.0 hexo-renderer-inferno@^0.1.3`
>
> - 重启 
>
>   `hexo serve`

- 添加必须
```bash
# 添加关于
hexo new page about
# 添加分类
hexo new page categories
# 添加标签
hexo new page tags
```
