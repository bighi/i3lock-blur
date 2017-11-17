# 3lock-blur
Small script that locks your computer with a screensaver that is a blurred version of your current screen

## How it works

When the script is called, it will use *scrot* to take a screenshot of your screen. Then it blurs the image using *imagemagick*, and uses *i3lock* to block your screen with the blurred image as a static screensaver.

## Dependencies

- i3lock
- scrot
- imagemagick

## Usage

I use this with the i3 window manager. You should set a keyboard shortcut to lock your screen. I use Ctrl-Alt-L.

Example:

bindsym Ctrl+Mod1+l exec ~/scripts/i3lock-blur

You should replace the path above with the correct path to where you saved the script.
