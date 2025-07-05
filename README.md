# Debian-XFCE-Mac-OS-Themes DEMO

> Run full Debian XFCE Desktop + GUI apps on Android using Termux + Proot-Distro + Termux-X11.

## 🖥️ Preview

![preview](pic.jpg)


## 📥 Download Debian Rootfs

[Click here to download Debian.tar.xz](https://example.com/debian.tar.xz)

## 🛠️ Installation

> First step
This serves to allow Termux to access Android internal storage.
```bash
termux-setup-storage
```
### 1. Then
> you need to install the following packages in Termux.

```bash
pkg update
pkg install x11-repo
pkg install termux-x11-nightly
pkg install pulseaudio
pkg install proot-distro
```
