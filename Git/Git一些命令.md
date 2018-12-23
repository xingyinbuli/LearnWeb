## 创建新仓库

[<u>Git 教程</u>](https://github.com/geeeeeeeeek/git-recipes/wiki)

```
git init
```

用 `git status` 查看git仓库状态 

用 `git log` 查看提交状态 `git log --oneline` 看一行提交

## 添加与提交

```
git add <filename>
git add *
git commit -m "代码信息"
```

## 推送改动

添加远程 推送改动

```
git remote add origin <server> 
git push origin master
```

用 `git remote rm origin` 删除远程

## git clone

将远程的拷贝到指定 `目录` 中

```
git clone <repo><directory>
```

本地仓库修改自己的config，并进行 `编辑` 

```
git config --global --edit
```

## 检出文件

检出提交

```
git checkout a1e8fb5
git checkout <commit>
```

检出文件

```
git checkout a1e8fb5 hello.py
git checkout <commit> <file>
```

如果不想保留checkout的文件

```
git checkout HEAD hello.py
```

## 回滚错误的修改

`git revert` 命令用来撤销一个已经提交的快照。但是，它是通过搞清楚如何撤销这个提交引入的更改，然后在最后加上一个撤销了更改的新提交。

```
git revert <commit>
```

