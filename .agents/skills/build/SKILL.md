---
name: build
description: Build the project from source
user-invocable: true
---

# Build Instructions

Build the project using the project's build system. Check the project root for:
- `Makefile` → run `make`
- `CMakeLists.txt` → run `cmake -B build && cmake --build build`
- `package.json` → run `npm run build`
- `Cargo.toml` → run `cargo build`
- `pyproject.toml` → run `pip install -e .`

Report build success or failure with specific error messages.
