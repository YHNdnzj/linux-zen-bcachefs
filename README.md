# linux-zen-bcachefs

Linux ZEN with Bcachefs support

### Extra changes

- [Replace all fbdev drivers with simplefb](https://fedoraproject.org/wiki/Changes/ReplaceFbdevDrivers)
- Disable deprecated EFI handover protocol (`CONFIG_EFI_HANDOVER_PROTOCOL`)

### Acknowledgement

- [bcachefs](https://github.com/koverstreet/bcachefs)
- [zen-kernel](https://github.com/zen-kernel/zen-kernel)
- [linux-bcachefs-git](https://aur.archlinux.org/packages/linux-bcachefs-git)

#### Special

- [systemd](https://github.com/archlinux/svntogit-packages/blob/packages/systemd/trunk/PKGBUILD): for how to combine two upstreams
