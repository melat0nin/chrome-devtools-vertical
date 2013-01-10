chrome-devtools-vertical
========================

A Custom.css stylesheet for Chrome/Chromium which alters the layout of Devtools when docked to the right of the screen so that the code appears horizontally above the attributes pane, instead of next to it. 

![Alt text](https://googledrive.com/host/0B3Ekginw8kODMnd2djRiMnVUMHM/devtools.png "Screengrab of chrome-devtools-vertical")

Firebug allows this layout by default and it's very useful on widescreen monitors; Devtools doesn't yet have the option so this is intended as an interim solution.

Installation:
-------------

Find your Chrome's user stylesheets directory:

- **Windows:** C:\Users\**Your Username**\AppData\Local\Google\Chrome\User Data\Default\User StyleSheets\
- **OSX:** ~/Library/Application Support/Google/Chrome/Default/User StyleSheets/
- **Ubuntu (Chromium):** ~/.config/chromium/Default/User StyleSheets/

Replace the existing Custom.css file with this one, or add the styles in this file to the bottom of your existing Custom.css file (in case you've tweaked other things and want to retain your changes).
No restart needed, changes are applied immediately
