# languages

Interactive installation of programming language runtimes and package managers.

## Available Languages/Tools

### Go (v1.24.3)
- Downloads and installs to `/usr/local/go`
- Adds `GOROOT` and PATH entries to `~/.zshenv`
- Includes SHA256 checksum verification

### NVM (Node Version Manager)
- Fetches latest version from GitHub API
- Installs to `~/.nvm`
- Adds initialization to `~/.zshrc`

### Python Poetry
- Python dependency management tool
- Installs to `~/.local/bin`
- Adds PATH entry to `~/.zshrc` (before Starship init)

## Interactive Prompts

Each tool has an individual prompt - answer "yes" to install, "no" to skip.

## Dependencies

Requires `zsh-antidote` role to run first (modifies Zsh config files).

## Usage

```bash
ansible-playbook setup.yml --tags langs
```
