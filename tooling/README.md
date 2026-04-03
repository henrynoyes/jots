# Useful development tools

> [!note]
> Many of these tools are written in Rust. Installing [cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html)/[cargo-binstall](https://github.com/cargo-bins/cargo-binstall) is recommended for package management.

## CLI

#### [`fzf`](https://github.com/junegunn/fzf)

Description: A fuzzy finder for command history, files, and processes.

Installation: `[brew|sudo apt] install fzf`

Usage: `fzf path/`

#### [`ripgrep`](https://github.com/BurntSushi/ripgrep)

Description: A faster `grep` with better defaults and Git integration.

Installation: `cargo binstall ripgrep`

Usage: `rg "pattern" path/`

#### [`bat`](https://github.com/sharkdp/bat)

Description: A faster `cat` with syntax highlighting and Git integration.

Installation: `cargo binstall bat`

Usage: `bat filename`

#### [`dust`](https://github.com/bootandy/dust)

Description: A faster `du` with better defaults and tree visualization.

Installation: `cargo binstall du-dust`

Usage: `dust path/`

#### [`meread`](https://github.com/sermuns/MEREAD)

Description: Locally preview GitHub Flavored Markdown files

Installation: `cargo binstall meread`

Usage: `meread README.md`

#### [`glimpse`](https://github.com/seatedro/glimpse)

Description: Easily build LLM context on the clipboard

Installation: `cargo install glimpse`

Usage: `glimpse path/`

## [Pixi](https://pixi.sh/latest/)

A modern package manager built on `conda` that supports automatic lockfiles, native PyPI integration, and project management tools. Uses [uv](https://docs.astral.sh/uv/) under the hood for blazing PyPI solving.

To install run,
```shell
curl -fsSL https://pixi.sh/install.sh | sh
```

For Python-only projects, a standalone [uv](https://docs.astral.sh/uv/) configuration can also be sufficient.

## [Ruff](https://docs.astral.sh/ruff/)

A modern Python linter and formatter. Written by the [Astral](https://astral.sh/) team, so has first-party integration with [uv](https://docs.astral.sh/uv/),
```shell
uv add --dev ruff
```

Can act as a drop-in replacement for [Black](https://docs.astral.sh/ruff/faq/#how-does-ruffs-formatter-compare-to-black) and [Flake8](https://docs.astral.sh/ruff/faq/#how-does-ruffs-linter-compare-to-flake8). Easily configurable as a [pre-commit](https://docs.astral.sh/ruff/integrations/#pre-commit) or [action](https://docs.astral.sh/ruff/integrations/#github-actions).

## [NetBird](https://netbird.io/)

A Zero Trust Networking platform for simple and secure remote access. Uses [WireGuard](https://github.com/wireguard) under the hood. Basically FOSS Tailscale.

To install run,
```shell
curl -fsSL https://pkgs.netbird.io/install.sh | sh
```

The free tier allows up to 5 users and 100 machines. [This](https://netbird.io/knowledge-hub/using-ssh-to-secure-remote-access) is a good guide to set up remote SSH.

## [zmx](https://zmx.sh/)

Simple and lightweight session persistence. The attach/detach functionality from `tmux` without the window management.

Install via `brew install neurosnap/tap/zmx` or the [pre-compiled binaries](https://github.com/neurosnap/zmx?tab=readme-ov-file#binaries).

## Terminal Config

Emulator - [Kitty](https://sw.kovidgoyal.net/kitty/)

Prompt - [Starship](https://starship.rs/)

Editor - [LazyVim](https://www.lazyvim.org/)

See [my dotfiles](https://github.com/henrynoyes/dotfiles) for more info

## Resources

[Oxidize Your Command Line | No Boilerplate](https://www.youtube.com/watch?v=rWMQ-g2QDsI)

[Modern Linux Tools | ikrima.dev](https://ikrima.dev/dev-notes/linux/linux-modern-tools/)