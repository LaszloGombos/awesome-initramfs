[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


Usual flow
```
fw -> bootloader -> kernel -> initramfs -> rootfs
```

In its simplest form (no separate initramfs, init included in the kernel)
```
fw -> kernel (init included)
```

No initramfs, separate rootfs
```
fw -> kernel -> rootfs 
```


> A curated list of awesome initramfs resources.

## Contents

- [Projects](#projects)
- [Documentation](#documentation)
- [Resources](#resources)

## Projects
* [dracut](https://github.com/dracut-ng/dracut-ng) - default on Fedora, OpenSUSE, Gentoo, Void
* [mkinitcpio](https://github.com/archlinux/mkinitcpio) - default on Arch
* [initramfs-tools](https://salsa.debian.org/kernel-team/initramfs-tools) - default on Debian
* [make-initrd](https://github.com/osboot/make-initrd) - default on AltLinux
* [mkinitfs](https://gitlab.alpinelinux.org/alpine/mkinitfs/) - default on Alpine
* [Minimal Builder Using Terse Options](https://mbuto.sh/mbuto) - Host-agnostic initramfs image builder for lightweight virtual machines
* [booster](https://github.com/anatol/booster) - Golang
* [genkernel](https://gitweb.gentoo.org/proj/genkernel.git) - Gentoo
* [u-root](https://github.com/u-root/u-root) - Golang
* [mkosi](https://github.com/systemd/mkosi/tree/main/mkosi/resources/mkosi-initrd) - use system packages (not just individual files)
* [gen_initramfs](https://github.com/torvalds/linux/blob/master/usr/gen_initramfs.sh)
* [better-initramfs](https://github.com/slashbeast/better-initramfs) - Bash shell, busybox
* [tiny-initramfs](https://github.com/chris-se/tiny-initramfs) - C, works great
* [tinyramfs](https://github.com/illiliti/tinyramfs) - POSIX shell
* [clr-init](https://github.com/clearlinux/clr-init) - Clear Linux
* [jamdisk](https://github.com/cbdevnet/jamdisk)
* [micro-rootfs](https://github.com/loicpoulain/micro-rootfs) - buildroot
* [tinycorelinux](https://github.com/tinycorelinux/Core-scripts/blob/master/init) - initramfs distro (no switch_root)
* [mkroot/toybox](https://github.com/landley/toybox/blob/master/mkroot/mkroot.sh) - minimal initramfs distro
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

## How to avoid having a need for initramfs
* build-in all kernel modules that needed to mount rootfs
* use root=/dev/sda (avoid using UUID)

## Build initramfs into the kernel
* [CONFIG_INITRAMFS_SOURCE](https://www.kernelconfig.io/CONFIG_INITRAMFS_SOURCE)

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

# Notable Dracut packages/patches/forks
 * [nix](https://github.com/NixOS/nixpkgs/tree/master/pkgs/os-specific/linux/dracut)
 * [pld](https://git.pld-linux.org/?p=packages/dracut.git;a=tree)
 * [ubuntu](https://git.launchpad.net/ubuntu/+source/dracut/tree/)
 * [rhel](https://github.com/redhat-plumbers/dracut-rhel8)
 * [t2sde](https://github.com/rxrbln/t2sde/tree/main/package/contrib/dracut)
 * [adelielinux](https://git.adelielinux.org/adelie/packages/-/tree/current/user/dracut)
 * [alpine](https://gitlab.alpinelinux.org/alpine/aports/-/tree/master/community/dracut)
 * [altlinux](https://git.altlinux.org/gears/d/dracut.git)
 * [arch](https://gitlab.archlinux.org/archlinux/packaging/packages/dracut)
 * [artixlinux](https://gitea.artixlinux.org/packages/dracut)
 * [aosc](https://github.com/AOSC-Dev/aosc-os-abbs/tree/stable/app-admin/dracut)
 * [azurelinux](https://github.com/microsoft/azurelinux/tree/2.0/SPECS/dracut)
 * [azurelinux-3](https://github.com/microsoft/azurelinux/tree/3.0/SPECS/dracut)
 * [buildroot](https://gitlab.com/buildroot.org/buildroot/-/tree/master/package/dracut)
 * [buildroot](https://git.busybox.net/buildroot/tree/package/dracut)
 * [debian](https://salsa.debian.org/debian/dracut/)
 * [crux](https://crux.nu/ports/opt/3.8/dracut/)
 * [distri](https://github.com/distr1/distri/tree/master/pkgs/dracut)
 * [fedora](https://github.com/redhat-plumbers/dracut-fedora)
 * [fedora-rpm](https://src.fedoraproject.org/rpms/dracut)
 * [freedesktop-sdk](https://gitlab.com/freedesktop-sdk/freedesktop-sdk/-/tree/master/patches/dracut)
 * [gentoo](https://github.com/gentoo/gentoo/blob/master/sys-kernel/dracut)
 * [gobolinux](https://github.com/gobolinux/Recipes/tree/master/Dracut)
 * [openembedded](https://git.openembedded.org/meta-openembedded/tree/meta-initramfs/recipes-devtools/dracut)
 * [openeuler](https://gitee.com/src-openeuler/dracut)
 * [openmandriva](https://github.com/OpenMandrivaAssociation/dracut)
 * [opensuse](https://github.com/openSUSE/dracut-ng)
 * [photonos](https://github.com/vmware/photon/tree/master/SPECS/dracut)
 * [rosa](https://abf.io/import/dracut)
 * [slack](https://git.slackbuilds.org/slackbuilds/tree/system/dracut)
 * [solus](https://github.com/getsolus/packages/tree/main/packages/d/dracut)
 * [spack](https://github.com/spack/spack/blob/develop/var/spack/repos/builtin/packages/dracut/package.py)
 * [void](https://github.com/void-linux/void-packages/tree/master/srcpkgs/dracut)

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
 * [bootengine](https://github.com/flatcar/bootengine)
 * [qubes-antievilmaid](https://github.com/QubesOS/qubes-antievilmaid/tree/master/90anti-evil-maid)
 * [dracut-encryptrootfs](https://github.com/Symantec/dracut-encryptrootfs)
 * [Fedora CoreOS](https://github.com/coreos/fedora-coreos-config/tree/testing-devel/overlay.d/05core/usr/lib/dracut/modules.d)
 * [dracut-iguana](https://github.com/aaannz/dracut-iguana)
 * [mkinitcpio-ykfde](https://github.com/eworm-de/mkinitcpio-ykfde/tree/master/dracut)
 * [dracut-ntfsloop](https://github.com/genosse-einhorn/dracut-ntfsloop)
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
 * [Debian installer](https://github.com/r0b0/debian-installer/tree/master/installer-files/usr/lib/dracut/modules.d/90overlay-generic)
 * [FIDO Device Onboard (FDO)](https://github.com/fdo-rs/fido-device-onboard-rs/tree/main/dracut/52fdo)
 * [initoverlayfs](https://github.com/containers/initoverlayfs)
   
 # OSS search
 * [dracut on Github](https://github.com/topics/dracut)
 * [dracut-module on Github](https://github.com/topics/dracut-module)

# Other notable projects using dracut 
(without an out-of-tree dracut modules)
 * [livecd-tools](https://github.com/livecd-tools/livecd-tools)
 * [lorax](https://github.com/weldr/lorax)
 * [rear](https://github.com/rear/rear)
 * [calamares](https://github.com/calamares/calamares)
 * [voidvault](https://github.com/atweiden/voidvault)
 * [grml-debootstrap](https://github.com/grml/grml-debootstrap)
 * [core-initrd](https://github.com/snapcore/core-initrd) - Ubuntu Core Linux
 * [Open-CAS](https://github.com/Open-CAS/open-cas-linux)

## How to avoid the need for initramfs
 * build-in kernel modules into the kernel that is needed to mount rootfs (e.g. CONFIG_EXT4_FS=y)
 * set root= kernel command line argument (see https://www.kernel.org/doc/html/v6.4/admin-guide/kernel-parameters.html)

## Resources
* [Linux initramfs for fun](https://www.youtube.com/watch?v=KQjRnuwb7is)
* [How to use initramfs](https://landley.net/writing/rootfs-howto.html)
