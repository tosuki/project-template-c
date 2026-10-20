# cursorgen

A simple Xcursor file generator in C.

## Project Structure

```text
.
├── Makefile
├── README.md
└── src/
    └── main.c
```

## Prerequisites

- C compiler (`clang` or `gcc`)
- `make`

## Building and Running

### Build the project

```bash
make
```

The binary will be generated at `bin/cursorgen`.

### Build and run

```bash
make run
```

To pass command-line arguments when running via `make`:

```bash
make run ARGS="arg1 arg2"
```

Or run the binary directly:

```bash
./bin/cursorgen
```

### Clean build artifacts

Removes the `build/` and `bin/` directories:

```bash
make clean
```
