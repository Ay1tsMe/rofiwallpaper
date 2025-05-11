# Wallpaper Dmenu in Rofi

![Demo](wallpaperrofi.gif)

This a bash script that grabs contents from your wallpapers directory and displays in dmenu mode with rofi

## Summary
The bash script runs as follows:
1. Searches through the `~/Pictures/Wallpapers` directory for folders and images and labels them according to their filetypes
2. Displays the options in rofi dmenu mode
3. Recursively executes script if folder is chosen
4. Otherwise runs the `walset` script available [here:](https://github.com/Ay1tsMe/walset)

(If required, change the `BASE_DIR` variable to the directory of your wallpapers and change the `walset` script to whatever wallpaper set script you use)

## Note
In order to display the folder icon, you must copy a `folder.svg` file of your choice and place it in the `$HOME/.local/share/icons/folder.svg`

