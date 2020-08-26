# Aug.26.2020
## Development environment construction.
### 1.Run Ubuntu in Windows by ```WSL```

    To install WSL2, I update my Windows to version 20197.1000.After that, just download Ubuntu in the Microsoft Store, and install.

### 2.Building a Cross-Compiler
Preparation
```
export PREFIX="$HOME/opt/cross"
export TARGET=i686-elf
export PATH="$PREFIX/bin:$PATH"
```
