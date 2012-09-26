SC2 Replay Auto-Renamer
========================

SC2 Replay Auto-Renamer (SC2RAR) is a an app that resides in your tray area and watches a folder and renames any newly added replays. 
This means that as soon as you finish a Starcraft II game it will rename the replay from the standard Date/Time format to a more sensible one.

How-to:
--------
* Extract the SC2RAR folder to a location of your choice.
* Start SC2RAR.exe
* Point the folder dialog to the folder you want to watch (usually 'Starcraft II\Replays\Recent\')

Features:
-----------
* Watches a folder (and any sub-folders) and automatically renames replays as they appear
* GUI for choosing format (including a preview function for creating dynamic formats)
* Renames replays from all languages
* Choice of multiple pre-set formats
* Dynamic format for those who want more control
* Optional moving of you (and your teammates) to the front/back of the replay name.

Output:
------------
The replay will be renamed in a format of your choice.
This is an example of the 'Normal' format: 'Player1(P) vs Player2(Z) on Kulas Ravine[FFFFFFFF].SC2Replay'.
The code at the end is there to give a unique name to each replay. (Its a CRC32 based on some replay information)