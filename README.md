# KordaOS
_A minimal x86 operating system for educational purposes_

**✨ Features**
- Lightweight - Written entirely in FASM assembly

- Modular - Separated bootloader, kernel, and applications

- Educational - Clean, commented code for learning OS dev

- Portable - Builds on Windows/Linux/macOS


## 🚀 Quick Start
Install dependencies:

# FASM (Linux example)
sudo apt install fasm
Build the OS:

**make && make run**
**Test in QEMU:**

```bash
qemu-system-i386 -drive format=raw,file=kordaos.bin
```
## 📚 Components
>Component	Description	File
>Bootloader	Loads kernel from disk	boot.asm
>Kernel	Core system services	kernel.asm
>FAT12	Filesystem driver	fat12.asm
>Calculator	Simple arithmetic app	calculator.asm
>📜 License
- I2 License (my own license) - See LICENSE for details.

*"Simplicity is the ultimate sophistication."*
— Leonardo da Vinci

Crafted with ♥ by Bandikaaking

**(github profile: https://github.com/bandikaaking)**
