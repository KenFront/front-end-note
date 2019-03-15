# Css 相關筆記

### 單行隱藏過多文字

```
{
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}
```

### 多行隱藏過多文字(Webkit 瀏覽器適用)

```
{
  overflow : hidden;
  text-overflow: ellipsis;
  display: -webkit-box;
  -webkit-line-clamp: 5;
  -webkit-box-orient: vertical;
}
```

### 解決Safari，動畫問題

```
{
  -webkit-transform: translate3d(0,0,0)
}
```

### 解決Safari，滑動問題

```
{
  -webkit-overflow-scrolling: auto;
}
```

### 解決Safari，彈出輸入框，編輯文字符號跑版

```
body {
  position:fixed;
}
```

### 移除按鈕長按特效

```
{
  -webkit-tap-highlight-color: transparent;
}
```

### 不可選取

```
{
  user-select: none;
}
```

### 移除outline

```
{
  outline: none;
}
```
