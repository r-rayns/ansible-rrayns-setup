# keychron-k2

Configures Keychron K2 keyboard with the correct key mappings and to use function keys (F1-F12) by default instead of media keys.

## What it does

Sets `fnmode=2` for the HID Apple keyboard driver, which makes:
- **Default behavior**: F1-F12 function keys
- **With Fn key pressed**: Media keys (brightness, volume, etc.)

Updates initramfs to apply changes on next boot.

**Note**: Requires a reboot to take effect.

## Usage

```bash
ansible-playbook setup.yml --tags keyboard
```
