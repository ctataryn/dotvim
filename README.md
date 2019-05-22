Craig Tataryn's <craiger@tataryn.net> ~/.vim directory

To run on a fresh install:

`git clone git@github.com:ctataryn/dotvim.git ~/.vim`
** On Linux:
*** ln -s ~/dotvim ~/.vimrc
*** ln -s ~/dotvim ~/.vim
** On Windows (make sure to run cmd.exe as Adminstrator):
*** mklink \Users\<userid>\.vimrc \Users\<userid>\.vim\dotvimrc
*** Rename dotvim folder to .vim (sym links under windows won't work with vundle)
`git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`
# Launch GVim
`:PluginInstall`
Wait until all plugins are installed
