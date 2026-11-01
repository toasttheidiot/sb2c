# sb2c

Converts a `.sb3` project into a devkitPro project (C source + romfs assets + Makefile).

## Setup
Prerequisites: Linux computer, preferably Arch Linux. If you don't have a Linux computer you can use WSL on Windows
Switch prerequisites: `pacman -S switch-dev switch-sdl2 switch-sdl2_image switch-sdl2_ttf`.
SVG costumes are rasterised at build time: `pip install cairosvg` (or install `rsvg-convert`).
Refer to the [devkitpro wiki] for more information about setup for development for switch and other devices.

[devkitpro wiki]: https://devkitpro.org/wiki/Main_Page
