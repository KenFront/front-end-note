# Git

版本控制軟體

- [官方網站](https://git-scm.com/)

## 安裝 Git

```
brew install git
```

## Git 常用指令

### 將所有檔案加入提交

```
git add .
```

### 提交此次變更

```
git commit -m "Hello World"
```

### 查看設定

```
git config --list
```

### 查看目前變更

```
git status
```

### 查看目前分支變更紀錄

```
git log
```

### 暫存目前變更

```
git stash
```

### 回復上次暫存變更

```
git stash pop
```

### 清除所有暫存變更

```
git stash clear
```

### 捨棄目前變更

```
git checkout -f
```

### 將目前分支同步遠端狀態

```
git fetch --all
git reset --hard origin/xxx
```

### 切換分支

```
git checkout xxx
```

### 新增分支

```
git branch xxx
```

### 新增本地端分支

```
git branch xxx
```

### 移除本地端分支

```
git branch -d xxx
```

### 移除遠端分支

```
git push orgin :xxx
```

### 合併其他分支至目前分支

```
git merge xxx
```


### 合併其他分支至目前分支，不增加commit

```
git merge xxx --no-commit --no-ff
```

### 刪除所有已合併的本地端分支

```
git branch --merged | egrep -v "(^\*|main|dev|master)" | xargs git branch -d
```


### 刪除專案的submoule

```
// if only one git submodule
git rm .gitmodules -f

git rm -fr --cached (relative path) 
vi .git/config //remove relatetive repo
git commit
```

### 調整檔案名稱大小寫

```
git mv hello.txt Hello.txt
```

### 刪除已上傳的檔案

```
// example .DS_Store
find . -name .DS_Store -print0 | xargs -0 git rm -f --ignore-unmatch
```

### 看git commit 紀錄

```
git log --oneline --graph
```
### 同步fork專案

```
git remote add upstream git://xxx.git

git fetch upstream

git pull upstream master
```
