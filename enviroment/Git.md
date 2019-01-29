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

### 捨棄目前變更

```
git checkout -f
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
git push orgin:xxx
```

### 合併其他分支至目前分支

```
git merge xxx
```

### 刪除所有本地端分支

```
git branch --merged | grep -v \* | xargs git branch -D 
```


### 刪除專案的submoule

```
git rm .gitmodules -f
git rm -fr (relative path)
vi .git/config //remove relatetive repo
git commit
```
