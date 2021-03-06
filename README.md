# powerline
## Linux
```console
git clone https://github.com/powerline/fonts.git
pip install git+git://github.com/powerline/powerline
```
## Ubuntu 16.04
```console
sudo apt install powerline fonts-powerline
```
## OpenSUSE
```console
zypper in zsh
cd /tmp
git clone git://github.com/altercation/solarized.git
cd $HOME
git clone https://github.com/rupa/z.git .z
```
Put something like this in your $HOME/.bashrc or $HOME/.zshrc:
```console
. $HOME/.z/z.sh
```

```console
gem install tmuxinator
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
cd /tmp
git clone https://github.com/powerline/fonts.git
cd fonts
./install.sh
pip install git+git://github.com/powerline/powerline
pip3 install git+git://github.com/powerline/powerline
vim ~/.zshrc
```
Change plugin value to

```console
plugins=(colorize common-aliases djagon git github gnu-utils history nmap tmux rsync)

export EDITOR='vim'

ZSH_THEME="agnoster"
```

## Fonts
```console
http://media.nodnod.net/Inconsolata-dz.otf.zip
```

## URL
http://www.tecmint.com/powerline-adds-powerful-statuslines-and-prompts-to-vim-and-bash/
