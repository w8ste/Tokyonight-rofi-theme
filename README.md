# Tokyonight-rofi-theme

```
Hey there, this is my Tokyonight rofi theme. Changes are to be expected :)
Consider leaving a star, so you will not miss any ⭐
```
### Versions

Default Version (normal icons and more text):
![Alt text](https://github.com/w8ste/screenshots/blob/main/rofi_full_2.png)

Big icons version 1 (bigger icons, one column):
![Alt text](https://github.com/w8ste/screenshots/blob/main/rofi_big_icons.png)

Big icons version 2 (bigger icons, two columns):
![Alt text](https://github.com/w8ste/screenshots/blob/main/rofi_big_icons_sinsingle.png)

### Prerequisites

My rofi setup requires you to have some kind of [Nerdfont](https://www.nerdfonts.com/) and [rofi](https://github.com/davatorium/rofi) installed. In case 
you would like my setup without having to install a nerdfont, just comment out lines 10-12 in my [config.rasi](https://github.com/w8ste/Tokyonight-rofi-theme/blob/main/config.rasi). 

### Installation

Run the following commands:

```
  rm -rf ~/.config/rofi
  git clone git@github.com:w8ste/Tokyonight-rofi-theme.git ~/.config/rofi
  sudo mv ~/.config/rofi/tokyonight.rasi /usr/share/rofi/themes
  sudo mv ~/.config/rofi/tokyonight_big1.rasi /usr/share/rofi/themes
  sudo mv ~/.config/rofi/tokyonight_big2.rasi /usr/share/rofi/themes
  rm ~/.config/rofi/README.md
```

Afterwards you can select the version, that you want via the rofi-theme-selector. In case you do not want all
of the versions: only `mv` the ones that you want into `/usr/share/rofi/themes` and `rm ~/.config/rofi/"version"`the other ones.
It may be possible that you need to reaload your .config files (e.g. $mod + shift + r for i3), even though
this never occured when i was testing.

![Alt text](https://github.com/w8ste/screenshots/blob/main/rofi_full.png)

### Alternative installation
In case you prefer to install just the theme without my configuration of rofi, you run the following commands:
```
  git clone git@github.com:w8ste/Tokyonight-rofi-theme.git ~/tokyonight
  sudo mv ~/tokyonight/tokyonight.rasi /usr/share/rofi/themes
  sudo mv ~/.config/rofi/tokyonight_big1.rasi /usr/share/rofi/themes
  sudo mv ~/.config/rofi/tokyonight_big2.rasi /usr/share/rofi/themes
  rm -rf ~/tokyonight
```

### Appendix
- This theme was inspired by the [tokyonight](https://github.com/folke/tokyonight.nvim) colorscheme for nvim by folke.
- If you like this rofi-theme please, consider becoming a stargazer :)
- Check out my [dotfiles](https://github.com/w8ste/dotfiles)
- and my [rofi-powermenu](https://github.com/w8ste/Rofi-Powermenu/tree/main)

### Contributing
- In case you have something to add to this colorscheme feel free to fork it and if you want to create a pull request. If i believe your changes improved
  the project i will merge them

![Alt text](https://github.com/w8ste/screenshots/blob/main/window_rofi.png)

### Reddit
This theme has been posted on reddit [here](https://www.reddit.com/r/unixporn/comments/15ybsjc/rofi_created_my_own_first_rofitheme_how_did_i_do/) and 
[here](https://www.reddit.com/r/unixporn/comments/15z3ob3/rofi_since_you_all_gave_my_feedback_how_do_you/). A big thanks to the unixporn community for their feedback, which 
helped me improve this theme :)
