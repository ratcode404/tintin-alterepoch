# tintin-alterepoch

A very basic configuration to provide a clean layout useable in [Alter Epoch](https://ae-mud.com/) in the [TinTin++](https://tintin.sourceforge.io) MUD client.

![Screenshot](https://i.imgur.com/ntevAjR.png)

## Installation
Download the TinTin++ Mud client, find the `/bin/ folder` in it and replace the `main.tin` inside.  
For my settings to work correctly I use a rather small and clean window, so I can do whatever next to it, even on one monitor. You might have to fiddle a bit more if you want to use it fullscreen.  
`TinTin Options - Text - Consolas, 10` and `TinTin Options - Window Columns 120, Rows, 62`

## Features
* OOC chat window with time-stamps
* Status chat window (with suppressed status bar after every output received)
* Movement Scaling highlighted
* Custom accessible color highlighting, for names or misc.
* Macros possibilities
* Automated logging of current and last session
* Working scrollbar
* Suppressed command echos

#### Color Highlighting
To customize your highlights, find the example `#HIGHLIGHT` in `/bin/main.tin` on line 3. More information on available colors can be found [here](https://tintin.mudhalla.net/manual/highlight.php).

#### Color Highlighting
To customize your macros, find the example `#ALIAS` in `/bin/main.tin`. 

## Disclaimer
The files in this repository were created and modified by me and [Scandum](https://github.com/scandum) for my own personal use and come with no guarantee to work for you. I provide these files "as-is" and offer no support whatsoever to get them working. 
