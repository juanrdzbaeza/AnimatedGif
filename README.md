# AnimatedGif

AnimatedGif is an screensaver for Mac OSX / macOS that plays animated gif's.

It also has a background mode to let you run the gif as a desktop background (or wallpaper). Unfortunly the screensaver clock is not working together with background mode and will be disabeld. But the clock works fine in normal screensaver mode. The background mode can be enabled under "Screen Saver Options" in macOS.

You can neither open only one single GIF file file or you can choose a directory that contains more than one GIF file. In case of an selected directory the option panel of screensaver let you choose a time between 1 and 30 minutes when the GIF file is randomly changed.
<br>

## Compatibility

This project was originally written with Xcode 6.2 and SDK for OSX 10.9 Mavericks and latest release was compiled with Xcode 10.1 with SDK for OSX 10.14 Mojave.

The latest release was tested successfully under Mavericks(10.9.5), El Capitan(10.11.6) and Mojave(10.14.1).

<br>

## Setup - Mac

1. Download and unzip the compiled release file from the releases tab: https://github.com/Waitsnake/AnimatedGif/releases/latest/
2. Double click on the extracted "AnimatedGif.saver" file. macOS will ask if you like to install the screen saver
3. Open ***System Preferences -> Desktop and Screensaver***
4. Select the AnimatedGif Screensaver
5. Click "Screen Saver Options" below the screensaver preview
6. Select your .gif file and adjust other settings to your liking
<p align="left">
<img src="readme_extra/screensaver.png?raw=true" width="500"/>
</p>
<p align="left">
<img src="readme_extra/options.png?raw=true" width="500"/>
</p>
<br>


## Uninstall AnimatedGif

***Automatic Uninstall***
<br>
In the linked tools here are 3 different ways to uninstall AnimatedGif. Each tool do the same and what way you choose depending only on your personal preferences.

- <a href="https://github.com/Waitsnake/AnimatedGif/raw/master/tools/Uninstall_AnimatedGif.app.zip">Uninstall_AnimatedGif.app.zip</a> is an ZIP file containing an macOS application that uninstalls AnimatedGif (recommended way for unexperienced users)
- <a href="https://github.com/Waitsnake/AnimatedGif/raw/master/tools/Uninstall_AnimatedGif.scpt">Uninstall_AnimatedGif.scpt</a> is an AppleScript that uninstalls AnimatedGif
- <a href="https://github.com/Waitsnake/AnimatedGif/raw/master/tools/Uninstall_AnimatedGif.sh">Uninstall_AnimatedGif.sh</a> is an shell script that uninstalls AnimatedGif
<br>

***Manually Uninstall***
<br>
1. Open ***System Preferences -> Desktop and Screensaver***
2. Click "Screen Saver Options" and stop the background mode if it was enabled and close options.
3. Right click the AnimatedGif Screensaver and select "Delete AnimatedGif"
4. Click on "Move to Trash" to confirm
<p align="left">
<img src="readme_extra/delete1.png?raw=true" width="500"/>
</p>
<p align="left">
<img src="readme_extra/delete2.png?raw=true" width="500"/>
</p>
<br>


Copyright 2015 Marco Koehler
(under the conditions of MIT License)
