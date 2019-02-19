# vim-config
## Installation ##
    #install vim8
    mkdir -p ~/.local/ && \
    mkdir -p ~/local && \
    cd ~/local/ && \
    git clone https://github.com/vim/vim.git && \
    cd vim/src && \
    ./configure --prefix=$HOME/.local && make && make install && \
    #install gruvbox
    git clone https://github.com/morhetz/gruvbox.git ~/.vim/pack/default/start/gruvbox && \
    echo "colorscheme gruvbox" >> ~/.vimrc && \
    echo "set background=dark" >> ~/.vimrc && \
    echo "export TERM=xterm-256color" >> ~/.bashrc
