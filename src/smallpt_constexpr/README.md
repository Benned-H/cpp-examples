# `constexpr` All the Things

This folder contains a refactored version of [smallpt](https://www.kevinbeason.com/smallpt/), a global illumination renderer originally written by [Kevin Beason](http://kevinbeason.com/). The refactor exercise, proposed in Jason Turner's C++ Weekly series, modifies the original implementation to use the `constexpr` feature (introduced in C++11) as much as possible.

To make this example, run the following command from the root of the repository:

```bash
g++ -O3 -Wpedantic -Wall -Wextra -Wconversion -std=c++20 src/smallpt_constexpr/smallpt.cpp -o build/smallpt
```

Then, run the example with:

```bash
time ./build/smallpt 40
```
