# C++ Hello World Example

This repository contains a very small C++ starter program.

## Project Contents

- `hello_world.cpp`: A basic C++ program with a `main()` function that prints:
  - `Hello, AI Course!`

## What the Program Does

The program:

1. Includes the iostream library for console output.
2. Uses `cout` to print a single line of text.
3. Returns `0` to show successful execution.

## Build and Run

### Option 1: Using g++ (MinGW or similar)

Compile:

```bash
g++ hello_world.cpp -o hello_world
```

Run:

```bash
./hello_world
```

On Windows Command Prompt, you can also run:

```bash
hello_world.exe
```

### Option 2: Using MSVC (Developer Command Prompt)

Compile:

```bat
cl /EHsc hello_world.cpp
```

Run:

```bat
hello_world.exe
```

## Expected Output

```text
Hello, AI Course!
```

## Purpose

This project is useful for beginners who want to practice:

- basic C++ file structure,
- compiling from the command line,
- and running a console application.
