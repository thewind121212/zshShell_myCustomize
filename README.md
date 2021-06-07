# zshrc customize file .zshrc
## Installation
### Installation zsh
 *Fedora: 
#### `dnf install zsh`
*Arch:
#### `pacman -S zsh zsh-completions`
*SUSE: 
#### `zypper in zsh`
*Ubuntu: 
#### `apt install zsh`

### Installation Oh my zsh
run this command 
### `curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh; zsh`
after run this command make sure it log  .....is now installed! 

*If it don’t show you the message “Shell changed.” just before the Oh My ZSH logo, maybe the script wasn’t able to change your default shell. In that case, you can manually change it using 

### `sudo usermod --shell $(which zsh) <your_username>`


#### Install nerd font use like from this repo https://github.com/ryanoasis/nerd-fonts (recomend hack font best performace)

### Install powerlevel9k

#### `git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k`

### For the last step install my customize
*clone my repo 
#### `git clone https://github.com/thewind121212/zshShell_myCustomize.git`
* Copy all thing in my file to to .zshrc in "~/.zshrc"






