# Wallpaper Dmenu in Wofi

![Demo](wallpaperwofi.gif)

This a bash script that grabs contents from your wallpapers directory and displays in dmenu mode with wofi

## Summary
The bash script runs as follows:
1. Searches through the `~/Pictures/Wallpapers` directory for folders and images and labels them according to their filetypes
2. Displays the options in wofi dmenu mode
3. Recursively executes script if folder is chosen
4. Otherwise runs the `walset` script available [here:](https://github.com/Ay1tsMe/walset)

(If required, change the `BASE_DIR` variable to the directory of your wallpapers and change the `walset` script to whatever wallpaper set script you use)

