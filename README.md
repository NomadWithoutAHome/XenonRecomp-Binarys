# XenonDecomp Binary Builds

Pre-compiled binaries of [XenonRecomp](https://github.com/hedge-dev/XenonRecomp) for Linux and Windows platforms. 

Binaries Builts: 3/8/2025

## Description

These are pre-compiled binaries of the XenonRecomp tool, which converts Xbox 360 executables into C++ code that can be recompiled for any platform. The original tool was developed by hedge-dev team.

## Available Builds

### Linux
- XenonAnalyse
- XenonRecomp
- XenonTests
- XenonUtils

### Windows (Coming Soon)
- XenonAnalyse.exe
- XenonRecomp.exe
- XenonTests.exe
- XenonUtils.exe

## System Requirements

### Linux
- x86_64 architecture
- glibc 2.31 or later
- LLVM/Clang runtime libraries

### Windows
- x64 architecture
- Windows 10 or later
- Microsoft Visual C++ Redistributable 2022

## Usage

1. Download the appropriate binary for your platform
2. Ensure you have the required dependencies installed
3. Basic command syntax:
```bash
XenonRecomp [input directory path] [input PPC context header file path] [output directory path]
```

## Build Information

These binaries were compiled using:
- Clang 18
- CMake 3.20+
- Built with optimizations for x86 platforms

## Known Limitations

- Currently only supports x86 platforms due to x86 intrinsics usage
- Some PPC instructions may not be fully implemented
- Vector register handling requires specific endianness considerations

## Legal Notice

These builds are provided under the MIT License, same as the original XenonRecomp project. This is an unofficial build and not affiliated with the original project maintainers.

## Credits

Original XenonRecomp project by hedge-dev team:
- [Original Repository](https://github.com/hedge-dev/XenonRecomp)
- Special thanks to the Xenia emulator team

## Support

For issues related to these builds, please open an issue in this repository.
For issues with the XenonRecomp tool itself, please refer to the [original repository](https://github.com/hedge-dev/XenonRecomp).
