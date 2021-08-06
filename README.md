# AsherLiu's build of suckless( dwm / st / dmenu )

* [DWM](./dwm/README.md)
* [st](./st/README.md)

## Requirements

In order to build dwm you need the Xlib header files.

## Installation

```sh
sudo make clean install
```

## Patches

some function come from the official patch.

visit suckless.org to get more patches.

```sh
patch < dwm-xxx.diff
```
*/patches/* is the patches I patched.
