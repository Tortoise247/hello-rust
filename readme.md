# RUSTを使ってみる

## 参考書籍

- [Command Line Rust](https://www.oreilly.com/library/view/command-line-rust/9781098109424/

## RUSTのインストール

```bash
# RUSTのインストール
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

source $HOME/.cargo/env

# RUSTのバージョン確認
rustc --version
```


## RUSTのコンパイル

```bash
# RUSTのコンパイル
rustc hello.rs
# RUSTの実行
./hello
```

## RUSTのプロジェクト作成

```bash
# RUSTのプロジェクト作成
cargo new hello
cd hello
# RUSTのビルド
cargo build
# RUSTの実行
cargo run
```
