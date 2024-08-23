![1](https://github.com/user-attachments/assets/71981178-29e6-4a2c-840e-6a293a9d6dc3)

<img alt="Windows" src="https://img.shields.io/badge/-Windows-0078D6?style=flat&logo=windows&logoColor=white"/> <img alt="NET" src="https://img.shields.io/badge/-Visual%20Basic-blue?style=flat&logo=.net&logoColor=white"/>

# Counter-Strike 2 Server Manager
A simple but effective Counter-Strike 2 server manager tool built with with Visual Basic.NET Framework 4.8.

**Uses SteamCMD to install/update your game servers:** https://steamcdn-a.akamaihd.net/client/installer/steamcmd.zip

**Comments and feedback on Reddit:** https://www.reddit.com/r/cs2/comments/172lgds/my_cs2_server_installerupdaterlauncher/

## Features
- Bulk install/update your game servers in one click
- Bulk start/stop your game servers
- Manage installation folders
- Manage launch parameters
- Locally store your Steam login data
- Download/Install SteamCMD updates
- Verify file integrity
- Autoclose SteamCMD on finish tasks
- Server watchdog  **<-NEW!**

## Server WatchDog
Since v1.5 release, this application includes a server watchdog. If a running server hangs, crashes or is closed, this application will try to restart the server process again. 

To check for hanged/crashed processes i'm using **Process.GetProcessById(Server.ProcessID).Responding = False**, if you know a better way to check for hanged/crashed processes, please open a new issue and i will update as soon as possible.

**Open a new issue:** https://github.com/fpaezf/CS2-server-manager/issues

## Installation & use
- Put the application in a folder on your desktop
- Start the application
- Hit "Install/Update SteamCMD" and wait while application installs all the requiered software
- Add or edit a new server
- Start managing your server

## Screenshots
![1](https://github.com/user-attachments/assets/d8ce9a22-d473-44cc-ada8-32cb26975178)
![2](https://github.com/user-attachments/assets/0d0048e4-d43d-4c3b-889f-329924d4cc81)
![3](https://github.com/user-attachments/assets/1964f433-b1ae-43ea-8db2-ff877662e9ca)

## Other CS2 admin tools
- **Conter-Strike 2 RCON tool:** https://github.com/fpaezf/Counter-Strike-dedicated-server-admin-tool

- **Conter-Strike 2 RCON tool on Reddit:** https://www.reddit.com/r/cs2/comments/1ev8s5q/counterstrike_dedicated_server_remote_admin_tool/

