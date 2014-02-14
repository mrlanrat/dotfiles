dotfiles
========

A place to store my configuration files.

USAGE: Run `./link.sh <module to link>`

All
--------

Configures all 


Vim
--------

Automagically configures vim with the following plugins:

1. https://github.com/tpope/vim-pathogen.git vim/bundle/vim-pathogen
2. https://github.com/scrooloose/nerdtree.git vim/bundle/nerdtree
3. https://github.com/Townk/vim-autoclose.git vim/bundle/autoclose
4. https://github.com/Lokaltog/vim-powerline.git vim/bundle/vim-powerline
5. https://github.com/tpope/vim-fugitive.git vim/bundle/vim-fugitive
6. https://github.com/majutsushi/tagbar.git vim/bundle/tagbar
7. https://github.com/msanders/snipmate.vim.git vim/bundle/snipmate
8. https://github.com/nanotech/jellybeans.vim.git vim/bundle/jellybeans

TODO for OSX:
    1. Download, compile, and install MacVim if it's not already installed!


Shell
--------

Configures the bash shell.

Replaces the ~/.bashrc and ~/.bash_profile with the profiles here.

Changes for all unix systems:

   1. A fancy prompt
   2. Some aliases
   3. bash_profile updates the path, and sources bashrc
   4. Adds functions that make your life easier:
   
        * extract $1 #Extract things. No more remember ugly tar crap!
        * scour $1 #Where the hell is it? 

Changes for OSX:
   1. Shell colors (yay!)
   2. vi opens the edit script. Link the scripts if you want this.


Scripts
--------

Links commonly used scripts to ~/bin/

Scripts linked for all unix systems:

Scripts linked for OSX:

    1. edit    -   Just opens MacVim


Terminator
--------


Conky
--------
