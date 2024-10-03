# Windows-Ink-Pressure-Fix
Fix to problem with pressure reading on some tablets in apps, that are using Windows Ink API.

* Download Open Tablet Driver from https://github.com/InfinityGhost/OpenTabletDriver and unzip it somewhere you would like to stay.

* Download VMulti Driver from https://github.com/X9VoiD/vmulti-bin/releases/tag/v1.0. Unzip it and run `install_hiddriver.bat` as administrator by Shift+right clicking it.
* In OTD Folder run `OpenTabletDriver.Daemon.exe` first and then `OpenTabletDriver.UX.Wpf.exe`.
  First one is an actual program for managing tablet inputs/outputs and have to be runing all time. The second one is UI for driver and setting stuff up and not required to run every time.
* From Top menu click `Plugins` > `Open Plugin Manager...`
* At the bottom of the list find `Windows Ink` and click install.
> [!NOTE]
> My advise to click on `Show plugin wiki` button in plugin info and read the Readme.
* You might want to relog at this point or restart PC.
* In `Output` tab at the bottom choose `Windows Ink Absolute Mode`.

  ![image](https://github.com/user-attachments/assets/9ebaa176-3a0d-4b5d-8b53-19251f1bab61)

* In `Pen Settings` tab > `Tip Settings` click `...`, set `Type` to `Windows Ink` and `Button` to `Pen Tip`

* ![image](https://github.com/user-attachments/assets/5843378a-8612-48bb-9af5-aeabb12099c3)

* Click `Apply`, close that window and click Save in main window.
