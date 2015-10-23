# mpdmenu
mpdmenu is a small script to modify your MPD playlist using dmenu.
You can add and remove songs, clear the playlist or jump to a position in the playlist.
Since it uses mpc to interact with MPD, it would be easy to add other options (e.g. change volume/repeat/...).

## Features
This fork adds greater control and UX improvements:
* Fuzzy search through a directory
* Display of currently playing track
* One-key shortcuts to actions

To set the search directory, change $SEARCH\_PATH in mpdmenu.sh

## Requirements
Fuzzy search depends on [rofi](https://davedavenport.github.io/rofi/), a dmenu replacement.
You should also have *locate*, which usually ships with Debian.

