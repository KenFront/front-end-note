# Rust

程式語言
- [官方網站](https://www.rust-lang.org/)

## 安裝 Rust(rustup)

```
curl https://sh.rustup.rs -sSf | sh -s -- -y
```

## rustup 常用指令

### 更新版本

```
rustup update
```

### 切換為最新穩定版

```
rustup default stable
```

## Cargo (Rust management tool)

### 新建專案

```
cargo new xxx
```

### 編譯(develop mode)

```
cargo build
```

### 編譯(production mode)

```
cargo build --release
```

### 清理暫存檔

```
cargo clean
```

### 執行

```
cargo run
```

### 檢查專案

```
cargo check
```

### 修正專案程式碼排版

```
cargo fmt
```

### 更新Cargo.lock

```
cargo update
```

### 安裝專案相依性套件管理指令工具

```
cargo install cargo-edit
// then
cargo add xxx // add lib to Cargo.toml
cargo rm xxx // remove lib from Cargo.toml
cargo upgrade xxx // update lib in Cargo.toml
```
