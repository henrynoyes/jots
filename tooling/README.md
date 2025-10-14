# Useful development tools

> [!note]
> Many of these tools are written in Rust. Installing [cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html) is recommended for package management.

## CLI substitutes

#### [`ripgrep`](https://github.com/BurntSushi/ripgrep)

Description: A faster `grep` with better defaults and Git integration.

Installation: `cargo install ripgrep`

Usage: `rg "pattern" path/`

#### [`bat`](https://github.com/sharkdp/bat)

Description: A faster `cat` with synatx highlighting and Git integration.

Installation: `cargo install bat`

Usage: `bat filename`

#### [`dust`](https://github.com/bootandy/dust)

Description: A faster `du` with better defaults and tree visualization.

Installation: `cargo install du-dust`

Usage: `dust path/`

## [Pixi](https://pixi.sh/latest/)

A modern package manager built on `conda` that supports automatic lockfiles, native PyPI integration, and project management tools. Uses [uv](https://docs.astral.sh/uv/) under the hood for blazing PyPI solving.

To install run,
```
curl -fsSL https://pixi.sh/install.sh | sh
```

For Python-only projects, a standalone [uv](https://docs.astral.sh/uv/) configuration can also be sufficient.

## Terminal Config

Emulator - [Kitty](https://sw.kovidgoyal.net/kitty/)

Prompt - [Starship](https://starship.rs/)

Editor - [LazyVim](https://www.lazyvim.org/)

See [my dotfiles](https://github.com/henrynoyes/dotfiles) for more info

## Resources

[Oxidize Your Command Line | No Boilerplate](https://www.youtube.com/watch?v=rWMQ-g2QDsI)