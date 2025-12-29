# software-common-gui

Interactive installation of GUI applications. Prompts for each app individually or option to install all.

## Available Applications

- **Kitty Terminal** - GPU-accelerated terminal emulator (via custom installer)
- **Chromium** - Open-source web browser (via apt)
- **KeePassXC** - Password manager (via flatpak)
- **Kdenlive** - Video editor (via apt)
- **GIMP** - Image editor (via apt)
- **Peek** - Screen recorder (via apt)
- **Yakuake** - Drop-down terminal (via apt)
- **Visual Studio Code** - Code editor (via Microsoft repository)

## Interactive Prompts

First prompt asks "Install all optionals?" - answer yes to skip individual prompts.

If no, you'll be asked about each application individually.

## Usage

```bash
ansible-playbook setup.yml --tags gui
```
