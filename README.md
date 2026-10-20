# C Project Template

A simple and lightweight boilerplate template for C projects using `make`.

## Project Structure

```text
.
├── .gitignore
├── Makefile
├── README.md
└── src/
    └── main.c
```

- **`src/`**: Place all your C source files (`.c`) here.
- **`build/`**: Temporary object files (`.o`) generated during compilation (git-ignored).
- **`bin/`**: Final compiled binary output (git-ignored).

## Prerequisites

- A C compiler (`clang` or `gcc`)
- `make`

## Getting Started

### Build

Compile the project:

```bash
make
```

The compiled binary will be placed in the `bin/` directory.

### Run

Compile (if needed) and run the executable:

```bash
make run
```

Pass command-line arguments to your program:

```bash
make run ARGS="arg1 arg2"
```

You can also run the binary directly:

```bash
./bin/$(TARGET)
```

### Clean

Remove all compilation artifacts (`build/` and `bin/`):

```bash
make clean
```

## Customization

You can adjust build configurations directly in [Makefile](file:///Users/carlos/Documents/Projects/cursorgen/Makefile):

- **`TARGET`**: Name of the generated binary output.
- **`CC`**: Compiler (`cc`, `clang`, `gcc`, etc.).
- **`CFLAGS`**: Compiler flags (optimization, warning levels, C standard version).
