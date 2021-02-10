# My Dotfiles

These are my configuration files of all my basic working environment in linux

## Installation

Just download the files and replace them with the corresponding ones in your configuration folder.

```bash
git clone https://github.com/CMOISDEAD/DROPFILES.git
cd dotfiles
```

## Usage
### Requirements

1. Bspwm
2. Sxhkd
3. compton
4. Hack Nerd Fonts, Fira Code Nerd Font
5. Polybar
6. Rofi


### Bspwm
To configure the corresponding with the machine startup and bspwm, enter the bspwm folder and configure the bspwmrc,
there you configure your workspaces among other things.

### Sxhkd
There you will have the configuration of the keyboard shortcuts etc.

Some applications that come by default are:

 1. Firefox
 2. Gnome Terminal
 3. Thunar

### Compton
For transparency, fade effect when changing work area etc.

### Fonts 
My setup uses two fonts, both come from Hack Nerd Fonts.
These are Fira Code and Hack Nerd Font.

You can change them from the "polybar/config"

### Polybar
This is my status bar, which I try to please you, it has some modules ready to be used and others that require a very simple configuration to use.

The modules that it has by default are, backlight for brightness, alsa for sound (these two are managed with the mouse scroll), a module for the date and a power menu, these on the right side, on the left side it has xworkspace for workspaces and xwindow for window titles.

Most of the scripts I use are in my bin folder.

## Rofi
I use rofi as an application launcher and powermenu.
