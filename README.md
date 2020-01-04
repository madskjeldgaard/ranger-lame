# ranger-lame
Lame integration plugin for the [Ranger File Manager](https://github.com/ranger/ranger) making mp3 conversion easy 

# Prerequisites

Lame

Install lame on mac using HomeBrew: `brew install lame`
Install lame on ubuntu using apt: `sudo apt install lame`

# Installation
Copy `ranger-lame.py` file to ~/.config/ranger/plugins folder and restart ranger.

# Usage
Select one or more files you want to manipulate using lame and then execute one of the following commands

Currently available commands:
- `:mp3` - convert to mp3 using standard VBR settings
- `:mp3medium` - convert to mp3 using medium VBR settings
- `:mp3extreme` - convert to mp3 using extreme VBR settings
- `:mp3insane` - convert to mp3 using insane CBR settings
