# .dotfiles
Dotfiles for my i3wm that i want to share with friends or me in future. I'll try to update them timely :)

TODO:

#picom

fix strange GPU chokes sound with picom GLX backend (if you want to use this dotfiles now you can experience this problem on NVIDIA Optimus laptops

--> fixed by adding vsync option to configs, configuring power plans in rog/asus ctl and curves.

remove picom transparency when right-clicking 


#display manager

set up a theme for lightdm

#i3-conf

configure a power-profiles binds like mod+X setting up "Performance" profille with relevant tools like tlp, asusctl, etc, !!!FAN CURVES!!!

configure keyboard layout switching when re-plugging keyboard

#Nvidia

configure a "hot swap" between my home setup "3 HiDPI monitors" and laptop setup "just 1 2K monit"
practically: removing all cables and go, without any X11 glitches


#fans

get curves configs at asus ROG G513RW (asusctl doesn't work properly)
--> solved by configure rog-fan-curve and rog-daemon.
