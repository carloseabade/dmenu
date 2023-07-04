# dmenu - dynamic menu

dmenu is an efficient dynamic menu for X. It's one of suckless utilities, more info [here](https://tools.suckless.org/dmenu/).

## Patches

As this is my own build, I've added some patches to it.

- [center](https://tools.suckless.org/dmenu/patches/center/)

## Requirements

In order to build dmenu you need the Xlib header files.


## Installation

Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

```bash
$ make clean install
```

## Running dmenu

See the man page for details.
