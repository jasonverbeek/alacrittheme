# Alacrittheme
theming tool writen in bash to easily swap between themes and fonts

## Installation
- Arch Linux

 Alacrittheme is available on the [AUR](https://wiki.archlinux.org/index.php/Arch_User_Repository)  using your prefered [AUR Helper](https://wiki.archlinux.org/index.php/AUR_helpers).

 `~ > paru -S alacrittheme` ([PARU](https://github.com/morganamilo/paru))

## Examples
Getting a list of available themes or fonts:

`~ > alacritty-theme`

`~ > alacritty-font`

Setting a different theme or font:

`~ > alacritty-theme gruvbox-dark`

`~ > alacritty-font firacode`

Restoring defaults:

`~ > alacritty-theme default`

`~ > alacritty-font default`

## Additional settings
Additional settings for alacritty can be set in `~/.config/alacritty/customize.yml`

customize.yml is appended to the bottom of the configuration, overwriting any config from themes/fonts
