# Nvm

Node.js 版本管理工具

- [官方網站](https://github.com/creationix/nvm)

## 安裝 Nvm

### 使用Homebrew安裝

```
brew install nvm
```

### 新增終端機設定檔

```
touch ~/.bash_profile
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

### 安裝Node.js(v10.x.x)

```
nvm install lts/dubnium
```

### 修改終端機設定(~/.bash_profile)

```
export NVM_DIR="$HOME/.nvm"
source /usr/local/opt/nvm/nvm.sh
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion
#使用nvm

nvm use lts/dubnium
#使用node v10.x.x
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
