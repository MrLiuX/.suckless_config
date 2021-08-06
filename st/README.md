# AsherLiu's build of st

st is a simple terminal emulator for X which sucks less.


## Requirements

In order to build st you need the Xlib header files.


## Installation

Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

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

## Running st

If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

```sh
tic -sx st.info
```

See the man page for additional details.

## Credits

Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

