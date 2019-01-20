# Learn Vim

# Why?

So you can have street cred. Duh! Why _`else`_?
(_you don't **really** want to get your work done faster, do you?_)


# What? 

The text editor you can use _anywhere_. 


# How?

## Installation

### Mac

```
brew install macvim
```

## Linux/Unix

see: https://www.vim.org/git.php
(_most Linux already have Vim, check your distro_)


### Windows? 

GOTO: https://www.vim.org/download.php

## Vundle Plugin Manager


First:
```
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
Then add the following to your `.vimrc` file:

```
set nocompatible              " be iMproved, required by Vundle
filetype off                  " required

" set the runtime path to include Vundle and initialize
set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()

" These are two plugins that will be installed/managed by Vundle:
Plugin 'slashmili/alchemist.vim'
Plugin 'scrooloose/nerdtree'

" All of Plugins must be added before the following line
call vundle#end()            " required
```

Finally restart Vim and run the following command: `:PluginInstall`

When you edit a `README.md` you should see something like this:

![Vim-showing-nerdtree](https://user-images.githubusercontent.com/194400/51445633-7bc11380-1cff-11e9-92c8-010ea17249dd.png)


<!-- temp comment out 
installation
====
A barbones install script is include that assumes this repo is cloned at ~/vim.
-->
