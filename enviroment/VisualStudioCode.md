# Visual Studio Code

開發程式，使用的編輯器

- [官方網站](https://code.visualstudio.com/)

## 安裝(Homebrew cask)

```
brew cask install visual-studio-code
```

## 產生安裝目前套件指令

```
code --list-extensions | xargs -L 1 echo code --install-extension
```