# dotfiles

## PowerLine
### Instalar no Fedora Linux:

```
sudo dnf install powerline powerline-fonts

mkdir /usr/local/bin/powerline

git clone https://github.com/powerline/powerline.git /usr/local/bin/powerline/

wget https://github.com/powerline/powerline/raw/develop/font/PowerlineSymbols.otf -O /usr/share/fonts/PowerlineSymbols.otf
sudo wget https://github.com/powerline/powerline/raw/develop/font/10-powerline-symbols.conf -O /etc/fonts/conf.d/10-powerline-symbols.conf
echo '. /usr/local/bin/powerline/powerline/bindings/bash/powerline.sh' >> ~/.bashrc

```
