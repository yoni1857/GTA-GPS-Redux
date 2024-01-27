# GTA SA GPS Redux

This mod includes automatic navigation for mission markers as well as the player target.
If you'd like to contribute, go ahead.

    Warning: This mod is still in the testing phase, if you find any 
    bugs, please report them as issues on this github repo.
    SAMP is not supported.
---

## Known Issues
The mod currently doesn't work with pickups due to technical reasons.
In some missions, a nav route will not appear for a valid target. 
This is a limitation of SA's pathfinding, as some coordinates break it and make it not generate any path. This also happens with the target route.

## Re-Upload Policy
If you'd like to distribute this mod, please ask for my (juicermv) permission first. 
If you downloaded this mod from anywhere other than https://github.com/juicermv/GTA-GPS-Redux,
make sure the source you downloaded this mod from can be trusted and is approved by me. If you're concered about people reuploading this mod without permission, you may reach me at the page listed above.

## You can find the latest release under the releases on the GitHub page. For the latest WIP build (unstable) check out the Actions tab on the GitHub.

## Installation

1. Via modloader
    - Create a new folder inside your modloader folder. You can name it whatever you want.
    - Drop/extract all the files from the release archive you downloaded into that folder.

2. Via asi loader/scripts folder
    - Drop/extract all the files from the release archive you downloaded into your scripts folder.

## [Default Config](GPSLine/SA.GPS.CONF.ini)
### This mod uses the following libraries:
* [mINI](https://github.com/metayeti/mINI)
* [plugin-sdk](https://github.com/DK22Pac/plugin-sdk)
