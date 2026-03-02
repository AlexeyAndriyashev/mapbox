# hello_world

A C++ hello world project.

## Build

```bash
# Build the active file
Cmd+Shift+B

# Or manually
clang++ -std=c++23 -g hello.cpp -o hello
```

## Run

```bash
./hello
```

## Toolchain

- Compiler: Apple clang++ 17 (`/usr/bin/clang++`)
- Standard: C++23
- Platform: macOS arm64

## Project structure

- `hello.cpp` — main source file
- `.vscode/tasks.json` — VS Code build task
