# flipper-substrate
I expect you already have prepared enviroment with Rust & Cargo.
If not, go through this https://substrate.dev/docs/en/contracts/installing-ink

```
$ cat rust-toolchain
nightly-2019-05-21⏎
$ rustup install nightly-2019-05-21
$ rustup target add wasm32-unknown-unknown --toolchain nightly-2019-05-21
$ cargo install --force --git https://github.com/paritytech/ink cargo-contract
```

Continue https://substrate.dev/docs/en/contracts/deploying-a-contract