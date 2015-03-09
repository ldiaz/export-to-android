# Android Assets for Photoshop


A Photoshop script for exporting assets for web.

The script works by duplicating the selected layer (or layergroup) to a new document, then scaling it to each of the 5 common Android sizes (XXHDPI, XHDPI, HDPI, MDPI, and LDPI) and then putting the files inside a folder next to the PSD.

## Installation
1. Download the script here

2. (Or load directly from PS from File - Command - Explore). Move the .jsx file to your Photoshop scripts folder. If you don't know where that is, you can easily find out by following the instructions <a href="http://www.outbackphoto.net/news/2013/2/17/free-script-where-is-my-photoshop-scripts-folder.html" target="_blank">on this quick post</a>.

## Common Errors

If you get any error message be sure of the following:

1. Document units must be pixels so the script can work out, you can switch to pixels just before execute if you like, and then change them again.

2. Do not change the default options if you use the "Export to web" feature, any change will be applied when the script executes. If you change any revert before execute the script.
