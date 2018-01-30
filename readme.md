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
* Package manager message disabled (no fuck to give about update…).

# Don’t fork me, learn to backup your personal conf.

It’s easy to do. 
* You need to init a repo with your `~/.config/sublime-text-3` folder.
* Add this `.gitignore` file on the repo https://github.com/4sStylZ/SublimeText3/blob/master/.gitignore.
* **Be careful. Your license for commercial package will be on the web if you have paid for some of them and don’t ignore it with the file.**

https://forum.sublimetext.com/t/what-s-the-best-way-to-backup-the-st3-configuration/25494

# Preview

![prevew](http://i.imgur.com/LoT9tei.jpg)

# Installation

## Sublime

* Backup your configuration if you have sublime already installed : `cp ~/.config/sublime-text-3 ~/.config/sublime-text-3-oldconf`.
* Or install sublime by the official website.
* Install package controll via the website or via the command pallete « Install Package Control ».
* Clone the project in your config folder `git clone https://github.com/4sStylZ/SublimeText3.git ~/.config/sublime-text-3/Packages/User/`
* Start sublime and wait : The package control need to install all the packages.

## Optionnal : Fonts (optionnal, if you want ProFont).

### Profont IIX

The new Tobias JUNG Profont IIX seems to be the best for Linux.
Find them and install them in the folder `.config/sublime-text-3/Packages/User/Fonts/profontiix/`

Alternative : 

http://tobiasjung.name/downloadfile.php?file=profontiix.zip

### Old Profonts

* Extracts the `.fonts` archive on your home directory : `~/.config/.fonts`.
* CP `.fonts.conf` to your home : `~/.fonts.conf`. (Or concat the content at your file if you have already a `.fonts.conf`).
* Type `fc-cache -fv` on a terminal for force-reload the font cache.

## Optionnal : Hack and disable all the update message from package manager

* Open Resource via PackageResourceViewer -> Select Package Control (installed by default in this sublime conf).
* Select package_control/package_manager.py to edit.
* Comment out line self.print_messages(package_name, package_dir, is_upgrade, old_version, new_version) by putting a hash # in the front.
* Save file.
