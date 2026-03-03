# KittyConfig

A clean, customizable configuration for the Kitty terminal.

## ⚡ Requirements

* Kitty terminal (latest version recommended)
* Nerd Font (CodeNewRoman Nerd Font)
* macOS, Linux, or BSD

## 🚀 Getting Started

> **Note:** Backup your existing Kitty configuration before installing.

Kitty configuration path:

| OS          | PATH              |
| :---------- | :---------------- |
| Linux/macOS | `~/.config/kitty` |

### Install

```bash
# Backup existing config (if any)
mv ~/.config/kitty ~/.config/kitty.bak

# Clone KittyConfig repo
git clone https://github.com/LuckiBit/kitty.git ~/.config/kitty

# Or manually copy your config files
cp my.conf ~/.config/kitty/
cp kitty.conf ~/.config/kitty/
```

### Reload Configuration

* After editing `kitty.conf` or included files, press:

```
Ctrl + Shift + F5
```

## ❌ Uninstalling

```bash
rm -rf ~/.config/kitty
```

* Deletes all Kitty configuration added by this setup

## 📂 File Structure

```
~/.config/kitty
├── kitty.conf       # Main configuration
└── my.conf          # Custom included settings
```

