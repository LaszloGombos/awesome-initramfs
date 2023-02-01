[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome initramfs resources.

## Contents

- [Projects](#projects)
- [Documentation](#documentation)
- [Resources](#resources)

## Projects
* [dracut](https://github.com/dracutdevs/dracut) - Fedora, Debian, Arch, Alpine
* [make-initrd](https://github.com/osboot/make-initrd) - AltLinux, Fedora, Ubuntu
* [initramfs-tools](https://salsa.debian.org/kernel-team/initramfs-tools) - Debian
* [mkinitcpio](https://github.com/archlinux/mkinitcpio) - Arch
* [mkinitfs](https://gitlab.alpinelinux.org/alpine/mkinitfs/) - Alpine
* [u-root](https://github.com/u-root/u-root) - Golang
* [better-initramfs](https://github.com/slashbeast/better-initramfs) - Bash shell
* [booster](https://github.com/anatol/booster) - Golang
* [tiny-initramfs](https://github.com/chris-se/tiny-initramfs)
* [tinyramfs](https://github.com/illiliti/tinyramfs) - POSIX shell
* [clr-init](https://github.com/clearlinux/clr-init) - Clear Linux
* [core-initrd](https://github.com/snapcore/core-initrd) - Ubuntu Core Linux
* [jamdisk](https://github.com/cbdevnet/jamdisk)
* [micro-rootfs](https://github.com/loicpoulain/micro-rootfs) - buildroot
* [tinycorelinux](https://github.com/tinycorelinux/Core-scripts/blob/master/init) - initramfs distro (no switch_root)
* [mkroot/toybox](https://github.com/landley/toybox/blob/master/scripts/mkroot.sh) - minimal initramfs distro
* [cloud-initramfs-tools](https://launchpad.net/cloud-initramfs-tools/) - initramfs-tools extra modules
* [mxlinux](https://github.com/MX-Linux/build-iso-mx/tree/master/Template/COMMON/initrd) - MX Linux
* [linux-live](https://github.com/Tomas-M/linux-live)
* [tinyroot](https://github.com/troglobit/tinyroot) - Tinyroot
* [mkinitramfs](https://www.linuxfromscratch.org/blfs/view/svn/postlfs/initramfs.html) - Linux from scratch
* [JamiKettunen](https://github.com/JamiKettunen/initramfs-tools)
* [Postmarketos-mkinitfs](https://gitlab.com/postmarketOS/pmaports/-/tree/master/main/postmarketos-mkinitfs)
* [Yocto-initrdscripts](https://github.com/yoctoproject/poky/tree/master/meta/recipes-core/initrdscripts)

## Documentation
* [linux kernel](https://www.kernel.org/doc/html/latest/filesystems/ramfs-rootfs-initramfs.html)
* [wikipedia](https://en.wikipedia.org/wiki/Initial_ramdisk)
* [debian](https://wiki.debian.org/initramfs)
* [ubuntu](https://wiki.ubuntu.com/Initramfs)
* [arch](https://wiki.archlinux.org/title/Arch_boot_process#initramfs)
* [gentoo](https://wiki.gentoo.org/wiki/Initramfs/Guide)
* [fedora](https://fedoraproject.org/wiki/Dracut)
* [postmarketos](https://wiki.postmarketos.org/wiki/The_initramfs)

## Minimal rootfs
* [micro-rootfs](https://github.com/loicpoulain/micro-rootfs)  - mdev

# Dracut wikis/docs
 * [Arch](https://wiki.archlinux.org/title/Dracut)
 * [Fedora](https://fedoraproject.org/wiki/Dracut)
 * [FedoraDebug](http://fedoraproject.org/wiki/How_to_debug_Dracut_problems)
 * [Gentoo](https://wiki.gentoo.org/wiki/Dracut)
 * [Wikipedia](https://en.wikipedia.org/wiki/Dracut_(software))
 * [DracutNotes](https://wwoods.fedorapeople.org/doc/dracut-notes.html)
 * [Repology](https://repology.org/project/dracut)

# Projects with out-of-tree dracut modules
 * [brltty](https://github.com/brltty/brltty/tree/master/Initramfs/Dracut)
 * [fai](https://github.com/faiproject/fai/tree/master/lib/dracut/80fai-autodiscover)
 * [kiwi](https://github.com/OSInside/kiwi/tree/master/dracut/modules.d)
 * [dracut-sshd](https://github.com/gsauthof/dracut-sshd)
 * [dracut-crypt-ssh](https://github.com/dracut-crypt-ssh/dracut-crypt-ssh)
 * [openzfs](https://github.com/openzfs/zfs/tree/master/contrib/dracut)
 * [clevis](https://github.com/latchset/clevis/tree/master/src/luks/systemd/dracut)
 * [ignition](https://github.com/coreos/ignition/tree/main/dracut)
 * [stratisd](https://github.com/stratis-storage/stratisd/tree/master/dracut)
 * [tpm2-totp](https://github.com/tpm2-software/tpm2-totp/tree/master/dist/dracut)
 * [anaconda](https://github.com/rhinstaller/anaconda/tree/master/dracut)
 * [transactional-updates](https://github.com/openSUSE/transactional-update)
 * [afterburn](https://github.com/coreos/afterburn/tree/main/dracut/30afterburn)
 * [qubes-antievilmaid](https://github.com/QubesOS/qubes-antievilmaid/tree/master/90anti-evil-maid)
 * [dracut-encryptrootfs](https://github.com/Symantec/dracut-encryptrootfs)
 * [Fedora CoreOS](https://github.com/coreos/fedora-coreos-config/tree/testing-devel/overlay.d/05core/usr/lib/dracut/modules.d)
 * [dracut-iguana](https://github.com/aaannz/dracut-iguana)
 * [mkinitcpio-ykfde](https://github.com/eworm-de/mkinitcpio-ykfde/tree/master/dracut)
 * [dracut-ntfsloop](https://github.com/genosse-einhorn/dracut-ntfsloop)
 * [constellation](https://github.com/edgelesssys/constellation/tree/main/image/mkosi.skeleton/usr/lib/dracut/modules.d)
 * [iguana](https://github.com/openSUSE/iguana/tree/main/dracut-iguana)
 * [kairos-io](https://github.com/kairos-io/packages/tree/main/packages/system/dracut/immutable-rootfs/30cos-immutable-rootfs)
 * [KaOS](https://github.com/KaOSx/core/blob/master/dracut)
 * [cloud-initramfs-tools](https://github.com/larsks/cloud-initramfs-tools/tree/master/growroot/dracut/modules.d/50growroot)
 * [zfsbootmenu](https://github.com/zbm-dev/zfsbootmenu/tree/master/dracut)
 * [gardenlinux-live](https://github.com/gardenlinux/gardenlinux/tree/main/features/_pxe/file.include/usr/lib/dracut/modules.d/98gardenlinux-live)
 
 # OSS search
 * [dracut on Github](https://github.com/topics/dracut)
 * [dracut-module on Github](https://github.com/topics/dracut-module)

# Other notable projects using dracut (without an out-of-tree dracut modules)
 * [livecd-tools](https://github.com/livecd-tools/livecd-tools)
 * [lorax](https://github.com/weldr/lorax)
 * [mkosi](https://github.com/systemd/mkosi)
 * [rear](https://github.com/rear/rear)
 * [calamares](https://github.com/calamares/calamares)
 * [voidvault](https://github.com/atweiden/voidvault)

## Resources
* [Linux initramfs for fun](https://www.youtube.com/watch?v=KQjRnuwb7is)
* [How to use initramfs](https://landley.net/writing/rootfs-howto.html)
