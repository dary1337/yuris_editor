# yuri's editor make edit context menu easy!

Now, you don't need open the registry to edit elements in context menu, just open yuri's editor!

You can add or remove items via listbox. If program couldn't delete element, you can try again with SYSTEM\TrustedInstaller rights

HotKeys:  
H - Opens supported hotkeys  
R - Restarts Form, withnot restart program  
S - Search (ctrl + S - closes search, if the field is empty)  
B - Starts Exporting your registry branches (Context Menu)  
T - Changes the app theme (Light or Dark)  
D - Developer mode. You can remove any SubKey with SYSTEM\TrustedInstaller rights. All warnings will be removed.  

Context Menu Editor & Tweaker! Click on "Editor" or "Tweaker" label to change the panel  

Supported arguments:  
/clean - Launches clean-up methods (or use right click on apply button in the program)  
/cmd - Launches cmd with SYSTEM\TrustedInstaller rights  
/fwd - Kills Windows Defender without regret

Example: "C:\Folder\yuri's editor.exe" /clean (or -clean)

# Version 1.4.3
- Fixed a typo in the help (H)

# Version 1.4.2.5
- Removed the bold stripes on the buttons, when pressed  

# Version 1.4.2.4
- Added branch: Directory\Background  
- Now the Enter button is responsible only for the Search (S)  
- Now you can't apply tweaks or start a new cleaning until the cleaning is finished  
- Fixed: Missing icon when adding an element  
- Now you can roll back the selected icon without restarting the program  
- The function of changing an existing branch HAS BEEN added.  
P.S. NOTE THAT IF YOU RENAME A BRANCH, ONLY THE RENAMED BRANCH AND THE KEYS NESTED IN IT WILL BE TRANSFERRED, THE REST WILL BE DELETED!!!

# Version 1.4.2.3
- The program no longer freezes on cleaning  
- Added an indicator that the program clears  
- Now you can't run more than 1 cleanup at once

# Version 1.4.2.2
- Now the B key is responsible for Exporting  
- Now you can't run 2 Exports at once

# Version 1.4.2.1
- Export of ALL registry branches has been cut out  

# Version 1.4.2
- Fixed missing shadow for Windows 11  
- Fixed, the program did not read the UAC tweak  
- Added argument: /fwd (Be careful, this key erase your Windows Defender without recovery!)  
- Added Import and Export buttons bottom right  
- Added event by clicking the middle and right mouse button on Additional settings  

# Version 1.4.1.3
- Fixed exception: "The process cannot access the file...", when you tried to check for updates after running the program with the check box "Check for updates at startup"  
- Fixed closing program, when you try check for updates without internet connection  
- Now, you won't see DOS windows anymore

# Version 1.4.1.2
- Added edge support in Windows 11  
- Added animation of buttons (Close, collapse) at startup  
- Now, auto-update does not hang when checking  
- Fixed "Click on notification" events  
- Added automatic replacement of arguments with a dash, instead of slash  

# Version 1.4.1.1
- Now, you can't uses russian symbols in the "Hex" textbox  
- if you written <6 symbols in "Hex" textbox, you doesn't see exception, but if you enter the wrong #HexColor, you will be notified about it  
- Fixed exception, when you closed program and see "Couldn't find part of the path...". It was cleaning up the update checking methods

# Version 1.4.1
- Added auto-update feature (the third checkbox in Settings)  
- Updated tab key movement
