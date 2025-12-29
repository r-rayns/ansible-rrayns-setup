# software-common-non-gui

Installs essential CLI development tools and configures Tmux.

## What it installs

- **Editors/Tools**: vim, tmux, curl, btop
- **Build tools**: gcc, build-essential
- **Python dev**: python3-venv, python3-pip
- **Utilities**: aspell (spell checker), wordnet (dictionary)

## Tmux Setup

- Clones Tmux Plugin Manager (TPM)
- Creates `~/.tmux.conf` with sensible defaults and plugins:
  - `tmux-sensible` - sensible default settings
  - `tmux-resurrect` - save/restore tmux sessions

**Post-install**: Open tmux and press `prefix + I` to install plugins (default prefix is `Ctrl+b`).

## Usage

```bash
ansible-playbook setup.yml --tags non-gui
```
