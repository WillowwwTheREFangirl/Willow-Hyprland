# Willow-Hyprland

### Important

This script automates the installation and setup of my Arch Hyprland environment.

    If you want to try it, you should use a minimal profile and backup your system beforehand.

### Note

This script does not include package uninstallation, as some packages may already exist on your system by default. Creating an uninstallation script could potentially affect your current setup.


### Second Note

If installing this on a Arch-Based distro such as CachyOS and not normal Arch Linux, SELECT NO DESKTOP ENVIRONMENT.

Also install git by doing sudo pacman -S git. this allows you to clone this repo to run the install script.


### Keybinding

SUPER + H (Windows + H) to open keybinding hints.


### Installation


Use this script to install Hyprland on an Arch-based system:

```shell

git clone --depth=1 https://github.com/WillowwwTheREFangirl/Willow-Hyprland.git
cd ~/Arch-Hyprland
chmod +x install.sh
./install.sh
