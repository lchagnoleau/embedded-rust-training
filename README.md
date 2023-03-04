# embedded-rust-training

## Install environment

```bash
rustup component add llvm-tools-preview
cargo install cargo-binutils cargo-embed
rustup target add thumbv7em-none-eabihf
```

For debug:
```bash
cargo install probe-run
```

## Build and flash

```bash
cargo build
cargo embed
```
