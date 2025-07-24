# Ref OS

**Ref OS** is a custom GUI-based operating system with native `.refx` app support, multitasking, a taskbar, and mouse interactions — all built from scratch.

## ✨ Features
- Bootable OS (GRUB-compatible)
- Custom GUI with draggable windows
- Clickable `.refx` apps
- Text input, multithreading, and app switching
- Optional Internet Stack (PCI, E1000, IPv4, UDP)

Bro compile it yourself, why do you think i put a zip there?. you might need WSL (For windows users). To download wsl go to https://learn.microsoft.com/en-us/windows/wsl/install

## 🛠️ Build & Run
```bash
./scripts/build.sh
./scripts/run-qemu.sh
