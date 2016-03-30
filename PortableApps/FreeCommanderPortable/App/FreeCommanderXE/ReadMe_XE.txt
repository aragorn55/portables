================================================================================
WHAT IS FreeCommander
================================================================================
FreeCommander is an easy-to-use alternative to the standard Windows file manager. 
You can configure almost everything. Supported Windows versions: Windows XP and above.
FreeCommander XE is in two versions 32 and 64 bit. 
Please check the info about using FreeCommander XE 32 bit on 64 bit Windows http://freecommander.com/en/version-summary/    



================================================================================
AFTER YOU HAVE INSTALLED FreeCommander XE
================================================================================

If you have worked with the FreeCommander 2009.02b:
- the settings of the FreeCommander 2009.02b are not compatible with the settings of the FreeCommander XE
- do not copy the old settings to the new settings folder

If you have worked with the FreeCommander XE 32 bit version and now you want use 64 bit version
- the settings are compatible; you can use the settings from the 32 bit version in the 64 bit version
- for moving the settings you can use Tools->Backup all settings, Tools->Restore all settings


The available help files you can download from the site http://freecommander.com/en/languages/  

Trouble with the help file
==========================
When viewing your CHM documentation, Microsoft's HTML Help Viewer is showing an error page saying either that:
 - The action has been canceled 
 - The page cannot be displayed
 
Solutions
 - Launch help file from local drive and not from a network path or via a mapped networked drive.  
 - Make sure your help file isn't in a path with symbols such as "#" (sharp).  
 - In some cases, you can have access to an "unblock" button in the properties page of the help file. Right click on the file then go to its properties and click the "unblock" button. This button is not available in all systems though. 
 - Try the HHReg utility http://www.ec-software.com/products_hhreg.html or read this technical note from the Microsoft Knowledge Base http://support.microsoft.com/kb/896054/.

================================================================================
FEEDBACK & SUGGESTIONS
================================================================================

Direct your feedback, suggestions and bug reports to the FreeCommander forum http://www.forum.freecommander.com
or directly to me marek@freecommander.com but please do not expect that you get an answer immediately :). 


I hope you will enjoy FreeCommander 

MAREK JASINSKI


================================================================================
Important changes and bug fixes in the release 686
================================================================================
- Bug fix: Display issue if Windows font size changed to bigger as 100% http://www.forum.freecommander.com/viewtopic.php?f=7&t=6439
- Bug fix: Pack files function fails if the source or target path is the desktop
- Implemented: New option for quick filters - 'Predefined quick filters'
- Implemented: New actions for predefined quick filters - for example: Show popup menu for quick filters
- Implemented: New option to define in the freecommander.ini - 'PrefixForBackupSubfolderNames', the default value is 'Bkp_Settings_'
- Implemented: New favorite tool option - 'Delimiter character for selected items - space is default' and 'Enclose each selected item with "'  
- Implemented: New favorite tool parameter 'Selected items as drag&drop' - %ActivSelAsDrag&Drop%
  
================================================================================
Important changes and bug fixes in the release 687
================================================================================
- Bug fix: Filter for "attributes off" works not properly http://www.forum.freecommander.com/viewtopic.php?f=18&t=6444
- Bug fix: Synchronize - option for "delete empty folders" no more available
- Bug fix: "Go to folder" - selected folder is appended to the existing text http://www.forum.freecommander.com/viewtopic.php?f=7&t=6481
- Changed: The default sort direction for date and size (started per hotkey Ctrl+F5, Ctrl+F6) changed to descending
- Implemented: New option to define in the freecommander.ini in the Section [dlgInputBox]: AutoComplete=0. With AutoComplete=1 will be auto completion activated in e.g. "Go to folder", "New folder" dialogs.
- Implemented: DOS-Prompt specification - now %ActivDir% variable is enabled
- Implemented: Default column profile works with network shares too
- Implemented: All history sections transfered to the new freecommander.hist.ini
- Implemented: "Make folder/file list" function implemented   
              
================================================================================
Important changes and bug fixes in the release 688
================================================================================
- Bug fix: New file created with Shift+ctrl+N is not selected automatically  http://www.forum.freecommander.com/viewtopic.php?f=19&t=6491
- Bug fix: "Make folder/file list" dialog can not be closed http://www.forum.freecommander.com/viewtopic.php?f=7&t=6499
- Bug fix: Wrong dialog title for move operation http://www.forum.freecommander.com/viewtopic.php?f=7&t=6498
- Bug fix: "Use FreeCommander" option for move operation may be ignored http://www.forum.freecommander.com/viewtopic.php?f=7&t=6497
- Bug fix: Command line parameter with the switch "/" may not work properly, the switch "-" works ok
- Bug fix: Multiple Selection is wrong after sorting selected list http://www.forum.freecommander.com/viewtopic.php?f=19&t=6504

================================================================================
Important changes and bug fixes in the release 689
================================================================================
- Bug fix: "Define shortcuts" dialog can not be opened (exception)

