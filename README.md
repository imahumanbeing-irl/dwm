# my dwm

## installation

NOTE: this assumes you dont a have a display manager, if you do, uninstall that bloat

```
yay -S nerd-fonts-fira-code
git clone https://github.com/imahumanbeing-irl/dwm
cd dwm
mv .fonts.conf ~
cd ..
git clone https://github.com/Earnestly/sx
cd sx
make PREFIX=/usr install
cd ../dwm
mv sxrc ~/.config/
sudo make install
```
edit ~/.config/sx/sxrc make status bar script autostart (optional)
