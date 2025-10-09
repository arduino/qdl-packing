# qdl-packing

This repository contains the release pipeline to build [qdl](https://github.com/linux-msm/qdl) statically on multiple platforms:
- Linux 64bit
- Linux 32bit
- Linux ARMv6
- Linux ARM64
- MacOS 64bit
- MacOS ARM64
- Windows 32bit

The compilation workflow uses the [arduino/crossbuild](https://github.com/arduino/crossbuild) docker image, wich container all the needed dependencies and toolchanin.

