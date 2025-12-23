# Applied Patches
* [attachbottom](https://dwm.suckless.org/patches/attachbottom/): master remains on the left and isn't replaced by slaves
* [fullgaps](https://dwm.suckless.org/patches/fullgaps/): adds useless gaps between windows
* [fullscreen](https://dwm.suckless.org/patches/actualfullscreen/): true fullscreen
* [hide vacant](https://dwm.suckless.org/patches/hide_vacant_tags/): hides tags not currently in use
* [selfrestart](https://dwm.suckless.org/patches/selfrestart/): removes the need of a unecessary dwm loop script to restart dwm
* [statuscmd](https://dwm.suckless.org/patches/statuscmd/): needed for a clickable dwmblocks or status monitor
* [swallow](https://dwm.suckless.org/patches/swallow/): gui applications take the place of terminals they were invoked from
* [pertag](https://dwm.suckless.org/patches/pertag/): for a layout per tag

# Installation instructions
```shell
git clone https://github.com/anuranjangyawali/dwm
cd dwm
make
make install
```

# Dependency
I use pywal for colorscheme generation. Make sure you generate a colorscheme and include your colors-wal-dwm.h path in config.h before installing.


