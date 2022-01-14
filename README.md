# 1. rust-toys

This is a toy code repo that contains some naive code when learning Rust with book [The Rust Programming Language](https://doc.rust-lang.org/book/title-page.html).

# 2. Tips

## 2.1. Visual Studio Code + Rust

- rust-analyzer - https://rust-analyzer.github.io/
2.2. - Better TOML
---
- Error Lens
- CodeLLDB

## 2.3. Rust crates.io 索引镜像

编辑 ~/.cargo/config 文件，添加以下内容：

```toml
[source.crates-io]
registry = "https://github.com/rust-lang/crates.io-index"

replace-with = 'ustc'

[source.ustc]
registry = "https://mirrors.ustc.edu.cn/crates.io-index"

[net]
git-fetch-with-cli = true
```

镜像可加快 cargo 读取软件包索引的速度。国内镜像有清华、中科大和上交。
