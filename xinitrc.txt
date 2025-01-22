#!/bin/sh

# set up the display res and scaling
xrandr --output eDP1 --mode 1920x1200 

# exec prgms
picom &
exec dwm
exec dmenu


