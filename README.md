# DiscordBOT-Arknights-Rust

## Rust 基本操作
為了避免忘記操作指令，只好把指令先寫下來

### Rust 基本設定
#### 查看版本
```
rustc --version
```

#### Rust 版本更新
```
rustup update
```

### 開發
#### 初始化專案
```
cargo init
```

```
cargo new <projectname>
```

#### 編譯 + 執行
```
cargo run
```

#### 編譯
```
cargo build
```

#### 發布
```
cargo run --release
```
或
```
cargo build --release
```
> 得到的結果會放在 `target/release` 資料夾中

#### 安裝套件
編輯 `Cargo.toml`，下次操作就會自動安裝了
