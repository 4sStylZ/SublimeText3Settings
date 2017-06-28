# Why this conf ?

It’s a personal conf optimized for my use, and I am a Bépo user (not a Qwerty-one) so don’t expect good qwerty keybindings.

* Use profont (awesome developper font).
* Power-user oriented -> Moar shortcut!
* Cool theme with picto.
* Php / JavaScript oriented.
  * Cool package.
  * Snippets.
  * Linters.
* Markdown Editing optimized.
* Custom theme.

# Preview

![prevew](http://i.imgur.com/LoT9tei.jpg)

# Installation

## Sublime

* Backup your configuration if you have sublime already installed : `cp ~/.config/sublime-text-3 ~/.config/sublime-text-3-oldconf`.
* Or install sublime by the official website.
* Install package controll via the website or via the command pallete « Install Package Control ».
* Clone the project in your config folder `git clone https://github.com/4sStylZ/SublimeText3.git ~/.config/sublime-text-3/Packages/User/`
* Start sublime and wait : The package control need to install all the packages.

## Fonts (optionnal, if you want ProFont).

* Extracts the `.fonts` archive on your home directory : `~/.config/.fonts`.
* CP `.fonts.conf` to your home : `~/.fonts.conf`. (Or concat the content at your file if you have already a `.fonts.conf`).
* Type `fc-cache -fv` on a terminal for force-reload the font cache.
