# Windows-Ink-Pressure-Fix
Fix to problem with pressure reading on some tablets in apps, that are using Windows Ink API.

* Download Open Tablet Driver from https://github.com/InfinityGhost/OpenTabletDriver and unzip it somewhere you would like to stay.

* Download VMulti Driver from https://github.com/X9VoiD/vmulti-bin/releases/tag/v1.0. Unzip it and run `install_hiddriver.bat` as administrator by Shift+right clicking it.
* In OTD Folder run `OpenTabletDriver.Daemon.exe` first and then `OpenTabletDriver.UX.Wpf.exe`.
  First one is an actual program for managing tablet inputs/outputs and have to be runnin all time. The second one is UI for driver and setting stuff up and not necessary to run it every time.

* In `Output` tab at the bottom choose `Windows Ink Absolute Mode`.

  ![image](https://github.com/user-attachments/assets/9ebaa176-3a0d-4b5d-8b53-19251f1bab61)

* In `Pen Settings` tab > `Tip Settings` click `...`, set `Type` to `Windows Ink` and `Button` to `Pen Tip`

* ![image](https://github.com/user-attachments/assets/5843378a-8612-48bb-9af5-aeabb12099c3)

* Click `Apply`
