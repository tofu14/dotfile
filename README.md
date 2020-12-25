# simple for newbie

![image](img/screen.png)

## reference

click this file [URL](./url)

## Settings terminal for VSCode

Check font iTerm2

> Command + , -> terminal.integrated.fontFamily -> MesloLGS NF

## for vim

### install vim-plug

- curl -fLo ~/.vim/autoload/plug.vim --create-dirs <https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim>

### config

- cp .vimrc ~/.vimrc
- open vim -> :source ~/.vimrc -> :PlugInstall -> :PlugUpdate

### remove plugin

- Step 1: Delete or comment out Plug commands for the plugins you want to remove.
- Step 2: Reload vimrc (:source ~/.vimrc) or restart Vim
- Step 3: Run :PlugClean. It will detect and remove undeclared plugins.

## for zsh

### zsh

- Mac: brew install zsh zsh-completions
- Ubuntu: sudo apt install zsh

### oh-my-zsh

- sh -c "$(curl -fsSL <https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh>)"

### zsh-autosuggestions

- git clone <https://github.com/zsh-users/zsh-autosuggestions> ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

### zsh-syntax-highlighting

- git clone <https://github.com/zsh-users/zsh-syntax-highlighting.git> ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

### fzf

- git clone --depth 1 <https://github.com/junegunn/fzf.git> ~/.fzf && ~/.fzf/install

#### Remember to answer “y” to all questions

- Ctrl+T to search for files
- Ctrl+R to search for commands in your history

#### nerd fonts (optional)

- sudo mkdir -p ~/.fonts
- tar xzf image-master-font-gofont-ttfs.tar.gz && mv Go-* ~/.fonts/

#### theme Powerlevel10K

- git clone <https://github.com/romkatv/powerlevel10k.git> ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel10k
