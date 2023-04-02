# WinTerminalProfiles
These are my user-specific configuration files that I use to personalize my Windows experience.

### Starship
Placed under C:\Users\USERNAME\.config

### Windows-Terminal-Settings
Placed under %LOCALAPPDATA%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState

### Launch in QuakeMode
* Open Windows Terminal and press Ctrl+Shift+P to open the Settings menu.
* In the search bar, type quake to find the Quake mode settings.
* Set "quakeMode": true to enable Quake mode.
* Set "newTabMode": "dropdown" to have the terminal open in a dropdown tab.
* Close Windows Terminal and open the Start menu.
* Type %APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup in the search bar and press Enter.
* Right-click in the folder and choose "New > Shortcut".
* In the "Type the location of the item" field, enter the following command:
* ``` wt ; new-tab -p "Windows PowerShell" -d "%USERPROFILE%" ```
* This will open Windows Terminal in Quake mode, with a new tab open to the Windows PowerShell shell and the working directory set to your user profile directory.
* Click "Next" and give the shortcut a name, such as "Windows Terminal (Quake mode)".
* Click "Finish" to create the shortcut.
* Now, every time you log in to your Windows account, Windows Terminal will launch automatically in Quake mode with the specified settings.