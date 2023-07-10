# llvm-msvc-vcpkg-test
vcpkg test for llvm-msvc


## Requirements

- Visual Studio 2022
- CMake 3.15+
- [llvm-msvc](https://github.com/NewWorldComingSoon/llvm-msvc-build/releases)

## Building with llvm-msvc

```
cmake -Bbuild -TLLVM-MSVC_v143
cmake --build build --config Release
```
