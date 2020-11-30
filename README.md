# pxllock 🔒
A simple, fast wrapper script to make X11 lockers look fancy

Inspired by blurlock as seen in Manjaro i3, it aims to root out its maim problem with **speed**, with the ability to now use maim or ffmpeg instead of/with imagemagick and to pixelate instead of blur.  
Also you can use [xsecurelock](https://github.com/google/xsecurelock) as an alternative to i3lock, and I’m planning to add support for more lockers.

## Installation
Just download or fork this repo and copy the `pxllock` script to a location like `/usr/local/bin` or `~/.local/bin` (must be in youth \$PATH to work from anywhere in the system) and install the needed [Dependencies](#dependencies).

To automatically launch it you can use tools like xss-lock or xautolock, please look up their man pages for further info.

## Usage
`pxllock <imagemagick|maim|ffmpeg> <i3lock|xsecurelock> [locker arguments]`

## Dependencies
- screenshot & pixelation:
  - imagemagick (slow) _or_
  - maim + imagemagick (faster) _or_
  - ffmpeg (fastest)
- lockers:
  - i3lock _or_
  - xsecurelock + xloadimage

## To-do:
- more lockers
- more options for manipulating the screenshots
- AUR package
