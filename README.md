# dotfiles

My personal configuration files for Omarchy Arch/Hyprland. Clean, minimal, and functional.

<img width="1919" height="1079" alt="screenshot-2025-12-06_13-09-25" src="https://github.com/user-attachments/assets/cbedf73d-d23c-4835-9115-83c0623cdbdf" />

## Installation

Clone the repository:

```bash
git clone https://github.com/jcnghm/dotfiles.git
cd ~/dotfiles
```

### Waybar

```bash
ln -sf ~/dotfiles/waybar/config.jsonc ~/.config/waybar/config.jsonc
ln -sf ~/dotfiles/waybar/style.css ~/.config/waybar/style.css
```

Reload Waybar:

```bash
omarchy-toggle-waybar
```


## Notes

Individual files are symlinked rather than the entire config directories. This allows for machine-specific configurations to coexist with version-controlled files.
