# KordaOS
_A minimal x86 operating system for educational purposes_

**✨ Features**
- Lightweight - Written entirely in FASM assembly

- Modular - Separated bootloader, kernel, and applications

- Educational - Clean, commented code for learning OS dev

- Portable - Builds on Windows/Linux/macOS


## 🚀 Quick Start
Install dependencies:

### 🐧 Linux

Install FASM using your distro's package manager:

```bash
# Debian / Ubuntu / Linux Mint
sudo apt install fasm
```
```bash
# Arch Linux / Manjaro
sudo pacman -S fasm
```
```bash
# Fedora / RHEL / CentOS
sudo dnf install fasm
```
```bash
# openSUSE
sudo zypper install fasm
```
```bash
# Arch-based (AUR)
yay -S fasm
```
## Build the OS:

**make && make run**
**Test in QEMU:**

```bash
qemu-system-i386 -drive format=raw,file=kordaos.bin
```

## windows

in windows, you can install wsl:

```terminal
wsl --install
```

or you can download FASM in EXE:


📎 [FASM Download Page](https://flatassembler.net/download.php)

## 🍎 macOS
First, install Homebrew if you haven't:
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
Then install FASM:

```bash
brew install fasm
```
ℹ️ If fasm isn't available via brew, you can download it manually:
📎 FASM for macOS (manual)
[Download FASM for macOS (Unix/Linux version)](https://flatassembler.net/fasm-1.73.30.tgz)


## 🐚 BSD (e.g. FreeBSD)
Install FASM using pkg:

``
pkg install fasm
``
Or build it manually from source *(advanced)*:
[download fasm source code](https://flatassembler.net/fasm-1.73.30.tgz)

- Build the source code
```bash
fetch https://flatassembler.net/fasm-1.73.30.tgz
tar -xvzf fasm-1.73.30.tgz
cd fasm
make
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
