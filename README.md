# CPP Beginner

This doc is to get familiar with the basics of CPP

## Build

```sh
clang++ src/main.cpp -o main && ./main
```

### Breakdown

| Column 1     | Column 2 |
| ---          | ---      |
| clang++      | The C++ compiler (Clang, Apple's default on macOS) |
| src/main.cpp | Your source file to compile |
| -o main      | -o = "output"; name the resulting executable main (instead of the default a.out) |
| &&           | "And if that succeeded, then..." — only runs the next command if the compile had no errors |
| ./main       | Run the program. ./ means "the current directory" (needed because main isn't on your PATH) |
