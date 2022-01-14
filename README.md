# yuri's editor make edit context menu easy!

Now, you don't need open the registry to edit elements in context menu, just open yuri's editor!

You can add or remove items via listbox. If program couldn't delete element, you can try again with SYSTEM\TrustedInstaller rights

HotKeys:  
H - Opens supported hotkeys  
R - Restarts Form, withnot restart program  
S - Search (ctrl + S - closes search, if the field is empty)  
B - Starts copying HKCR, HKCU, HKLM subkeys on the desktop  
T - Changes the app theme (Light or Dark)  
D - Developer mode. You can remove any SubKey with SYSTEM\TrustedInstaller rights. All warnings will be removed.  

Context Menu Editor & Tweaker! Click on "Editor" or "Tweaker" label to change the panel  

Supported arguments:  
/clean - Launches clean-up methods (or use right click on apply button in the program)  
/cmd - Launches cmd with SYSTEM\TrustedInstaller rights  

Example: "C:\Folder\yuri's editor.exe" /clean

# Version 1.4.1.1 (A small update)  
- Now, you can't uses russian symbols in the "Hex" textbox  
- if you written <6 symbols in "Hex" textbox, you doesn't see exception, but if you enter the wrong #color, you will be notified about it  
- Fixed exception, when you closed program and see "Couldn't find part of the path...". It is cleaning up check update methods (please, don't close the program until notification about "An update available" doesn't closed)   

# Version 1.4.1

- Added auto checks updates feature (the third checkbox in Settings)
- Updated tab key movement
