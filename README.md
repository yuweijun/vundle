# install vim plugins under vim8

    $ mkdir -p ~/.vim/pack/plugins
    $ cd ~/.vim/pack/plugins
    $ git clone https://github.com/yuweijun/vundle.git start
    $ cd start
    $ git submodule update --init --recursive

# install vim plugins under neovim

    $ mkdir -p ~/.local/share/nvim/site/pack/plugins
    $ cd ~/.local/share/nvim/site/pack/plugins
    $ git clone https://github.com/yuweijun/vundle.git start
    $ cd start
    $ git submodule update --init --recursive

# more infomation about packadd in vim8 and neovim

    :h packages
    :h packadd
