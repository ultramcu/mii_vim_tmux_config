# mii_vim_tmux_config

##install application

###CentOS

sudo yum -y install tmux git vim tree zsh

###Ubuntu

sudo apt-get install tmux git vim tree zsh

### macOS

sudo port install tmux git vim tree zsh

##install oh-my-zsh

sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

##install my config

cd ~

git clone https://github.com/ultramcu/mii_vim_tmux_config.git

ln -s mii_vim_tmux_config/.tmux.conf ./

ln -s mii_vim_tmux_config/.vimrc ./

unzip mii_vim_tmux_config/vim.zip -d mii_vim_tmux_config/

mv mii_vim_tmux_config/vim mii_vim_tmux_config/.vim

ln -s mii_vim_tmux_config/.vim ./


--
##change zsh theme to pygmalion

vi ~/.zshrc

ZSH_THEME="pygmalion"

--

#Welcome to my colourful Terminal :)


