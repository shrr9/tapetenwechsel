# Tapetenwechsel

This is a project heavily inspired by the plasma applet 'Animated Hue' by Zren (https://github.com/Zren/plasma-wallpapers/tree/master/animatedhue) and designed to replicate the color changeing wallpaper with the wallpaper manager nitrogen, so without the need to actually run plasma.

# How to use
Make sure nitrogen is installed, as well as python with the modules PIL and tqdm.
Clone this directory, cd into it and chmod +x prepare set_wallpaper.
Setting a wallpaper requires two steps, but the first is only needed once.

First, t prepare the wallpaper,  all differenct color shades have to be created. To do this, run ./prepare path/to/image.jpg 20, where the last number represents the number of color shades in a cycle. This might take a while, as it has to create all color shades and saves them in a seperate directory in this git repository.

Second, to set the wallpaper, run ./set_wallpaper image 1. The last number is the delay in seconds between two color Shades.

# Disclaimer
This is just for fun and a very coarse scaped together project, so bugs are expected, and i might not have the motivavtion to improve it. Just have a look at the code yourself, its not too hard :)

# Enjoy
