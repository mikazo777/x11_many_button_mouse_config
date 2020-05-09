# x11_many_button_mouse_config
For X window system, many button mouse config file

# Overview
On Fedora, CentOS, Redhat and Asianux,
you can only use up to 10 mouse buttons.
But, if you use this file, you can up to 20 mouse buttons with your mouse.

# How to use
1. Copy 11-logicool-mxrevolution.conf to /usr/share/X11/xorg.conf.d/
2. Restart X11

# Remodeling method

If you use mouse other than MX Revolution, do the following process.

1. xinput --list
2. Change the Identifier and MatchProduct to output device of "xinput --list".

# Others
Ubuntu doesn't need this file.
On Wayland, this file isn't referenced.

