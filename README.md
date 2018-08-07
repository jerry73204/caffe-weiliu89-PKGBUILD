# PKGBUILD files for weiliu89's caffe

The repository aims to provide PKGBUILD files for [weiliu89's caffe](https://github.com/weiliu89/caffe/tree/ssd). The files `PKGBUILD.gpu` and `PKGBUILD.cpu` are respectively for GPU-enabled and -disabled builds.

It is tested on Arch Linux. For other pacman-based systems, please use with caution.

## Usage

Here assumes Arch Linux. Copy to `PKGBUILD` and run `makepkg` to build package.

```sh
# For example, copy GPU-enabled PKGBUILD
cp PKGBUILD.gpu PKGBUILD

# build and install
makepkg
pacman -U caffe-ssd-xxx-y-zzz.pkg.tar.xz
```
