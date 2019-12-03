# arm-gcc-original-scripts

These project keeps a copy of the ARM original scripts used to build
[GNU ARM Embedded Toolchain](https://developer.arm.com/open-source/gnu-toolchain/gnu-rm),
to easily identify the differences between releases.

It includes all existing files in the root folder, except the
`How-to-build-toolchain.pdf`.

## How to update

To update this repo:

- download the source tarball from https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads
- unpack the .bz2; the result is afolder like
`gcc-arm-none-eabi-9-2019-q4-major`
- clone from GitHub repo from https://github.com/xpack-dev-tools/arm-gcc-original-scripts.git
- remove all files except this `README.md` and the `.git`
- copy all files except the `How-to-build-toolchain.pdf`
- commit the changes with a message like _9-2019-q4-major_
- update this README.md with the new version name and URL
- commit with a message like _README.md: add new version_

## Versions

The main GCC version is in `gcc/gcc/BASE-VER`.

### gcc-arm-none-eabi-6-2017-q2-update

- v6.3.1
- https://developer.arm.com/-/media/Files/downloads/gnu-rm/6-2017q2/gcc-arm-none-eabi-6-2017-q2-update-src.tar.bz2

### gcc-arm-none-eabi-7-2017-q4-major

- v7.2.1
- https://developer.arm.com/-/media/Files/downloads/gnu-rm/7-2017q4/gcc-arm-none-eabi-7-2017-q4-major-src.tar.bz2

### gcc-arm-none-eabi-7-2018-q2-update

- v7.3.1
- https://developer.arm.com/-/media/Files/downloads/gnu-rm/7-2018q2/gcc-arm-none-eabi-7-2018-q2-update-src.tar.bz2

### gcc-arm-none-eabi-8-2018-q4-major

- v8.2.1
- https://developer.arm.com/-/media/Files/downloads/gnu-rm/8-2018q4/gcc-arm-none-eabi-8-2018-q4-major-src.tar.bz2

### gcc-arm-none-eabi-9-2019-q4-major

- v9.2.1
- https://developer.arm.com/-/media/Files/downloads/gnu-rm/9-2019q4/gcc-arm-none-eabi-9-2019-q4-major-src.tar.bz2

