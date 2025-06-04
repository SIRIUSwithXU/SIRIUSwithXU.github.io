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


## git使用笔记

1、克隆仓库：

```
git clone https://github.com/你的用户名/项目名.git
```

2、创建分支：

```
git checkout -b master // 基于主分支创建新分支
```

3、提交并推送分支：

```
git add . // 将改动添加到暂存区，.代表全部文件
git commit -m "添加新功能"
git push origin main// 将本地更改推送到远程master分支。
```

其它操作：


```
git status   ## 查看修改的状态
git diff .   ## 查看修改的具体不同

git remote -v
git remote：查看当前 Git 仓库关联的远程仓库名称。
-v（verbose）：显示详细信息，包括每个远程仓库的 URL 和用途（fetch 或 push）。
```


## 文件状态说明

_site:这个应该是网站在本地编译后的文件目录，上传到GitHub后的文件目录应该是这个样子。

### 图片的地址说明：

其中图片最好放在assets的image下面，会被传上去。

所以文件中图片的地址写成：../assets/image/

![1690876333028](../assets/image/1690876333028.png)
