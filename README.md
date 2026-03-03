# xequery

A small utility extending `equery` for inspecting Gentoo repositories and packages.

`xequery` provides quick commands for listing available repositories and querying packages inside a specific repository. These functionalities are either very verbose, inconvenient or non existent with raw `equery`.

## Current features
- Simple and intuitive commands
- List all configured repositories
- List packages belonging to a specific repository

## Usage

### List all used repositories

```bash
xequery list repos
```

Example:
```bash
xequery list repos
crossdev
farmboy0
gentoo
guru
pentoo
```


### List all installed packages from a specific repository

```bash
xequery list pkgs <repository>
```

Example:
```bash
xequery list pkgs pentoo
dev-util/ghidra-11.4.2
xequery list pkgs farmboy0
kde-misc/corectrl-1.5.2
```

## Requirements
- Gentoo Linux
- `app-portage/gentoolkit` for `equery`
- Bash-compatible shell

## Installation
Use your favorite method for installing scripts.