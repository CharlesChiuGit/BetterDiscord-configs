# BetterDiscord-configs

## Customize my Discord

1. Download [BetterDiscord](https://betterdiscord.app/)
2. Install it and restart Discord.
3. Go to **Settings > BetterDiscord > Plugins** and open the folder.
4. Put all the **.plugin.js** files of this repo to that folder.
5. Press **Ctrl + R** to reload all the plugins and start setting those plugins.
6. (Optional) If u have problem setting your Discord open while Windows boots up, try following tips **in order**:
   - Go to **Discord > Settings > Windows Settings**, make sure the "Open Discord" is on.
   - Press **Crtl+Shift+Esc** to open _Task Manager_, go to "Startup" tab, check if Discord is enabled, left click to change the "Status".
   - Quit Discord, go to **C:\Users\USER_NAME\AppData\Roaming**, search for "discord" or "Discord" folder, rename the folder to "discord_backup". (If anything goes wrong, rename the folder back.)
   - Restasrt. Discord should automaticlly open up. If everything is normal, u can now delete the "discord_backup" folder.
     - Also u can open _Registry Editor_, go to **Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Run**, and check if Discord is in it, and the "Data" is **C:\Users**\USER_NAME **\AppData\Local\Discord\Update.exe --processStart Discord.exe**.
     - **Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run** is another place to check.
