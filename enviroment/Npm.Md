# NPM

Node.js 套件管理工具
- [官方網站](https://www.npmjs.com/)

## 安裝 NPM

裝完Node.js，附帶的工具

## NPM 常用指令

### 產生專案設定檔(package.json)

```
npm init -y
```

### 查看目前安裝套件

```
npm ls
```

### 安裝編譯時期套件

```
npm i xxx -D
```

### 新增編譯時期(compile time)套件

```
npm i xxx
```

### 新增執行時期(run time)套件

```
npm i xxx
```

### 安裝時指定版號

```
npm i xxx@1.2.3
```

### 安裝所有記錄在package.json的套件

```
npm i
```

### 安裝所有記錄在package.json/dependencies(執行時期)套件

```
npm i --only=prod
```

### 安裝所有記錄在package.json/devDependencies(編譯時期)套件

```
npm i --only=dev
```

### 檢查已安裝套件版本

```
npm outdated
```

### 更新所有套件

```
npm update
```

### 更新某個套件

```
npm update xxx
```

### 解決已安裝套件安全性問題
視情況加上--force
```
npm audit fix
```

### 安裝非npm上的套件
```
git+https://xxxxxx.git
git+ssh://xxxxxx.git
```
