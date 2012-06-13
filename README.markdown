 Evan M. Sanders : Custom Vim Config

 Alterações feitas por

#Diego Andrade

## Lista de Plugins

1. Solarized
2. SuperTab
3. closeTag
4. delimitMate
5. NERDTree
6. Mini Buf Explorer
7. TagBar
8. Surround
9. CSSColor

## Instalação

1. cd ~
2. git clone git@github.com:didijudo/dotvim.git ~/.vim
ou git clone http://github.com/didijudo/dotvim.git ~/.vim
3. ln -s ~/.vim/vimrc ~/.vimrc
4. cd ~/.vim
5. git submodule init
6. git submodule update

## Atualizando Plugins recursivamente

1. cd ~/.vim
2. git submodule foreach git pull origin master
