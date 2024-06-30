# mcmodvcs
A version control system shell script for managing Minecraft mods
# Installation
### Arch Linux
Available as `mcmodvcs` in AUR
### Other Linux distro
Download and copy `mcmods.sh` to a directory under $PATH of your choice and rename to `mcmods`\
For example, to download and install to /usr/bin:\
``` # mv /path/to/mcmods.sh /usr/bin/mcmods ```
# Basic usage
You can create a snapshot of your current mods folder by using\
``` mcmods save <name> ```\
To load a snapshot, use\
``` mcmods load <name> ```\
To overwrite last loaded/saved snapshot with your current mods folder, use\
``` mcmods sync ```\
For list of all functionalities, use\
``` mcmods help ```
