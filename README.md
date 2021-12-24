# Personal dwm build 

My personal dwm build with its patches and personal tweaks.
Go to `config.h` for key bindings.

## Included patches:

- Reads xresources colors/variables (i.e. works with `pywal`, etc.).
- scratchpad: Accessible with mod+shift+enter.
- New layouts: bstack, fibonacci, deck, centered master and more. All bound to keys `super+(shift+)t/y/u/i`.
- True fullscreen (`super+f`) and prevents focus shifting.
- Windows can be made sticky (`super+s`).
- stacker: Move windows up the stack manually (`super-K/J`).
- shiftview: Cycle through tags (`super+g/;`).
- vanitygaps: Gaps allowed across all layouts.
- swallow patch: if a program run from a terminal would make it inoperable, it temporarily takes its place to save space.

## Installation:

My personal dwm build with its patches and personal tweaks.
Go to `config.h` for key bindings and shortcuts.


```
$ git clone https://github.com/IHatePineapples/dwm
$ cd dwm && sudo make clean install
```
Todo: Man page
