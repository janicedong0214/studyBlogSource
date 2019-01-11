---
title: hexo+githubPage搭建个人博客
date: 2019-01-11 15:50:39
tags: [git,hexo]
---
#### 1.本地环境配置：
> 安装node.js
  安装git
  通过npm安装hexo：npm i -g hexo-cli
#### 2.github上的配置
> 1.新建git仓库

> 2.点击settings设置

> ![](1.jpg)

> 3.选择主分支(根据自己需求选择分支)，然后点击save保存

> ![](2.jpg)
#### 3.本地创建hexo项目
> ** 1.初始化hexo项目 **
```
hexo init 项目名
```

> ** 2.修改配置文件_config.yml **

> 1. 设置url和根目录root

![](3.png)

> 2. 设置喜欢的主题
注：到官网选择主题模板，克隆到theme文件夹下，
例：git clone https://github.com/cofess/hexo-theme-pure.git themes/pure

![](4.jpg)

> 3. 配置部署项

![](5.jpg)

> 4. 安装git插件：npm i hexo-deployer-git --save

#### 4.常用命令
>   hexo g
>   hexo s(本地运行)
>   hexo d：部署到远程github上，通过之前设置的url+root就能访问了

