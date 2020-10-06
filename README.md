# Description

Use libvorbis package for testing CMAKE / Ninja build.

# Building

- conan create . 1.3.7@dev/test
- conan create . 1.3.7@dev/test --profile VS2017


# PROFILES


default
```
[settings]
os=Windows
os_build=Windows
arch=x86_64
arch_build=x86_64
compiler=Visual Studio
compiler.version=15
build_type=Release
[options]
[build_requires]
[env]
```

VS2017
```
[settings]
os=Windows
os_build=Windows
arch=x86_64
arch_build=x86_64
compiler=Visual Studio
compiler.version=15
build_type=Release
[options]
[build_requires]
[env]
```
