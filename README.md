# low-level-design-cpp

A collection of low-level designs in modern C++, with an embedded and systems focus. Each design has working code, tests, and a write-up of the trade-offs.

## Build and run
Each design is a self-contained folder:

    cd 01-ring-buffer
    clang++ -std=c++17 -Wall -Wextra -fsanitize=address,undefined main.cpp -o out && ./out

## Repo layout
    NN-design-name/
      README.md   design notes for that design
      *.hpp       implementation
      main.cpp    tests (asserts)
