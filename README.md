# BSDotsInstaller
This is the boilerplate for my install install script

## Usage
The script takes the files found in the ./dots directory and places them into the intended locations

### User Configs
./dots/config -> ~/.config

./dots/fonts -> ~/.fonts

./dots/themes -> ~/.themes

./dots/icons -> ~/.icons

### System Configs
./dots/system/etc -> /etc

./dots/system/themes -> /usr/share/themes

./dots/system/icons -> /usr/share/icons

## Script Configuration
The script will read from the ./logo file to display an ASCII art logo on runtime, the name of the config can be specified in the ./bsconf file