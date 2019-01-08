# Homebrew

Mac OS 套件管理工具

- [官方網站](https://brew.sh/index_zh-tw)

## 安裝 Homebrew

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

```

## 安裝 Homebrew Cask

```
brew tap caskroom/cask
```

## Homebrew 常用指令

### 查詢指令

```
brew help
```

### 安裝套件

```
brew install xxx
```

### 安裝應用程式

```
brew cask install xxx
```

### 更新套件清單

```
brew update
```

### 升級已安裝套件

```
brew upgrade
```

### 升級已安裝應用程式

```
brew cask upgrade
```

### 解除安裝套件

```
brew uninstall xxx
```

### 解除安裝應用程式

```
brew cask uninstall xxx
```

### 檢查Homebrew狀態

```
brew doctor
```