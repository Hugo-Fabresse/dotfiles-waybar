# dotfiles-waybar

Waybar configuration.
Black bar, white text, nerd font icons.

---

## Stack

- **Bar** : Waybar
- **Font** : Maple Mono NF

---

## Dependencies

```bash
sudo pacman -S waybar
yay -S maplemono-otf
```

---

## Install

```bash
git clone git@github.com:Hugo-Fabresse/dotfiles-waybar.git ~/dotfiles/waybar
ln -s ~/dotfiles/waybar ~/.config/waybar
```

Launch :

```bash
waybar -c ~/.config/waybar/config -s ~/.config/waybar/style.css &
```

---

## Modules

| Position | Module |
|----------|--------|
| Left | Hyprland workspaces |
| Center | Clock (click to open calendar) |
| Right | Audio, Battery, Network |

---

## Content

```
waybar/
├── config
└── style.css
```
