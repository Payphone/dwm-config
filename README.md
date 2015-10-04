# DWM Config
This is a cutomization of the config.h file for DWM using solarized colors.
## FreeBSD Installation
To use this config with FreeBSD it is recommended that you use the DWM port.
To patch dwm you must navigate to the DWM port directory located at 
/usr/ports/x11-wm/dwm then run `sudo make clean patch DWM_CONF=/path/to/config.h`. 
Navigate to work/dwm-6.0 then run `sudo patch -p1 < /path/to/dwm-6.0-xft.diff`. 
You can get dwm-6.0-xft.diff from [here](http://dwm.suckless.org/patches/xft). 
Finally navigate back to the dwm port directory and run `sudo make install` 
