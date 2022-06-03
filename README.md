# plymouth-simplewallpaper

A simple [plymouth][https://wiki.archlinux.org/title/Plymouth] theme that just
shows a fullscreen image.

## How to use

1. `sudo cp -r simplewallpaper /usr/share/plymouth/themes/`
2. Copy a `wallpaper.png` of your choice into `/usr/share/plymouth/themes/simplewallpaper`
3. `sudo plymouth-set-default-theme -R simplewallpaper`
