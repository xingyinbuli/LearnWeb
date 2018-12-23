

[分支的游戏网站](https://learngitbranching.js.org) 

## 新建分支

新建分支

```
git branch <new-branch-name>
git checkout <new-branch-name>
```

> 创建一个分支的同时，切换到新创建的分支

```
git checkout -b <new-branch-name>
```

## 合并分支

`合并`分支到master，前提是在master

```
git merge <branh-name>
```

`复制`分支到master

```
git rebase master
```

# Head

head>master>C1 `head指向C1` 

```
git checkout C1
```

移动 `head` 分支

```
git checkout HEAD^
git checkout HEAD~3
```

移动 `分支` 

```
git branch -f master HEAD~3
```

## 撤销变更

本地变更放弃

```
git reset HEAD~1
```

远程变更放弃

```
git revert HEAD
```

