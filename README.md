# Hello Solana - Rust Smart Contract

This is a basic Solana smart contract written in Rust that prints a message to the program logs.

## 📦 Usage

```bash
cargo build-sbf -- -Znext-lockfile-bump
solana program deploy target/deploy/hello_solana.so
