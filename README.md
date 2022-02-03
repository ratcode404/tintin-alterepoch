# tintin-alterepoch

A very basic configuration to provide a clean layout useable in [Alter Epoch](https://ae-mud.com/) for the [TinTin++](https://tintin.sourceforge.io) MUD client.

![Screenshot](https://i.imgur.com/gMdtXsy.png)

## Installation
Installing the configuration is easy. Download the TinTin++ Mud client, find the `/bin/ folder` of the installation and replace the files inside. The standard installation for WinTin++ installations directs to `C:/Users/XXX/AppData/Roaming/WinTin++/bin`.

#### Custom Size settings in TinTin++ for correct display
For my settings to work correctly I use a rather small and clean window, so I can do whatever next to it, even on one monitor. You might have to fiddle a bit more if you want to use it fullscreen.  
set `TinTin Options - Text - Consolas, 10`  
and `TinTin Options - Window Columns 120, Rows, 62`  
  
#### Custom Prompt
To correctly display the prompt bar, you have to change the AE basic prompt. This only has to be set once per character.  
Use the custom command `QUICKCONFIG` for this.
  
## Features
* OOC chat window with time-stamps
* Status chat window (with suppressed status bar after every output received)
* MV highlighted and slightly more accessible level info
* Custom accessible color highlighting, for names or misc.
* Macros possibilities
* Automated logging of current and last session
* Working scrollbar
* Suppressed command echos
* Possible to use TinTin++ mapping features, although no plans to make a HUD for this

#### Color Highlighting
To customize your highlights, find the example `#HIGHLIGHT` in `/bin/highlight.tin` on line 1. More information on available colors can be found [here](https://tintin.mudhalla.net/manual/highlight.php).

#### Color Highlighting
To customize your macros, find the example `#ALIAS` in `/bin/macros.tin`. There is an example one which removes your boots and gloves with one command.

## Disclaimer
The files in this repository were created and modified by me and [Scandum](https://github.com/scandum) for my own personal use and come with no guarantee to work for you. I provide these files "as-is" and offer no support whatsoever to get them working. 
