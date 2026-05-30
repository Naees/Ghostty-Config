# Setting up my personal Ghostty Configs 🫐

A curated repository containing optimized, aesthetic, and syntax-perfect configuration files for the **Ghostty** terminal emulator. Optimized for both **Linux** and **macOS** environments.

## Features

- **Theme:** Balanced Banana Blueberry palette with a `0.85` blurred translucent background.
- **Typography:** Tailored for *JetBrains Mono Nerd Font* with full ligature support (`->`, `!=`) and enhanced bold weight for readability.
- **Window Layout:** Borderless (`window-decoration = false`) with ideal 12px inner text padding.
- **Custom Splits:** Seamless arrow-key panel window splitting and navigation layout.

## Custom Keybindings for both Linux & Mac

### Linux Configuration (`ctrl`)
- `Ctrl + R`: Reload terminal configuration instantly
- `Ctrl + Up / Down / Left / Right`: Spawn a new pane split in that specific direction
- `Ctrl + Shift + Up / Down / Left / Right`: Move your active cursor focus between splits

### macOS Configuration (`super`)
- `Cmd + R`: Reload terminal configuration instantly
- `Cmd + Up / Down / Left / Right`: Spawn a new pane split in that specific direction
- `Cmd + Shift + Up / Down / Left / Right`: Move your active cursor focus between splits

## Installation

1. Clone this repository or copy the file matching your OS.
```bash
mkdir -p ~/.config/ghostty && cp ./config.ghosttylinux ~/.config/ghostty/config
```
#### OR
```bash
mkdir -p ~/.config/ghostty && cp ./config.ghosttymac ~/.config/ghostty/config
```
2. Open or reload Ghostty using `Ctrl + Shift + ,` (Linux) or `Cmd + Shift + ,` (macOS).

