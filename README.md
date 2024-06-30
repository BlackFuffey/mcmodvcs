# mcmodvcs
A version control system shell script for managing Minecraft mods
# Installation
### Arch Linux
Available as `mcmodvcs` in AUR
### Other Linux distro
Download and copy `mcmods.sh` to a directory under $PATH of your choice and rename to `mcmods`\
For example, to download and install to `/usr/bin` using wget:
``` 
# wget https://raw.githubusercontent.com/BlackFuffey/mcmodvcs/main/mcmods.sh -O /usr/bin/mcmods
```
# Basic usage
You can create a snapshot of your current mods by using\
``` mcmods save <name> ```\
\
To load a snapshot, use\
``` mcmods load <name> ```\
\
To overwrite last loaded/saved snapshot with your current mods folder, use\
``` mcmods sync ```\
\
For list of all functionalities, use\
``` mcmods help ```
