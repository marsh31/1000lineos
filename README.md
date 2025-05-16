# README

[1000行で作るOS](https://operating-system-in-1000-lines.vercel.app/ja/)をやってみる。  

## Requirement

```bash
sudo pacman -S clang llvm lld qemu-system-riscv curl
curl -LO https://github.com/qemu/qemu/raw/v8.0.4/pc-bios/opensbi-riscv32-generic-fw_dynamic.bin
```


## Startup

```bash
./run.sh
```


## Tools

- [Compile explorer](https://godbolt.org/)  
  `RISC-V rv32gc clang (trunk)`  


## Term

SBI Supervisor Binary Interface  
[RISC-V SBI Documentation](https://github.com/riscv-non-isa/riscv-sbi-doc)  
[OpenSBI](https://github.com/riscv-software-src/opensbi)  


## qemu

```txt
C-a h    print this help
C-a x    exit emulator
C-a s    save disk data back to file (if -snapshot)
C-a t    toggle console timestamps
C-a b    send break (magic sysrq)
C-a c    switch between console and monitor
C-a C-a  sends C-a
```


## github

[Github author page](https://github.com/nuta/operating-system-in-1000-lines/tree/main)  

