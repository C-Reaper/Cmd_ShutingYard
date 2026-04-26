# Project README

## Overview
This project contains a C/C++ implementation of an evaluator for arithmetic expressions using the Shunting Yard algorithm. The primary goal is to demonstrate parsing and evaluating mathematical expressions.

## Features
- Parsing of arithmetic expressions with support for addition, multiplication, parentheses, and unary negation.
- Output of parsed tokens and execution results.

## Project Structure
### Prerequisites
- C/C++ Compiler and Debugger (GCC, Clang)
- Make utility
- Standard development tools

## Build & Run
### Build Process
To build the project on Linux:
```bash
cd <Project>
make -f Makefile.linux all
```

To build the project on Windows:
```bash
cd <Project>
make -f Makefile.windows all
```

To build the project on Wine for Windows:
```bash
cd <Project>
make -f Makefile.wine all
```

To build the project using Emscripten for WebAssembly:
```bash
cd <Project>
make -f Makefile.web all
```

### Execution
After building, you can run the executable:
```bash
make -f Makefile.(os) exe
```
Replace `(os)` with `linux`, `windows`, `wine`, or `web` depending on your target platform.