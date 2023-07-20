# Tokyonight-rofi-theme

![Alt text](https://github.com/w8ste/screenshots/blob/main/rofi_full_2.png)

### Prerequisites

My rofi setup requires you to have some kind of [Nerdfont](https://www.nerdfonts.com/) and [rofi](https://github.com/davatorium/rofi) installed. In case 
you would like my setup without having to install a nerdfont, just comment out lines 10-12 in my [config.rasi](https://github.com/w8ste/Tokyonight-rofi-theme/blob/main/config.rasi).

### Installation

Run the following commands:

```
  rm -rf ~/.config/rofi
  git clone git@github.com:w8ste/Tokyonight-rofi-theme.git ~/.config/rofi
  mv ~/.config/rofi/tokyonight.rasi /usr/share/rofi/themes
  rm ~/.config/rofi/README.md
```

It may be possible that you need to reaload your .config files (e.g. $mod + shift + r for i3), even though
this never occured when i was testing.

![Alt text](https://github.com/w8ste/screenshots/blob/main/rofi_full.png)

### Appendix
- This theme was inspired by the [tokyonight](https://github.com/folke/tokyonight.nvim) colorscheme for nvim by folke.

### Contributing
- In case you have something to add to this colorscheme feel free to fork it and if you want to create a pull request. If i believe your changes improved
  the project i will merge them

![Alt text](https://github.com/w8ste/screenshots/blob/main/window_rofi.png)
