# Rust Webassembly example

This is a cargo project for the following tutorial:
https://www.hellorust.com/demos/add/

## Preparation

Install nightly toolchain and wasm target:
```
rustup install nightly
rustup target add wasm32-unknown-unknown --toolchain nightly
```

Set default toolchain for current directory:
```
rustup override set nightly
```

## Build

```
cargo build
```

The output can be found in `target/wasm32-unknown-unknown/debug/add.wasm`.

## TODO 

- `wasm-gc` steps
