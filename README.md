# Open Computers II (RISC-V Musl Linux) Hello World Rust example, made very small

Final compiled binary size: ~8KiB

- `strip = true`
- `panic = 'abort'`
- `codegen-units = 1`
- `opt-level = 'z'`
- `lto = true`
- `build-std`
- `panic_immediate_abort`
- `#![no_main]`

## Resources

https://github.com/johnthagen/min-sized-rust

https://darkcoding.net/software/a-very-small-rust-binary-indeed/
