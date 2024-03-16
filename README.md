# Simple C++ Cookiecutter 

This repository contains a simple C++ project template for Cookiecutter that I use for most of my C++ projects.

## Features
- Simple C++ project structure
- CMake build system
- Catch for unit tests
- Cookiecutter for project creation
- Git for version control
- GitHub for hosting

## Usage
1. Make sure you have installed [Cookiecutter](https://github.com/audreyr/cookiecutter).
2. Run `cookiecutter https://github.com/thacoon/cookiecutter-cpp-simple.git` in your terminal.
3. Now a new folder should have been created with the following tree structure:
```bash
├── CMakeLists.txt
├── bin
├── build
├── main.cpp
├── src
│   ├── myclass.cpp
│   └── myclass.hpp
└── tests
    ├── CMakeLists.txt
    ├── SmokeTests.cpp
    ├── bin
    ├── build
    └── catch.hpp
```


## Future work
- Add support for Travis CI
- Add support for AppVeyor
- Add support for Conan
- Add support for Doxygen
- Add support for Cppcheck


