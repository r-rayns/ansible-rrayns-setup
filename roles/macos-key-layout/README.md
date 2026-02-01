# macos-key-layout

Configures MacOS UK keyboard layout behavior on Linux using keyd.

## Features

- Command key acts like Ctrl (Cmd+C → Ctrl+C)
- Shift+2 → @ (Mac UK style)
- Shift+' → " (Mac UK style)
- Option+3 → #
- Option+2 → €

## Dependencies

Installs keyd from source (https://github.com/rvaiya/keyd)

## Adding More Mappings

Edit `/etc/keyd/default.conf` and restart:

```bash
sudo systemctl restart keyd
```

Common additions:
- `[mac_option]` section: Add more Option+key → character mappings
- `[shift]` section: Add more shifted key swaps
