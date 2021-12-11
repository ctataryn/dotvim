Craig Tataryn's <craiger@tataryn.net> ~/.vim directory

To run on a fresh install:

```
cd ~
git clone git@github.com:ctataryn/dotvim.git
```

## Install .vim files
* On Linux/Mac:
   * `ln -s ~/dotvim/dotvimrc ~/.vimrc`
   * `ln -s ~/dotvim ~/.vim`
* On Windows (make sure to run cmd.exe **as Adminstrator**):
   * `mklink \Users\<userid>\.vimrc \Users\<userid>\.vim\dotvimrc`
   * Rename dotvim folder to .vim (sym links under windows won't work with vundle)

## Install Vundle
   * `git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

## Launch GVim
type: `:PluginInstall`

Wait until all plugins are installed
