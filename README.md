# CircuitPython Devtools

This repository contains convenience scripts for developing CircuitPython programs on macOS for the Raspberry Pi Pico family of devices. It is meant to be reusable across multiple projects by adding this repository as a Git submodule instead of copying scripts each time.

## Setup
Add a submodule to the main project repository:
```sh
git submodule add https://github.com/ide/circuitpython-devtools.git
```

Add the submodule's `bin` directory to `PATH`. For instance, with [direnv](https://direnv.net/):
```sh
# .envrc
PATH_add circuitpython-devtools/bin
```

## Documentation
Read the code under `bin`.
