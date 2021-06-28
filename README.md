# The Voidrice

This is a fork of Luke Smith <https://lukesmith.xyz>'s dotfiles.

The dotfiles here are based on the dotfiles deployed by [LARBS](https://larbs.xyz) and as seen on [Luke's YouTube channel](https://youtube.com/c/lukesmithxyz).

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
    - sxhkd (general key binder)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- sxiv (image/gif viewer)
	- mpv (video player)
    - tmux
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

- [dwm](https://github.com/lukesmithxyz/dwm) (window manager)
- [dwmblocks](https://github.com/lukesmithxyz/dwmblocks) (statusbar)
- [st](https://github.com/lukesmithxyz/st) (terminal emulator)

I also recommend trying out
[mutt-wizard](https://github.com/lukesmithxyz/mutt-wizard), which additionally
works with this setup. It gives you an easy-to-install terminal-based email
client regardless of your email provider. It is integrated into these dotfiles
as well.

## Install these dotfiles and all dependencies

Use [my fork](https://github.com/theblackfly/LARBS) of [LARBS](https://larbs.xyz) to autoinstall everything:

```sh
curl -LO https://github.com/theblackfly/LARBS/blob/blackfly/larbs.sh
sudo sh larbs.sh
```

or clone the repo files directly to your home directory and install [the prerequisite programs](https://github.com/theblackfly/LARBS/blob/blackfly/progs.csv).

## Do you want to customize the dotfiles further and version control it with git?

1. Fork this repository.
2. Create a new branch and make your changes there.
