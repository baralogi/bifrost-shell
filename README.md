# I ❤️ ITerm2 + ZSH + PowerLevel10k

My wonderful setting for terminal with ITerm2, zsh, and powerlevel10k to increase productivity

![image](https://github.com/baralogi/bifrost-shell/assets/31835484/3b513812-feb6-4e1c-b63d-6fed5e23fd2f)

## Terminal

Use [Official ITerm2 Site](https://iterm2.com/)

## Shell

For my Shell, I use **ZSH** with **Oh-My-Zsh** for configure any plugins.

### Install Zsh

`brew install zsh`

`chsh -s /usr/local/bin/zsh`

`zsh --version`
   
### Install [Oh-My-Zsh](https://ohmyz.sh/)

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

U will see `.zhrc` file for setting any plugins. See `.zhrc` file to this repo. Copy and reload sheel.

`source ~/.zshrc`

Plugins : 
* `git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions`
* `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting`

### Install Powerlevel10k

`git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k`

author: [@baralogi](https://github.com/baralogi)


