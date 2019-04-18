# How to install(mac)

* 1st step

```
brew update
brew install vim python cmake go mono node rust
```

* 2nd step

copy .vimrc

* 3rd step

install plugin

```
cd ~/
vim +PlugInstall +qall
cd .vim/plugged/YouCompleteMe/
python2.7 ./install.py --all
```

fin!!
