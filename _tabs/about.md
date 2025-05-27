---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---
> Add Markdown syntax content to file `_tabs/about.md`{: .filepath } and it will show up on this page.
> {: .prompt-tip }

# 关于github的同步以及该笔记的一些使用说明

详细说明在：[https://chirpy.cotes.page/](https://chirpy.cotes.page/)

## 本地服务器启动

bundle exec jekyll s

## 与git上的仓库同步笔记

1、在github上创建项目

2、使用git clone https://github.com/xxxxxxx/xxxxx.git 克隆到本地

3、编辑项目【增、删、改】
git status   ## 查看修改的状态
git diff .   ## 查看修改的具体不同

4、git add . （将改动添加到暂存区，.代表全部文件）

5、git commit -m "提交说明"

6、git push origin master  将本地更改推送到远程master分支。

## 文件状态说明

_site:这个应该是网站在本地编译后的文件目录，上传到GitHub后的文件目录应该是这个样子。

### 图片的地址说明：

其中图片最好放在assets的image下面，会被传上去。

所以文件中图片的地址写成：../assets/image/

![1690876333028](../assets/image/1690876333028.png)
