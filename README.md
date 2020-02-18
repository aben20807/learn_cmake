# Learn cmake command

+ A simple project for testing cmake command.

## References

+ [[YouTube] How to CMake Good - 1c - Subdirectories and Target Interface Properties by vector-of-bool](https://www.youtube.com/watch?v=SYgESCQeGJY)

## Usage

```bash
mkdir build
cd build
cmake ..
make
./bin/exec
```

## Files
```bash
$ tree -F -I 'build|LICENSE|*.md' .
.
├── CMakeLists.txt
├── extern/
│   ├── say_hello/
│   │   ├── CMakeLists.txt
│   │   └── src/
│   │       └── say_hello_util/
│   │           ├── hello.cpp
│   │           └── hello.hpp
│   └── sum/
│       ├── CMakeLists.txt
│       ├── include/
│       │   └── sum_header/
│       │       └── sum.hpp
│       └── src/
│           └── sum/
│               └── sum.cpp
└── src/
    ├── CMakeLists.txt
    └── main.cpp
```