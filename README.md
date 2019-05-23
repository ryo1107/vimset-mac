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


# Linux

* any

```
yum install cmake go
```

* node

```
curl -sL https://rpm.nodesource.com/setup_10.x | bash -
yum install -y nodejs
```

* rust

```
curl https://sh.rustup.rs -sSf | sh
source $HOME/.cargo/env
```


```
mkdir .vim
cd .vim
mkdir autoload
cd autoload
curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
cd
vim +PlugInstall +qall
cd .vim/plugged/YouCompleteMe/
python2.7 ./install.py --all
```
