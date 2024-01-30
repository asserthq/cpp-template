# cpp-template

## Features
- **CMake** as buildsystem
- **CMake Presets** for simplier managing
- **vcpkg** as package manager

## Plans
- [x] One template for most cases
- [ ] Ability to choose concrete set of features in each case
    - Buildsystem
        - [ ] premake
        - [ ] conan2 (?)
    - Package manager
        - [ ] vcpkg
        - [ ] conan2
    - Unit testing
        - [ ] GTest
    -  CI/CD
        - [ ] Github Actions
    - Others
        - [ ] CMake presets
        - [ ] invoke.py

## Usage

### Set up

```sh
git clone --recurse-submodules https://github.com/asserthq/cpp-template.git
cd cpp-template
./vcpkg/bootstrap-vcpkg.sh
```

### Configure and build

```sh
cmake --preset debug
cmake --build --preset debug
```
