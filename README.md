# crosstool-ng-misc

configs, etc., for **crosstool-ng** toolchains

primarily intended for future **crosware** consumption for running glibc binaries on musl systems

## TODO

- investigate `--enable-static-nss`
- `patchelf` for rpath/loader with static nss?
- arches
  - `aarch64-linux-gnu`
  - `arm-linux-gnueabihf`
  - `i686-linux-gnu`
  - `riscv64-linux-gnu`
  - `x86_64-linux-gnu`

## links

- crosstool-ng: https://github.com/crosstool-ng/crosstool-ng
- crosware: https://github.com/ryanwoodsmall/crosware
- musl-cross-make: https://github.com/richfelker/musl-cross-make
- dockcross: https://github.com/dockcross/dockcross - LOTS of useful info for toolchain building/features/etc.
