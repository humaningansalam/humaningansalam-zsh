# humaningansalam-zsh


### NEED

zsh install
```bash
sudo apt install zsh

sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

plugin install
```bash
# zsh-syntax-highlighting
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

# zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

# fzf (Fuzzy Finder )
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install

# alias-tips
git clone https://github.com/djui/alias-tips.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/alias-tips

# batcat
sudo apt install bat
git clone https://github.com/fdellwing/zsh-bat.git  ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-bat

# autojump
git clone https://github.com/wting/autojump.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/autojump
cd ${ZSH_CUSTOM:-$ZSH/custom}/plugins/autojump
./install.sh
```
