# SWAPAPP
Swapapp allows you to easilly create edit and delete swap files for linunx machines

![imageedit_14_3059041997](https://github.com/alkisqwe/swapapp/assets/73914940/6f8f0694-8e8f-4fd8-b6e7-d4b9c6575f3a)

# Usage
```
python3 swapapp.py
```
available parameters
```
usage: swapapp.py
 -h,--help                   give this help list
 --gui                       open gui version

usage: swapapp.py list [options]
 -i,--include                include folder to search

usage: swapapp.py create [options] swapfile
 -tp,--temporary-permanent   (0=temporary,1=permanent)(default 1)specify temporary(until reboot) or permenant
 -s,--size                   (required)specify size in mb of swapfile
 -p,--priority               (default=auto)specify priority for swapfile

usage: swapapp.py edit [options] swapfile
 -c,--change                 change swap filename
 -tp,--temporary-permanent   (0=temporary,1=permanent)specify temporary(until reboot) or permenant
 -s,--size                   specify size in mb of swapfile
 -p,--priority               specify priority for swapfile

usage: swapapp.py delete swapfile

usage: swapapp.py disable swapfile

usage: swapapp.py enable [options] swapfile
 -p,--priority               set temporary priority(Until Reboot)

```
if you don't use any parameters, you'll enter GUI version
