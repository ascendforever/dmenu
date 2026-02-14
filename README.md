# dmenu


This is a fork of suckless `dmenu` with a few patches and custom configurations applied.

`dmenu` is an efficient dynamic menu for X.

##### Patches
- vi mode

##### Other changes
- Alternate colorscheme
- Bug fixes in vi mode



### Debian package
Debian packages are available for stable and oldstable releases.


#### Install the signing key
Clearnet:
```bash
curl https://deb.ascendforever.com/ascendforever.gpg | sudo tee /usr/share/keyrings/ascendforever.gpg >/dev/null
```
Or onion:
```bash
curl http://csjkrevghycpr6b266bk2hrgfotoxsz7xbyfk6rkk63fxlbkbes7b7qd.onion | sudo tee /usr/share/keyrings/ascendforever.gpg >/dev/null
```


#### Add repository
Change `trixie` -> `bookworm` if needed.

Clearnet:
```bash
printf 'deb [signed-by=/usr/share/keyrings/ascendforever.gpg] https://deb.ascendforever.com %s main' trixie | sudo tee /etc/apt/sources.list.d/ascendforever.list
```
Or onion:
```bash
printf 'deb [signed-by=/usr/share/keyrings/ascendforever.gpg] http://csjkrevghycpr6b266bk2hrgfotoxsz7xbyfk6rkk63fxlbkbes7b7qd.onion %s main' trixie | sudo tee /etc/apt/sources.list.d/ascendforever.list
```


#### Install
```bash
sudo apt install -y dmenu
```





## Original readme
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