================================================================================
Important changes and bug fixes in the release 690
================================================================================
- Bug fix: Status bar fields - incorrect folder count on selection   http://www.forum.freecommander.com/viewtopic.php?f=22&t=6535
- Implemented: Start filter mask with "-[]:" if you want use [] as literals http://www.forum.freecommander.com/viewtopic.php?f=22&t=6521
- Implemented: Define "RightClickEmptySpaceFcMenu=0" in the freecommander.ini [Form] section, if you like show the default context menu on free space right click
- Implemented: New option added; Customize toolbars - General options: Use flat symbols

================================================================================
Important changes and bug fixes in the release 691
================================================================================
- Bug fix: Multi-rename search and replace always excludes extension : http://www.forum.freecommander.com/viewtopic.php?f=7&t=6540  
- Bug fix: "Auto rename copied files" option not working     http://www.forum.freecommander.com/viewtopic.php?f=19&t=6595
- Bug fix: Selected item position will be changed after refresh in the file list with detail view http://www.forum.freecommander.com/viewtopic.php?f=19&t=6613 
- Bug fix: Directory loading can be cancelled with ESC if the application is not active
- Implemented: Basic long path support
- Implemented: "Windows preview" mode in the internal viewer added (no plugins needed for pdf and all office documents). It works starting with Vista.

================================================================================
Important changes and bug fixes in the release 692
================================================================================
- Bug fix: New folder from empty space context menu can create wrong folder:   http://www.forum.freecommander.com/viewtopic.php?f=19&t=6659
- Bug fix: Tab - Context menu lost http://www.forum.freecommander.com/viewtopic.php?f=22&t=6674&sid=c550fd5c361aa2d61c6e16def009009c
- Bug fix: "My Documents" shows twice in the S-button http://forum.freecommander.com/viewtopic.php?p=21294#p21294
- Implemented: "Download" folder added to S-button (Vista+)
- Implemented: New address bar option added "Show history popup menu on free area click"
- Implemented: Action "Show/hide folders" added http://www.forum.freecommander.com/viewtopic.php?f=6&t=6675
- Implemented: New column for using in detail view added: Length of the path
- Implemented: Synchronize folders - for "Site backup": New Option added "copy - rename target item"
- Implemented: Synchronize folders - hotkeys for changing of the copy status added

================================================================================
Important changes and bug fixes in the release 693
================================================================================
- Bug fix: Exception on program start possible (not all PCs)

================================================================================
Important changes and bug fixes in the release 694
================================================================================
- Bug fix: Snchronization on Network Share does not work if Network option "Use Windows for loading network" is active
- Bug fix: Space bar opens always next file in viewer http://www.forum.freecommander.com/viewtopic.php?f=18&t=6745
- Bug fix: "Use current folder" option is not active if archive file is open in the target site  http://forum.freecommander.com/viewtopic.php?f=19&t=6358
- Bug fix: Favorites tree font size grows if settings are saved - only if Windows font is set to value > 100%  http://www.forum.freecommander.com/viewtopic.php?f=22&t=6707&p=21605#p21605
- Bug fix: Synchronize folders - exception "List index out of bounds" possible if option for empty folder is active       
- Implemented: File rename possible if quick viewer open.
 
================================================================================
Important changes and bug fixes in the release 695
================================================================================ 
- Bug fix: Copy and paste in textbox of address bar may not work http://www.forum.freecommander.com/viewtopic.php?f=19&t=6819
- Bug fix: Exception in viewer for jpg files with size 0
- Bug fix: Selection problem in the NC-Mode http://www.forum.freecommander.com/viewtopic.php?f=6&t=6798
- Bug fix: Some check boxes and radio buttons broken in Settings in the release 694 http://www.forum.freecommander.com/viewtopic.php?f=7&t=6813
- Changed: Attributes/Timestamp dialog - 'Move timestamp' editing changed

================================================================================
Important changes and bug fixes in the release 696
================================================================================ 
- Bug fix: Copy/move folder does not work if the tree has focus 
- Bug fix: Favorites tree - icons are not displayed for items with placeholder in the path   http://www.forum.freecommander.com/viewtopic.php?f=18&t=6861 
- Bug fix: Option "auto rename target item" in the synchronize dialog doeas not work http://www.forum.freecommander.com/viewtopic.php?f=7&t=6835&p=21974#p21974
- Bug fix: File selection problem in NC-mode http://www.forum.freecommander.com/viewtopic.php?f=22&t=6870
- Bug fix: Multi rename may not work properly if files and folders should be renamed in one step http://www.forum.freecommander.com/viewtopic.php?f=7&t=6880
- Changed: Converter in viewer - target file extension is now definable.
- Implemented: new option "GoUpFromDriveEnabled"; default value is 1 (true). Set the value to 0 if you do not want go to parent from the drive root.
- Implemented: favorite tool option  'Enclose each selected item with "' for %InactivDir% %ActivDir% http://www.forum.freecommander.com/viewtopic.php?f=7&t=6871 

