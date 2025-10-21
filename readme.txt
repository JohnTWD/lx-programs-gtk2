Archives of the last versions of GTK-2 LXDE programs on the Arch repository
that I used before they were considered deprecated on 2025/10/21 and removed in
favor of GTK-3.

Why? Because I like my GTK-2 theme better, and I can't bother to find a GTK-3
theme or port it there.


Inside are x64 packages of the following:
	PCManFM     1.4.0-1
	LXPanel     0.11.1-2
	LXTask      0.1.12-1
	libfm-gtk2  1.4.0-1
	

Install everything via `sudo pacman -U *`, then add each package to exclusion list,
`IgnorePkg = libfm-gtk2 lxpanel lxtask pcmanfm`

There are probably some additional dependencies that is not included inside, but
my computer already has them. This repository is only meant for myself the next
time I want to reinstall Arch. If you are interested improving the way I did 
this, perhaps package it into an AUR repository that can be used by anyone, that
would be great! 