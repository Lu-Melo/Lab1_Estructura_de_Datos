# C Lab: Lists and Stacks (Listas y Pilas)

## Overview
A university lab exercise in C covering Array Lists and Stacks (TDA Lista y TDA Pila).

## Project Structure
- `exercises.c` — Student implementation file (the only file to modify)
- `arraylist.h` / `arraylist.c` — ArrayList TDA implementation
- `stack.h` — Stack TDA header
- `test.c` — Automated test suite
- `test.sh` — Build and test runner script

## Running Tests
Open the Shell and run:
```bash
bash test.sh
```

This compiles `test.c` with GCC and runs all tests, showing pass/fail counts.

## Important Notes
- Only `exercises.c` should be modified by the student.
- No frontend or backend web server — this is a pure C project.
- The `Run Tests` workflow executes `bash test.sh`.
