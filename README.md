dotfiles
========

Store dotfiles for various applications to keep them in sync across my computers. Each dotfile tracked in dotfilesrc will have a symlink created in `$HOME`.

Project structure and dotsync based off of [dotphiles](https://github.com/dotphiles/dotphiles).

Installation
------------

Clone dotfiles into home directory:

    git clone --recursive git@github.com:hansmosh/dotfiles.git ~/.dotfiles

Then, symlink your dotfiles into place:

    ~/.dotfiles/dotsync/bin/dotsync -L
