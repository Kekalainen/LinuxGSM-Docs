# Config Files
```
serverfiles/ShooterGame/Saved/Config/LinuxServer/GameUserSettings.ini
serverfiles/ShooterGame/Saved/Config/LinuxServer/Game.ini
```

# Adding Mods

Add `-automanagedmods` to the [[start parameters]].

Next edit `GameUserSettings.ini`, adding the following line under `[ServerSettings]`.
```
ActiveMods=[workshopID],[workshopID],[workshopID],[workshopID]
```
Replace `[workshopID]` with required workshop ID's.

All workshop mods can be found here http://steamcommunity.com/app/346110/workshop/.