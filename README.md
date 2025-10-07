# swayview
A minimal layout launcher for SwayWM that opens a set of apps (e.g. mpv, feh, kitty) in a specific horizontal or vertical layout with predefined ratios.

* When you run swayview, the specified programs open according to the specified layout and thats it -- this just saves a bit of time getting back to frequently used workflows and resizing them manually
* Windows can be tiled 1/3 evenly by default, but this can be changed easily
* This program will not auto-resize them if something else opens, it will just apply sway's default behaviour, this is just for opening windows in a specific layout
* I was planning to loop a local video folder from mpv and image folder from feh, but these are just run commands can easily be changed (mpv --shuffle ~/Videos, feh -rzsZFD 7 ~/Images-1, ...)
