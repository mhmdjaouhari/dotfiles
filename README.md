# dotfiles

These are the dotfiles deployed by [LARBS](https://github.com/LukeSmithxyz/larbs) based on Luke Smith's dotfiles ([voidrice](https://github.com/LukeSmithxyz/voidrice)).

> - Very useful scripts are in `~/.local/bin/`
> - Settings for:
> 	- vim/nvim (text editor)
> 	- zsh (shell)
> 	- lf (file manager)
> 	- mpd/ncmpcpp (music)
> 	- sxiv (image/gif viewer)
> 	- mpv (video player)
> 	- other stuff like xdg default programs, inputrc and more, etc.
> - I try to minimize what's directly in `~` so:
> 	- All configs that can be in `~/.config/` are.
> 	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
> - Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
> 	- File bookmarks in `~/.config/shell/bm-files`
> 	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

- [dwm](https://github.com/mojaouhari/dwm) (window manager) - *[fork public](https://github.com/mojaouhari/dwm)*
- [dmenu](https://github.com/lukesmithxyz/dmenu) (menu for dwm) - *fork private*
- [dwmblocks](https://github.com/lukesmithxyz/dwmblocks) (statusbar) - *fork private*
- [st](https://github.com/lukesmithxyz/st) (terminal emulator) - *fork private*

## Install these dotfiles and all dependencies

Use [LARBS](https://larbs.xyz) to autoinstall everything:

```
curl -LO larbs.xyz/larbs.sh
sh larbs.sh -r git@github.com:mojaouhari/dotfiles.git -p https://raw.githubusercontent.com/mojaouhari/dotfiles/master/.local/progs.csv
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/mojaouhari/dotfiles/blob/master/.local/progs.csv).
