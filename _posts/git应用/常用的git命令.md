## 常用的git命令。

#### 在当前目录新建一个Git代码库：
```shell
git init
```

#### 下载一个项目和它的整个代码历史：
```shell
git clone [url]
```

#### 添加当前目录的所有文件到暂存区：
```shell
git add .
```

#### 提交暂存区到仓库区：
```shell
git commit -m "commit message"
```

#### 显示有变更的文件：
```shell
git status
```

#### 显示暂存区和工作区的差异：
```shell
git diff
```
#### 显示当前分支的版本历史：
```shell
git log
```

#### 显示当前分支的最近几次提交：
```shell
git reflog
```

#### 重置当前分支的HEAD为指定commit，同时重置暂存区和工作区，与指定commit一致：
```shell
git reset --hard [commit]
```

#### 列出所有本地分支：
```shell
git branch
```

#### 新建一个分支，但依然停留在当前分支：
```shell
git branch [branch]
```

#### 切换到指定分支，并更新工作区：
```shell
git checkout [branch]
```

#### 下载远程仓库的所有变动：
```shell
git fetch [remote]
```

#### 取回远程仓库的变化，并与本地分支合并：
```shell
git pull [remote] [branch]
```

#### 上传本地指定分支到远程仓库：
```shell
git push [remote] [branch]
```

#### 合并指定分支到当前分支：
```shell
git merge [branch]
```

#### 选择一个commit，合并进当前分支：
```shell
git cherry-pick [commit]
```

#### 暂时将未提交的变化移除，稍后再移入：
```shell
git stash
git stash pop
```
