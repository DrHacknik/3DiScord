# 3DiScord
## A Discord client for the 3DS

3DiScord is a heavily WIP Discord client for the 3DS based on [VitaCord] (https://github.com/devingDev/VitaCord) by [devingDev / coderx3](https://github.com/devingDev/).  
Note: this is based on an old version of VitaCord so no DMs and it may crash.  
If something is wrong, contact me on Discord: cheuble#4952

### Features

* Send and recieve messages in servers only (no DMs **at the moment**)
* 2FA supported

### Credits

* UI and port by [cheuble] (https://github.com/cheuble)
* Network features by [Rinnegatamante] (https://github.com/Rinnegatamante/) (from lpp3ds)
**All the original VitaCord staff:**
* coderx3 (devingDev)
* Arkanite
* XandridFire
* SKGleba
* Rinnegatamante
* xyz
* noname120
* davee
* T3CHNOLOG1C  

### Building

In order to build this homebrew, you'll need the following requirements:
* devkitARM (included in devkitPro)
* ctrulib (included in devkitARM)
* [3ds portlibs] (https://github.com/devkitPro/3ds_portlibs)
* [sf2dlib] (https://github.com/xerpi/sf2dlib)
* [sfillib] (https://github.com/xerpi/sfillib)
* [sftdlib] (https://github.com/xerpi/sftdlib)
Once you have installed these, a simple `make` should compile it. If you have FBI installed on your 3ds, and python installed on your computer, open FBI and go to `Remote install` -> `Recieve URLs over the network`.
 On your computer, type `make spunch`. This should install the CIA directly on your 3DS!
 
### Changelog

**1.0**
* Initial Release