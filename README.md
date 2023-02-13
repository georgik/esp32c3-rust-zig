# Example application for ESP32-C3

Rust `no_std` app invokes Zig function.

## Build

```
cd ziglib
zig build-lib -target riscv32-freestanding-none  -mcpu sifive_e76   src/main.zig
cd ..
cargo build --release
```

