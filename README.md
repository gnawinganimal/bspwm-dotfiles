# bspwm-dotfiles

My bspwm dotfiles that I use for my daily driver

### Overview
| Component         | Program |
| ----------------- | ------- |
| *desktop*         | bspwm   |
| *status bar*      | polybar |
| *launcher*        | rofi    |
| *notifications*   | dunst   |
| *terminal*        | kitty   |
| *file manager*    | ranger  |
| *document viewer* | zathura |

### Install

You can run the provided `install.sh` script to copy all provided files into the `.config` and `.fonts` directories. Make sure to call `fc-cache` to load the fonts.

You can install all necessary components with the following command, or you may install them individually:
```bash
yay -S bspwm sxhkd polybar rofi dunst kitty fish ranger zathura cava  
```
