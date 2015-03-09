---
layout: post
title: Git 常用命令
---

####初始化

```bash
git init
```

####与github对接

```bash
git remote add origin https://github.com/jinphen/Competition.git
```

####从github上下载代码

```bash
git pull origin master
```
其中git pull `-u` 表示把origin当作默认主机，这样就可以简写成这样git pull

####添加上传文件

```bash
git add Competiton.js
```

####添加所有改变的文件

```bash
git add -A
```


####查看状态

```bash
git status
```

####提交代码

```bash
git commit -m "log infomation"
```

####上传代码到github

```bash
git push origin master
```