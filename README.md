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

# Version 1.4.4.8
- Updating the program now preserves the previous position  
- Fixed displaying the size of deleted files via the /clean argument  
- Fixed closing the program when the value in the registry "Lang" is incorrect in the Russian version of the program

# Version 1.4.4.7
- Accelerated cleaning  
- Redesigned the Microsoft spy verification method

# Version 1.4.4.6
- The program remembers its name after the update  
- Fixed the location "Returned" and "Reboot required" for a scale greater than 100  
- Fixed the size of the Settings window in Developer mode

# Version 1.4.4.5
- Fixed localization for elements used multiple times

# Version 1.4.4.4
- Added text to the Search textbox  

# Version 1.4.4.3
- Full support Windows DPI > 150 & 175  
- The text of the button [...] should be centered  
- Slightly accelerated code  

# Version 1.4.4.2
- Accelerated program launch

# Version 1.4.4.1
- Now the program does not close if the values in the registry are broken  

# Version 1.4.4.0
- Now the Settings appear in the center of the application, not the screen  
- Added the possibility of hot language replacement (Russian, English)  
- Now the program language is remembered in the registry  
- Added full Windows scale support  

# Version 1.4.3.9
- Fixed program blurring at scale > 100  
- Fixed notification appearance at scale > 100  

# Version 1.4.3.8
- All texts have been transferred to the dictionary. This simplifies the translation in the future. If you want to help translate the program into your language, write to Me about it, the contacts are listed in the profile.  
- Fixed changes in the highlighted text color when applying a tweak.

# Version 1.4.3.7
- Fixed loss of focus when opening settings  
- Changed the color of the light theme  
- Accelerated change of the application theme  
- Now, when adding an extension, you do not need to write the first dot  
- Added additional text in the add extension mode  

# Version 1.4.3.6
Now you can edit the Create (New) menu!

How this work:  

- How does the program understand if there is an extension in the create menu:  
The program checks whether the extension has (as an example, I'll take .txt) inside the ShellNew branch, if yes, then looks to see if there is an ItemName or FileName value, if there are no such values, the item will not appear in the list (Which means it is not in the create menu).  

- When you click "Add":  
In the textbox of the "name", specify the extension, for example .txt (it is possible without a dot), if you just want to add this extension, then click "Add", if you know what you are doing, then specify "paths" in the textbox: @C:\Windows\system32\notepad.exe,-470.  
That is, if you add an element with an empty field to the "paths" textbox. The program will create an empty FileName value in the branch .txt\ShellNew.
If you have written something in the "paths" textbox, the program will create the ItemName value in the branch.txt\ShellNew. (This means that if you write something incorrectly, the item will not appear)  

- When you click "Edit":  
The program checks whether the extension has (as an example, I'll take .txt) the value of ItemName, if yes, then you can see the "paths" in the textbox field: @C:\Windows\system32\notepad.exe,-470  
If there is no such value, the field will be empty (FileName value)  

- When you click "Remove":  
Since it's not cool to demolish extensions, the program deletes the values: ItemName and FileName in the extension you selected.  

Export works for extensions that are in the create menu, so I recommend that you Export before you do something  

Keep in mind, all this applies to the branch: HKEY_CLASSES_ROOT.  
If the items are registered in HKLM\SOFTWARE\CLASSES, they will not be displayed in the program.  

# Version 1.4.3.5
- Fixed the discrepancy between the light theme in applications and settings  
- Fixed the abrupt disappearance of the program when collapsing  
- For a light theme, opacity was increased  
- Added smooth animation of changing the application theme

# Version 1.4.3.4
- Fixed the calculation of the weight of files in the temp folder

# Version 1.4.3.3
- The program no longer closes if some kind of "protection" prevents cleaning  
- Fixed updating the list if you didn't select the import file  
- Now, when you select an icon you can choose: display only icons or all files in the selection menu

# Version 1.4.3.2
- Fixed tweak return for Grant Access  
- Now the Print item is removed for png, jpg and the like

# Version 1.4.3.1
- Removed the focus from the Export button when the program starts  
- The Export and Import panel began to move more smoothly

# Version 1.4.3
- Fixed a typo in the help (H)

# Version 1.4.2.5
- Removed the bold stripes on the buttons, when pressed  

# Version 1.4.2.4
- Added branch: Directory\Background  
- Now the Enter button is responsible only for the Search (S)  
- Now you can't apply tweaks or start a new cleaning until the cleaning is finished  
- Fixed Missing icon when adding an element  
- Now you can roll back the selected icon without restarting the program  
- Added the function of changing an existing branch.  
P.S. PLEASE NOTE THAT IF YOU RENAME A BRANCH, ONLY THE RENAMED BRANCH AND THE KEYS NESTED IN IT WILL BE MOVED, THE REST WILL BE DELETED!!!

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
