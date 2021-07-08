Make sure SSH key is configured for GitHub

Installation:

    git clone https://github.com/knightjdr/dotvim.git ~/.vim

Create symlinks:

    ln -s ~/.vim/.vimrc ~/.vimrc
    ln -s ~/.vim/.gvimrc ~/.gvimrc

Switch to the `~/.vim` directory, and fetch submodules:

    cd ~/.vim
    git submodule init
    git submodule update
