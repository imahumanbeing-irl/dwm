# my dwm

## installation

NOTE: this assumes you dont a have a display manager, if you do, uninstall that bloat

```
yay -S nerd-fonts-fira-code
git clone https://github.com/imahumanbeing-irl/dwm
cd dwm
mv .fonts.conf ~
sudo mv status /usr/bin/
cd ..
git clone https://github.com/Earnestly/sx
cd sx
make PREFIX=/usr install
cd ../dwm
mv sxrc ~/.config/
sudo make install
```
