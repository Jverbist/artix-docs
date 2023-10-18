# Configuration of my Artix

## Software
- Vim
- lvim
- python 



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

