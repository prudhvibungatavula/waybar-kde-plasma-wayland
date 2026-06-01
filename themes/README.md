# Themes

## Color Scheme
- Main.colors — primary color scheme used
- Install: copy to ~/.local/share/color-schemes/
- Apply: System Settings -> Colors & Themes -> Colors

## GTK Theme
- gtk-theme: Breeze
- icon-theme: Papirus-Dark
- cursor: capitaine-cursors-light
- font: JetBrains Mono Medium 11

## Install GTK theme
```bash
sudo pacman -S papirus-icon-theme
yay -S capitaine-cursors
```

## Apply settings
```bash
cp themes/gtk/gtk3-settings.ini ~/.config/gtk-3.0/settings.ini
cp themes/gtk/gtk4-settings.ini ~/.config/gtk-4.0/settings.ini
```

## Plasma Theme
- Sweet (install from KDE Store or `yay -S plasma5-themes-sweet-kde-git`)
