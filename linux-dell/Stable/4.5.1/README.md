# linux 4.5.1 - Stable
## dsmethod.patch
This patch fixes the WD15 dock WOO HOO

## all other patches from [Arch Forums](https://bbs.archlinux.org/viewtopic.php?pid=1619336#p1619336)


##Misc notes
Please consider editing the pkgbuild to enable modprobed-db.  
For Arch users install this from aur
https://aur.archlinux.org/packages/modprobed-db
And read the archwiki:
https://wiki.archlinux.org/index.php/Modprobed-db

Just remember to plug in all your devices and run it. This will speed up your compile time down to 8 minutes.

##Compile
makepkg -s
pacman -U <package name>

