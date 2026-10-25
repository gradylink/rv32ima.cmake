# rv32ima.cmake

Simple RV32IMA emulator for CMake's script mode. Yes, it is slow.

## Requirements

- CMake >= 3.12
- An image compiled for RV32IMA, e.g. one from
  [mini-rv32ima-images](https://github.com/cnlohr/mini-rv32ima-images/)

## Usage

```
cmake -DIMAGE=Image [-DDTB=minimal.dtb] -P rv32ima.cmake
```
