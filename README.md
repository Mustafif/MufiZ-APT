# MufiZ APT Repository

This is the official MufiZ APT repository that will allow any 
Debian-based system to install the MufiZ compiler using the 
APT package manager.

## Installation

```bash
echo "deb [arch= {arch}, trusted=yes] https://mustafif.github.io/Mufi-APT mufiz main" | sudo tee /etc/apt/sources.list.d/mufiz.list
sudo apt update && sudo apt upgrade
sudo apt install mufiz
```

## Supported Architectures

- amd64
- arm64
- mipsel
- mips64el
- mips64
- mips
- powerpc
- powerpc64
- powerpc64le
- riscv64