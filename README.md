# glfw_bin

This repo is just a GitHub action file that tries to build GLFW static libraries.

## Supported Platforms:

- macOS ARM (aarch64) ✅
- macOS Intel (x86_64) ✅
- linux ARM (aarch64) ✅
- linux x64 (x86_64) ✅
- windows ARM (aarch64) ❌ - PRs welcomed
- windows x64 (x86_64) ❌ - PRs welcomed

## Sample link command

macOS:

```bash
clang -o main_release -O3 main.c glfw-release/lib/libglfw3.a -I glfw-release/include -framework CoreFoundation -framework Cocoa -framework IOKit -framework QuartzCore
```
