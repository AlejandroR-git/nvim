# nvim
1. Clone this repository into this directory: ~/.config
2. Clone vimPlug repository using this commandline: 
    -> sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
3. Install Node 12 using this commands: 
    -> sudo apt update
    -> sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates
    -> curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
    -> sudo apt -y install nodejs
