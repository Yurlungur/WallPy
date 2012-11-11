WallPy-A program for randomizing your wallpaper
=================

This is a small program written in python to cycle through your
wallpapers in a random order.

DEPENDENCIES:
------------------------------
Python3
Bash
xsetroot OR nitrogen OR your favorite command line wallpaper setting tool.
------------------------------

INSTALLATION:
-------------------------------

Add cycle_wallpaper.sh to your path.

Open up randomwallpaper.py and change WALLPAPER_DIRECTORY to your
wallpaper directory.

Similalry, set the path for your set command (like nitrogen or
xsetroot).

Set CONFIGURATION_FILE to the path you want you configuration file
saved to, and the name.

Save your changes and close randomwallpaper.py.

Open cycle_wallpaper.sh. Set ROTATOR to the path to randomwallpaper.py.

If you're using a simple windows manager, open up .xinitrc and add the line
cycle_wallpaper.sh time.

Time should be a number of seconds, or a number of units, and a unit. I.e.,
cycle_wallpaper.sh 1h
cycles every hour.
cycle_wallpaper.sh 15m
cycles every 15 minutes.

If you're using a more complicated windows manager, add the command to
the commands that run at startup by either making a new .desktop file
or by using the menus available.
