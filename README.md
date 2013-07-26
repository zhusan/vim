Install
1. clone the repo

        git clone https://github.com/zhusan/vim.git

1. rename it

        mv vim ~/.vim

1. set up `~/.vimrc`, have a fake `.vimrc` in your `$HOME`

        ln -s ~/.vim/vimrc ~/.vimrc

1. you also need to install `Ctags`, `ack-grep`

        sudo apt-get install exuberant-ctags ack-grep # for ubuntu
