[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/Paebbels/GCC-Toolchains)

[![GCC Toolchain for AArch64 with NewLib](https://github.com/Paebbels/GCC-Toolchains/actions/workflows/gcc.yaml/badge.svg)](https://github.com/Paebbels/GCC-Toolchains/actions/workflows/gcc.yaml)

# GCC-Toolchains

This projects compiles GCC toolchains froms scratch for embedded platforms.

## Supported Embedded Platforms
* Xilinx Zynq-7000
  * ARM A9 &rarr; tbd
* Xilinx Zynq UltraScale+ MPSoC
  * ARM R5 &rarr; GCC 11.1.0 (binutils 2.36.1) `arm-none-elf` with newlib 4.1.0
  * ARM A53 &rarr; GCC 11.1.0 (binutils 2.36.1) `aarch64-none-elf` with newlib 4.1.0

## Supported Hosts
* Ubuntu 20.04
