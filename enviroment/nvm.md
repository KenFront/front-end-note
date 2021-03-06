# Nvm

Node.js 版本管理工具

- [官方網站](https://github.com/creationix/nvm)

## 安裝 Nvm

### 使用Git安裝

```
cd ~/
git clone https://github.com/nvm-sh/nvm.git .nvm
cd ~/.nvm
git checkout v0.xx.x
```

### 新增終端機設定檔

```
touch ~/.zprofile
```

### 修改終端機設定檔

```
export NVM_DIR="$HOME/.nvm"
source /usr/local/opt/nvm/nvm.sh
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion
#使用nvm
```

## 使用Nvm

### 安裝Node.js(v14.x.x)

```
nvm install lts/Fermium
```

### 修改nvm預設node版本(v14.x.x)

```
nvm alias default lts/Fermium
#使用node v14.x.x
```

### 確認Node安裝成功

```
node -v
```

## nvm常用指令

### 安裝某版本的Node.js

```
nvm install x.x.x
```

### 顯示目前安裝版本資訊

```
nvm ls
```

### 解除安裝某版本的Node.js

```
nvm uninstall x.x.x
```

### 切換使用的Node.js版本

```
nvm use x.x.x
```

### 設定預設Node.js版本

```
nvm alias default lts/xxx
```
