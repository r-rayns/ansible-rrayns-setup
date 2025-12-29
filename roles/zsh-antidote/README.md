# zsh-antidote

Installs and configures Zsh shell with Antidote plugin manager and Starship prompt.

## What it installs

- **Zsh** - Z shell, set as default shell
- **Antidote** - Fast Zsh plugin manager (static loading)
- **Starship** - Cross-shell prompt (Tokyo-Night theme)
- **FiraCode Nerd Font** - Programming font with ligatures and icons

## Configuration

Creates the following files:
- `~/.zshrc` - Sources Antidote, initializes plugins, runs Starship
- `~/.zsh_plugins.txt` - Plugin declarations (Oh My Zsh lib, colored-man-pages, zsh-z, poetry completion)
- `~/.config/starship.toml` - Custom Tokyo-Night themed prompt config

## Plugins Included

- Oh My Zsh library and colored man pages
- `zsh-z` - Jump to frequent directories
- Poetry completion support

## Usage

```bash
ansible-playbook setup.yml --tags shell
```
