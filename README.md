# helloworld_in_riscv_and_rust_baremetal
hello world in RISC-V / bare-metal Rust.

## run
Required qemu-system-riscv64 and target "riscv64imac-unknown-none-elf".
```
$ rustup target add riscv64imac-unknown-none-elf
$ cargo r
```

# Reference
[tomoyuki-nakabayashi/riscv-rust-hello](https://github.com/tomoyuki-nakabayashi/riscv-rust-hello)  
[light4/riscv-baremetal-rust-helloworld: Rust riscv-64gc baremetal example](https://github.com/light4/riscv-baremetal-rust-helloworld)  
[qemu/hw/riscv/sifive_u.c](https://github.com/qemu/qemu/blob/master/hw/riscv/sifive_u.c)  
