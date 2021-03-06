# What is lazy-dwm
A fork of Suckless's Dynamic Window Manager with some common patches applied.

Because of Suckless's limitation in 2000 SLOC, DWM is not that usable out of the box and many users have to apply the same patches to get the functionality they want. We have applied some common patches you would probably apply anyways to save you some time!

# Our goals
Our goal is to save DWM users some time by applying patches they would likely have to apply anyways and providing compatibility between the applied patches (e.g. systray and alpha patches aren't compatible even when patching manually. After applying the patches mentioned before, additional changes are required to make DWM work). We also hope our project will help new users and popularize DWM and tiling window managers in general.

# Patches we've applied

Patches that work without known issues:

* actualfullscreen
* alpha
* attachdirection
* barpadding
* cfacts
* cfacts-vanitygaps
* cyclelayouts
* fadeinactive
* movestack
* systray

Patches that work with some issues:

* tatami (Issue: gaps do not apply)
