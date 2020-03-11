# my-x11-keymaps
A backup for the config file of my computer.

## Usage ##

Swap <kbd>Capslock</kbd> and <kbd>Ctrl_R</kbd> in X11.
Change <kbd>Alt_R</kbd> to <kbd>Esc</kbd> in X11.

**NOTE:** Only work in X11.
NOT console.

See [Freed-Wu/my-keymaps](http://www.github.com/Freed-Wu/my-keymaps) to
know keymaps in console.

See [dual-key-remap](https://github.com/ililim/dual-key-remap) and
[xkeymacs](https://github.com/fujieda/xkeymacs) to know keymaps in Window OS.

## Install ##

```{bash}
cd /usr/share/X11/xkb/symbols
sudo chown $USERNAME .
sudo chgrp $USERNAME .
git clone git@github.com:Freed-Wu/my-keymaps.git
mv my-keymaps/* . && rm my-keymaps
```

