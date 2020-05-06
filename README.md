# x11_many_button_mouse_config
For X window system, many button mouse config file

# Overview
In Fedora, CentOS, Redhat, Asianux,
you can only use up to 10 mouse buttons with MX Revolution.
So, you can't use Sum wheel buttons. 
But, you can use up to 20 mouse buttons with this file.

# How to use
1. Copy 11-logicool-mxrevolution.conf to /usr/share/X11/xorg.conf.d/
2. Restart X11

# Remodeling method

If you use mouse other than MX Revolution, do the following process.

1. xinput --list
2. Change the Identifier and MatchProduct to output device of "xinput --list".

# Others
Ubuntu doesn't need this file.
In Wayland, this file isn't referenced.

