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

##config zsh

vi ~/.zshrc

###change zsh theme to pygmalion

ZSH_THEME="pygmalion"

###Export Path

export PATH=/sbin:/bin:/usr/sbin:/usr/bin:$PATH

###if has perl: warngin: Setting locale failed.

export LANGUAGE=en_US.UTF-8

export LC_ALL=en_US.UTF-8

export LANG=en_US.UTF-8

export LC_TYPE=en_US.UTF-8




--

##Change Default Shell

chsh -s /bin/zsh


--

#Enjoy it :)


