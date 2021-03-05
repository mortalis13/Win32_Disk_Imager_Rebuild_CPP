# Win32 Disk Imager [Rebuild]

Custom build of the [**Win32 Disk Imager**](https://sourceforge.net/projects/win32diskimager) application for wrinting images to **USB** or **SD Cards**.  
Check the **README.txt** for the original description.

## Download

### v1.2
- [win32-disk-imager-1.2.zip](https://github.com/mortalis13/Win32_Disk_Imager_Rebuild_CPP/releases/download/v1.2/win32-disk-imager-1.2.zip)

## Modifications
- added cmd argument for image path, used as the first program arg
- check buttons state when the image path field is modified manually
- added some shortcuts
- removed warning message before writing
- fixed size window
- drag'n'drop for image files (works when ran as admin)

## Build
1. Install [**Qt 5.7.0**](http://qtmirror.ics.com/pub/qtproject/archive/qt/5.7/5.7.0/qt-opensource-windows-x86-mingw530-5.7.0.exe).
2. Open **Qt Creator** as **admin**.
3. Load the **src/DiskImager.pro** project.
4. **Run**.
