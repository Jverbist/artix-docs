# Configuration of my Artix

## Software
- Vim
- lvim
- hexchat
- python 
- tailscale ->
git clone --depth=1 'https://github.com/void-linux/void-packages'
cp -R void-packages/srcpkgs/tailscale/files/tailscaled /etc/runit/sv
ln -s /etc/runit/sv/tailscaled /run/runit/service

## Change DPI for 4K screen

lvim ~/.xprofile =>  
xrandr --dpi 150		# Set DPI. User may want to use a larger number for larger screens.

## Change default browser

lvim ~/.local/src/dwm/config.h

**edit =>**

#define BROWSER "my_browser"

**save and exit**

sudo make install

**reboot**

## Join hexachat

/join #TheLounge