================================================================================
Important changes and bug fixes in the release 697
================================================================================ 
- Bug fix: Layout of the delete dialog is faulty http://www.forum.freecommander.com/viewtopic.php?f=6&t=6884
- Bug fix: Tools - Settings - Programs: bottom scroller is partially cutted out on all tabs http://www.forum.freecommander.com/viewtopic.php?f=6&t=6884

================================================================================
Important changes and bug fixes in the release 698
================================================================================ 
Bug fix: Quick filter field not correctly displayed on high dpi monitor http://www.forum.freecommander.com/viewtopic.php?f=7&t=6892
Bug fix: Quick starter search text input field not correctly displayed on high dpi monitor http://www.forum.freecommander.com/viewtopic.php?f=7&t=6895
Bug fix: Unpack dialog - status bar not correctly displayed on high dpi monitor http://www.forum.freecommander.com/viewtopic.php?f=7&t=6900
Bug fix: Search dialog - delete key deletes converter instead of text http://www.forum.freecommander.com/viewtopic.php?f=7&t=6912 
Implemented: "Unpack in subfolder" option is saved now
Implemented: Drag&drop to drive bar start copy operation to root folder of the drive
Implemented: Drag&Drop to folder as favorite tool start copy operation to the folder 
Implemented: Drag&drop to favorite folder in the tree start copy operation to the folder

================================================================================
Important changes and bug fixes in the release 700
================================================================================ 
Bug fix: "Right align extension" option may not work http://www.forum.freecommander.com/viewtopic.php?f=7&t=6917
Bug fix: Unpack operation does not work when not allowed characters exist in the path  http://forum.freecommander.com/viewtopic.php?f=19&t=6904
Bug fix: Font color of selected node in the tree broken http://www.forum.freecommander.com/viewtopic.php?f=7&t=6932     
Implemented: New option for text thumbnails - Font Size
Changed: "Attributes/Timestamp..." dialog layout changed

================================================================================
Important changes and bug fixes in the release 702                              
================================================================================
Bug fix: Right align extension problem http://www.forum.freecommander.com/viewtopic.php?f=7&t=6938
Bug fix: Exception on drop operation on favorite toolbar http://www.forum.freecommander.com/viewtopic.php?f=19&t=6947
Implemented: Right click with the pressed control key changes the meaning of the option RightClickEmptySpaceFcMenu 
Implemented: Option "OpenItemsWarningItemsCount=2" to define in the [Form] section of the freecommander.ini (default value 2). 
             If you do not like the warning message for opening of multiple files, then increase the value.   
Implemented: Last used plugin for the pack operation will be saved
Implemented: New option added, Settings->View: Change splitter color if content is not visible
Implemented: Basic FTP functions 

================================================================================
Important changes and bug fixes in the release 703                              
================================================================================
Bug fix: Right align problem http://www.forum.freecommander.com/viewtopic.php?f=6&t=6983

================================================================================
Important changes and bug fixes in the release 704                              
================================================================================
Bug fix: Rename problem in the tree http://www.forum.freecommander.com/viewtopic.php?f=19&t=7019
Bug fix: Some FTP bugs fixed 
Implemented: AND operator for quick filter implemented: \&
Implemented: Full screen state (F11) will be saved
Implemented: New command added - actViewQuickViewSetFocus: Set focus to quick view panel; Activate quick view panel
Implemented: New sorting commands added (site specific) - now you can use sorting buttons in address bar and they show proper state; You should use the normal sorting commands - without "left" or "right" suffix. 
 
================================================================================
Important changes and bug fixes in the release 705                              
================================================================================
Bug fix: Target file name can not be changed if pack one file http://www.forum.freecommander.com/viewtopic.php?f=7&t=7026
Changed: Options for subfolder filter in the search dialog

================================================================================
Important changes and bug fixes in the release 706                              
================================================================================
Bug fix: Layout with the tree does not set the proper width of the tree

================================================================================
Important changes and bug fixes in the release 707                              
================================================================================
Bug fix: FTP upload broken

================================================================================
Important changes and bug fixes in the release 708                              
================================================================================
- Bug fix: Exception by Alt+V if "Compare folders" option "Show dialog with options" is active and Windows font is set to 200%  
- Changed: Search dialog - "Use for full subfolder path (otherwise only for subfolder name)" possible for folder filter 
- Implemented: Search dialog - fast attribute filter is possible in field "File name:" (see the hint to the field) 
- Implemented: Search dialog - selected items are preserved when sorting

================================================================================
Important changes and bug fixes in the release 709                              
================================================================================
- Bug fix: Save current layout broken

================================================================================
Important changes and bug fixes in the release 710                              
================================================================================
- Bug fix: Locked tab will be unlocked if the locked path is not available
- Bug fix: FTP - TLS can not be defined http://www.forum.freecommander.com/viewtopic.php?f=22&t=7077
================================================================================
Important changes and bug fixes in the release 711                              
================================================================================
- Bug fix: Exception on program start if program was closed with only right panel

