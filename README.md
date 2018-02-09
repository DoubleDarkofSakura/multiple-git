# multiple-git

**Author: Double Dark of Sakura**

测试同时提交到多个远程仓库

## Step 1 创建空仓库

github: https://github.com/DoubleDarkofSakura/multiple-git.git
coding: https://git.coding.net/ddosakura/multiple-git.git
gitee:  https://gitee.com/moyinzi/multiple-git.git

## Step 2 Clone from github

## Step 3 Create README.md

## Step 4 Add remote

1. 查看远程地址 `git remote -v`

```
origin  https://github.com/DoubleDarkofSakura/multiple-git.git (fetch)
origin  https://github.com/DoubleDarkofSakura/multiple-git.git (push)
```

2. 添加远程仓库

```bash
git remote add coding https://git.coding.net/ddosakura/multiple-git.git
git remote add gitee https://gitee.com/moyinzi/multiple-git.git
```

3. 查看远程地址 `git remote -v`

```
coding  https://git.coding.net/ddosakura/multiple-git.git (fetch)
coding  https://git.coding.net/ddosakura/multiple-git.git (push)
gitee   https://gitee.com/moyinzi/multiple-git.git (fetch)
gitee   https://gitee.com/moyinzi/multiple-git.git (push)
origin  https://github.com/DoubleDarkofSakura/multiple-git.git (fetch)
origin  https://github.com/DoubleDarkofSakura/multiple-git.git (push)
```

## Step 5 Commit

## Step 6 Push

```
git push -u origin master
git push -u coding master
git push -u gitee master
```