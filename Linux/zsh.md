## Install

### Zsh Installation

```shell
sudo apt install zsh -y

# check for the installation
# there should be `/bin/zsh`
cat /etc/shells

# change default shell
# may need reboot
chsh -s /bin/zsh

# check the change result 
echo $SHELL
```

### Oh my zsh Installation

```shell
# for Chinese users
sh -c "$(curl -fsSL https://gitee.com/shmhlsy/oh-my-zsh-install.sh/raw/master/install.sh)"
```

## Configuration

in `~/.zshrc`

### Theme

```shell
ZSH_THEME="ys"
```

### Plugin

```shell
# zsh-autosuggestions and zsh-syntax-highlighting need extract installation
plugins=(git z extract zsh-autosuggestions zsh-syntax-highlighting)
```

### Others

```shell
ENABLE_CORRECTION="true"
COMPLETION_WAITING_DOTS="true"
```
