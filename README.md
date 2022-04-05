# `foundry justfile example`


## Overview

> `just` is the new `make`

- load `.env` via `justfile`
- run tests
- can even execute nodejs/python/etc scripts via `justfile`


## Example

```shell
$ just
just --list
Available recipes:
    build                     # build using forge
    test                      # default test scripts
    test-local *commands=""
    test-mainnet *commands="" # run mainnet fork forge tests (all files with the extension .debug.sol)
```


### Justfile Install

| Operating System                                     | Package Manager           | Package                                          | Command                                                                                 |
| ---------------------------------------------------- | ------------------------- | ------------------------------------------------ | --------------------------------------------------------------------------------------- |
| [Various][rust-platforms]                            | [Cargo][cargo]            | [just][just-crate]                               | `cargo install just`                                                                    |
| [Microsoft Windows][windows]                         | [Scoop][scoop]            | [just][just-scoop]                               | `scoop install just`                                                                    |
| [Various][homebrew-install]                          | [Homebrew][homebrew]      | [just][just-homebrew]                            | `brew install just`                                                                     |
| [macOS][macos]                                       | [MacPorts][macports]      | [just][just-macports]                            | `port install just`                                                                     |
| [Arch Linux][arch linux]                             | [pacman][pacman]          | [just][just-pacman]                              | `pacman -S just`                                                                        |
| [NixOS][nixos], [Linux][nix-plat], [macOS][nix-plat] | [Nix][nix]                | [just][just-nixpkg]                              | `nix-env -iA nixos.just`                                                                |
| [Solus][solus]                                       | [eopkg][solus-eopkg]      | [just][just-solus]                               | `eopkg install just`                                                                    |
| [Void Linux][void linux]                             | [XBPS][xbps]              | [just][just-void]                                | `xbps-install -S just`                                                                  |
| [FreeBSD][freebsd]                                   | [pkg][freebsd-pkg]        | [just][just-freebsd]                             | `pkg install just`                                                                      |
| [Alpine Linux][alpine linux]                         | [apk-tools][apk-tools]    | [just][just-alpine]                              | `apk add just`                                                                          |
| [Fedora Linux][fedora linux]                         | [DNF][dnf]                | [just][just-fedora]                              | `dnf install just`                                                                      |
| [Gentoo Linux][gentoo linux]                         | [Portage][gentoo-portage] | [dm9pZCAq overlay: sys-devel/just][just-portage] | `eselect repository enable dm9pZCAq && emerge --sync dm9pZCAq && emerge sys-devel/just` |
| [Various][conda-platforms]                           | [Conda][conda]            | [just][just-conda]                               | `conda install -c conda-forge just`                                                     |
| [Microsoft Windows][windows]                         | [Chocolatey][chocolatey]  | [just][just-chocolatey]                          | `choco install just`                                                                    |
