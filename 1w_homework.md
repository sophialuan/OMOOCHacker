只想学习搭建一款自己的blog，然后毅然决然开启了学习Github之旅。

Github for Windows装上后一直同步不到仓库，开始了命令行求索。嘤。

## 何为[Git](http://git-scm.com/book/zh/v2) 

11.9 理解：版本控制工具，链接本地与云端。
## 配置Git 基本环境
>1.配置用户名 git config--global user.name "Your  Name" 

>2.配置邮箱git config --global user.email "you@email.address"

>3.配置[SSH key](http://segmentfault.com/a/1190000002645623) 


##Git 命令集

- 创建文件夹 mkdir 

- 进入文件夹 cd

- 初始化文件夹作为git目录 git init

- 添加文件 git add 

- 提交更改 git commit -m"descripsion"

- 添加文件并提交更改 git commit -am "description"（win用提示语法错误呢）

- 添加远程仓库 git remote add origin git@id/folder name

- 初次远程推送 git push -u origin master

- 推送更新 git push

看似这个简单的过程，其中想不到的问题数不胜数，幸亏有百度。自己遇到的大部分分问题均可在这篇[《github本地如何上传代码》](http://blog.sina.com.cn/s/blog_4cae9efc0102vgj6.html)中找到。

以及[廖雪峰的Git教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)对理解Git的原理起了很大帮助。

此外：
- git push 报错时 采用了 fetch -merge 的方法。原理及三个区别详见： [《git fetch, merge, pull, push需要注意的地方》](http://blog.csdn.net/hutaoer06051/article/details/8673947)

编程90%是个自己学习的过程哪，上课的视频过了两遍后依然不知道老师在讲啥OMG。Git官网真是贴心，这本 [Git Book](http://git-scm.com/book/zh/v2)给准备了mobi 和pdf下载，读完后修炼成：

![GitHub女王](http://blogs-images.forbes.com/kashmirhill/files/2014/04/github-girl-cat2-e1398192921347.jpg)