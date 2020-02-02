# NOBORU
<img src="/res/logo.png" width="50%" height="50%"><br>
App for PSVita to read manga or comic<br>
All issues with parsers should be in <a href="https://github.com/Creckeryop/NOBORU-parsers">this repo</a>
```diff
- There is a lot of problems with performance, i don't think i can solve 'em all
```
### Requirements:
* At least 10-20 MB memory (for online reading) or more (for offline reading)
### Data structure:
```
ux0:data/noboru/books/ - folder that holds library saved manga info
ux0:data/noboru/cache/ - folder that holds chapters saved
ux0:data/noboru/parsers/ - folder for parsers
ux0:data/noboru/save.dat - library save
ux0:data/noboru/settings.ini - application settings
```
You can simply delete `noboru` folder to reset all settings
## Features:
* Browsing manga sites
* Searchinge
* Reading manga (with Vertical or Horizontal mode!)
* MultiTouch, Swipes and other touch things
* Adding manga to library
* Loading longpages (webmanga) without downscaling (thanks to my [piclib](https://github.com/Creckeryop/piclib))
* Multilanguage
* Reading without network (Offline mode !!Don't forget to add manga in library!!)
## TODO:
* Caching info about last readed chapters (to make continue function)
* History
* More languages
## Screenshots:
![s1](/res/screenshot1.png)
![s2](/res/screenshot2.png)
![s3](/res/screenshot3.png)
![s4](/res/screenshot4.png)
## FAQ:
<b>Q</b>: I found bug that ...<br>
<b>A</b>: You can create issue [here](https://github.com/Creckeryop/NOBORU/issues), give screenshot with error or error file<br>
<br>
<b>Q</b>: Is it safe to use?<br>
<b>A</b>: I'm really don't know, but i use safe eboot.bin(App have access only to `app0:` and `ux0:data`, so no important files will be removed)<br>
<br>
<b>Q</b>: How to view debug console?<br>
<b>A</b>: DPAD_LEFT + START<br>
<br>
<b>Q</b>: App crashes with...<br>
<b>A</b>: Again, create issue [here](https://github.com/Creckeryop/NOBORU/issues)<br>
<br>
<b>Q</b>: Reader doesn't load some images<br>
<b>A</b>: Please create Issue and describe how you come to this (Parser you used, Manga, Chapter and page)<br>
<br>
<b>Q</b>: I downloaded app and can't see any parsers<br>
<b>A</b>: Press Triangle to update parser list, so if that won't help create issue [here](https://github.com/Creckeryop/NOBORU/issues)<br>
## Compile
	Execute `build.bat`
## Credits:
[Rinnegatamante](https://github.com/Rinnegatamante) - [LuaPlayerPlus_Vita](https://github.com/Rinnegatamante/lpp-vita)
<br>[VitaSDK](https://github.com/vitasdk) - vitaSDK
<br>[xerpi](https://github.com/xerpi) - [libvita2d](https://github.com/xerpi/libvita2d)
