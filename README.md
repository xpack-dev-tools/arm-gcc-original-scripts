# arm-gcc-original-scripts

This [GitHub project](https://github.com/xpack-dev-tools/arm-gcc-original-scripts.git)
keeps a copy of the ARM original scripts used to build
[GNU ARM Embedded Toolchain](https://developer.arm.com/open-source/gnu-toolchain/gnu-rm),
to easily identify the differences between releases.

It includes all existing files in the root folder, except the
`How-to-build-toolchain.pdf`.

Note: there is also a GitHub project
[ARM-software/toolchain-gnu-bare-metal](https://github.com/ARM-software/toolchain-gnu-bare-metal), with the build scripts, but it does not seem up
to date.

## How to update

To update this repo:

- download the source tarball from https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads
- unpack the `.bz2`; the result is a folder like
`gcc-arm-none-eabi-9-2019-q4-major`
- clone from GitHub repo from https://github.com/xpack-dev-tools/arm-gcc-original-scripts.git
- remove all files except this `README.md` and the `.git`
- copy all files except the `How-to-build-toolchain.pdf`
- commit the changes with a message like _9-2019-q4-major_
- update this README.md with the new version name and URL
- commit with a message like _README.md: add new version_
- add a tag like _9-2019-q4-major_

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

### gcc-arm-none-eabi-9-2020-q2-update

- v9.3.1
- https://developer.arm.com/-/media/Files/downloads/gnu-rm/9-2020q2/gcc-arm-none-eabi-9-2020-q2-update-src.tar.bz2

```
% ls -l src
total 404976
-rw-r--r--@ 1 ilg  staff  40194618 May 21 15:31 binutils.tar.bz2
-rw-rw-r--@ 1 ilg  staff    281051 May 27 21:48 build-manual.tar.bz2
-rw-r--r--@ 1 ilg  staff    405103 May 21 15:33 expat-2.1.1.tar.bz2
-rw-r--r--@ 1 ilg  staff  89297302 May 21 15:32 gcc.tar.bz2
-rw-r--r--@ 1 ilg  staff  38102986 May 21 15:33 gdb.tar.bz2
-rw-r--r--@ 1 ilg  staff   2383840 May 21 15:33 gmp-6.1.0.tar.bz2
-rw-r--r--@ 1 ilg  staff      2820 May 21 15:33 installation.tar.bz2
-rw-r--r--@ 1 ilg  staff   1475708 May 21 15:33 isl-0.18.tar.xz
-rw-r--r--@ 1 ilg  staff    148529 May 21 15:33 libelf-0.8.13.tar.gz
-rw-r--r--@ 1 ilg  staff   5264188 May 21 15:33 libiconv-1.15.tar.gz
-rw-r--r--@ 1 ilg  staff    669925 May 21 15:33 mpc-1.0.3.tar.gz
-rw-r--r--@ 1 ilg  staff   1279284 May 21 15:33 mpfr-3.1.4.tar.bz2
-rw-r--r--@ 1 ilg  staff  13980378 May 21 15:33 newlib.tar.bz2
-rw-r--r--@ 1 ilg  staff      9372 May 21 15:33 samples.tar.bz2
-rw-r--r--@ 1 ilg  staff    571091 May 21 15:33 zlib-1.2.8.tar.gz
```
