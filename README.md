# dmenu


This is a fork of suckless `dmenu` with a few patches and custom configurations applied.

`dmenu` is an efficient dynamic menu for X.

##### Patches
- [vi mode](https://tools.suckless.org/dmenu/patches/vi-mode/)
- [xresources-alt](https://tools.suckless.org/dmenu/patches/xresources-alt/)

##### Other changes
- Alternate colorscheme
- Bug fixes in vi mode





## Install

Debian and Fedora packages are available.
See [AscendForever/repos](https://ascendforever.com/repos)
    [[secure]](https://secure.ascendforever.com/repos)
    [[tor]](http://zuh3vfagsxufncxiyhrsu4wbcihjdexzvsvm2zoxtypiqjh7nvtdkkqd.onion/repos)
    [[i2p]](http://xryyir2gvnjhdxlsjx2ajdqps4p3yxh5tczboumrizagd4tavwcq.b32.i2p/repos)
    for instructions.





## Upstream readme

```markdown
dmenu - dynamic menu
====================
dmenu is an efficient dynamic menu for X.


Requirements
------------
In order to build dmenu you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


Running dmenu
-------------
See the man page for details.
```
