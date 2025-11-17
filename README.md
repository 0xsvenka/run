# Simple Bash Script to Build & Run Single C++ Source File

Usage:

- Build with debug symbols on

  ```
  run -d <source_file>
  ```

  which is equivalent to:

  ```
  g++ -g -o <source_file> <source_file>.cpp
  ```

- Build with -O2 optimization and run directly

  ```
  run <source_file>
  ```

  which is equivalent to:

  ```
  g++ -O2 -o <source_file> <source_file>.cpp
  ./<source_file>
  ```

Note that <source_file> should not include the ".cpp" extension.
