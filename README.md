# wdw-component-grub4dos

This repository holds the grub4dos files that
[WinDiskWriterX](https://github.com/Stiven-Gjekaj/WinDiskWriterX) downloads for
Legacy BIOS boot.
Stiven Gjekaj keeps it.

The [latest release](https://github.com/Stiven-Gjekaj/wdw-component-grub4dos/releases/latest)
holds three files:

| File | What it does |
| ---- | ------------ |
| `grldr` | The grub4dos boot loader |
| `grldr.mbr` | The boot code that WinDiskWriterX writes to the start of the drive |
| `menu.lst` | The boot menu. It finds `bootmgr` and starts the Windows installer |

The code is grub4dos 0.4.6a by chenall and the grub4dos developers.
The tag `1.0-wdw-component-0.4.6a` marks the commit of the release.
The release files are the same as in the grub4dos component of WinDiskWriter by
TechUnRestricted.
grub4dos is under the GNU General Public License, version 2.
See [COPYING](COPYING).

The text below is the original README of grub4dos.

---

# grub4dos

![GitHub](https://img.shields.io/github/license/chenall/grub4dos?style=flat-square) ![GitHub Release Date](https://img.shields.io/github/release-date/chenall/grub4dos?style=flat-square) ![GitHub all releases](https://img.shields.io/github/downloads/chenall/grub4dos/total?style=flat-square)

多功能启动引导管理器

## 下载

http://grub4dos.chenall.net/

https://github.com/chenall/grub4dos/releases

## 分支

- [0.4.6a (Legacy BIOS)](https://github.com/chenall/grub4dos/tree/0.4.6a) [更新日志](https://github.com/chenall/grub4dos/blob/0.4.6a/ChangeLog_chenall.txt)
- [0.4.5c (Legacy_BIOS)](https://github.com/chenall/grub4dos/tree/master) [更新日志](https://github.com/chenall/grub4dos/blob/master/ChangeLog_GRUB4DOS.txt)
- [efi (i386-efi/x86_64-efi)](https://github.com/chenall/grub4dos/tree/efi) [更新日志](https://github.com/chenall/grub4dos/blob/efi/ChangeLog_UEFI.txt)

## 外部命令及工具

- [grubutils](https://github.com/chenall/grubutils) grub4dos/grub4efi 外部命令
- [mkimage](https://github.com/grub4dos/mkimage) grub4efi 启动文件生成工具
- [ntloader](https://github.com/grub4dos/ntloader) 启动 Windows WIM/VHD
- [grub4dos-build](https://github.com/chenall/grub4dos-build) grub4dos 编译脚本

## 论坛 / BUG 反馈

- [无忧启动](http://bbs.c3.wuyou.net/forum.php?mod=forumdisplay&fid=60) (Simplified Chinese)
- [GitHub Issues](https://github.com/chenall/grub4dos/issues)

