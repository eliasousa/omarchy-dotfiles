# Omarchy Dotfiles

Personal configuration files for [Omarchy](https://omarchy.com) Linux desktop, managed with [GNU Stow](https://www.gnu.org/software/stow/).

## Packages

| Package | Description |
|---------|-------------|
| `zsh` | Zsh shell config (oh-my-zsh) |
| `hypr` | Hyprland window manager |
| `ghostty` | Ghostty terminal |
| `alacritty` | Alacritty terminal |
| `kitty` | Kitty terminal |
| `waybar` | Status bar |
| `walker` | Application launcher |
| `omarchy` | Omarchy hooks, extensions, themed templates, branding |

## Usage

```bash
# Clone
git clone git@github.com:eliasousa/omarchy-dotfiles.git ~/omarchy-dotfiles

# Stow all packages
cd ~/omarchy-dotfiles
stow zsh hypr ghostty alacritty kitty waybar walker omarchy

# Stow a single package
stow hypr

# Unstow a package
stow -D hypr
```
