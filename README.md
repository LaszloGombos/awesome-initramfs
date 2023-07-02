[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome initramfs resources.

## Contents

- [Projects](#projects)
- [Documentation](#documentation)
- [Resources](#resources)

## Projects
* [dracut](https://github.com/dracutdevs/dracut) - Fedora, Debian, Arch, Alpine
* [mkinitcpio](https://github.com/archlinux/mkinitcpio) - Arch
* [initramfs-tools](https://salsa.debian.org/kernel-team/initramfs-tools) - Debian
* [make-initrd](https://github.com/osboot/make-initrd) - AltLinux
* [mkinitfs](https://gitlab.alpinelinux.org/alpine/mkinitfs/) - Alpine
* [Minimal Builder Using Terse Options](https://mbuto.sh/mbuto) - Host-agnostic initramfs image builder for lightweight virtual machines
* [booster](https://github.com/anatol/booster) - Golang
* [genkernel](https://gitweb.gentoo.org/proj/genkernel.git) - Gentoo
* [u-root](https://github.com/u-root/u-root) - Golang
* [mkosi-initrd](https://github.com/systemd/mkosi-initrd) - use system packages
* [gen_initramfs](https://github.com/torvalds/linux/blob/master/usr/gen_initramfs.sh)
* [better-initramfs](https://github.com/slashbeast/better-initramfs) - Bash shell, busybox
* [tiny-initramfs](https://github.com/chris-se/tiny-initramfs) - C, works great
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

# Notable Dracut forks
 * [openSUSE](https://github.com/openSUSE/dracut)
 * [Debian](https://salsa.debian.org/debian/dracut)
 * [Fedora](https://src.fedoraproject.org/rpms/dracut)

# Notable Dracut packages/patches
 * [Gentoo](https://github.com/gentoo/gentoo/blob/master/sys-kernel/dracut)
 * [Void](https://github.com/void-linux/void-packages/tree/master/srcpkgs/dracut)
 * [Alpine](https://gitlab.alpinelinux.org/alpine/aports/-/tree/master/community/dracut)
 * [CBL-Mariner](https://github.com/microsoft/CBL-Mariner/tree/2.0/SPECS/dracut)
 * [distri](https://github.com/distr1/distri/tree/master/pkgs/dracut)
 * [Nix](https://github.com/NixOS/nixpkgs/tree/master/pkgs/os-specific/linux/dracut)
 * [Solus](https://dev.getsol.us/source/dracut/)
 * [Slack](https://git.slackbuilds.org/slackbuilds/tree/system/dracut)
 * [pld](https://git.pld-linux.org/?p=packages/dracut.git;a=tree)
 * [OpenMandriva](https://github.com/OpenMandrivaAssociation/dracut)
 * [Arch](https://gitlab.archlinux.org/archlinux/packaging/packages/dracut)
 * [AOSC](https://github.com/AOSC-Dev/aosc-os-abbs/tree/stable/app-admin/dracut)
 * [altlinux](https://github.com/altlinux/specs/tree/sisyphus/d/dracut)

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
 * [immucore](https://github.com/kairos-io/immucore)
 * [KaOS](https://github.com/KaOSx/core/blob/master/dracut)
 * [cloud-initramfs-tools](https://github.com/larsks/cloud-initramfs-tools/tree/master/growroot/dracut/modules.d/50growroot)
 * [zfsbootmenu](https://github.com/zbm-dev/zfsbootmenu/tree/master/dracut)
 * [gardenlinux-live](https://github.com/gardenlinux/gardenlinux/tree/main/features/_pxe/file.include/usr/lib/dracut/modules.d/98gardenlinux-live)
 * [hrmpf](https://github.com/leahneukirchen/hrmpf/tree/master/dracut)
 * [Cray-HPE/metal-dmk8s](https://github.com/Cray-HPE/dracut-metal-dmk8s/tree/main/93metaldmk8s)
 * [Cray-HPE/metal-mdsquash](https://github.com/Cray-HPE/dracut-metal-mdsquash/tree/main/90metalmdsquash)
 * [AsahiLinux](https://github.com/AsahiLinux/asahi-scripts/tree/main/dracut)
 
 # OSS search
 * [dracut on Github](https://github.com/topics/dracut)
 * [dracut-module on Github](https://github.com/topics/dracut-module)

# Other notable projects using dracut 
(without an out-of-tree dracut modules)
 * [livecd-tools](https://github.com/livecd-tools/livecd-tools)
 * [lorax](https://github.com/weldr/lorax)
 * [mkosi](https://github.com/systemd/mkosi)
 * [rear](https://github.com/rear/rear)
 * [calamares](https://github.com/calamares/calamares)
 * [voidvault](https://github.com/atweiden/voidvault)

## How to avoid the need for initramfs
 * build-in kernel modules into the kernel that is needed to mount rootfs (e.g. CONFIG_EXT4_FS=y)
 * set root= kernel command line argument (see https://www.kernel.org/doc/html/v6.4/admin-guide/kernel-parameters.html)

## Resources
* [Linux initramfs for fun](https://www.youtube.com/watch?v=KQjRnuwb7is)
* [How to use initramfs](https://landley.net/writing/rootfs-howto.html)
