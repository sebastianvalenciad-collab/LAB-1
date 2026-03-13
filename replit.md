# C Data Structures Lab

A student lab project for practicing C data structures — specifically linked lists and stacks.

## Project Structure

- `exercises.c` — Student exercise file (the only file students should modify)
- `arraylist.h` — ArrayList/List TDA header
- `arraylist.c` — ArrayList/List TDA implementation
- `stack.h` — Stack TDA header
- `test.c` — Test suite
- `test.sh` — Test runner script (compiles and runs tests)

## Running Tests

Open the Shell and run:

```bash
bash test.sh
```

Or use the "Run Tests" workflow which executes `bash test.sh`.

## Workflow

- **Run Tests** — Runs `bash test.sh` (console output)

## Notes

- No frontend or backend server — this is a pure C project
- Students should only modify `exercises.c`
- Tests are compiled with: `gcc -g test.c -Wall -Werror -o a.out`
