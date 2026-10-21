# Landcros Manual Library: releases

Installers for the Landcros Manual Library program (Windows and Linux). This repository holds only the signed
installers and the update lists the program reads; the program checks here for new versions.

**Install:** open [Releases](../../releases/latest), download the file for your computer and run it:

- **Windows:** `Landcros-Manual-Library-<version>-win-x64.exe`. The first time, Windows SmartScreen may say
  "Windows protected your PC": choose **More info**, then **Run anyway**.
- **Linux:** `Landcros-Manual-Library-<version>-linux-x86_64.AppImage`. Make it executable, then run it.

Every installer has a signature file beside it (`.sig`). The program checks it before installing any update and refuses
anything unsigned or altered.
