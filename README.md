# TIS-100 Solutions

## Directory for save files

Find the `TIS-100` folder for your system. Some potential folder paths are listed below. In the `TIS-100` folder there are sub-directors for managing the users/players/accounts for different save data. If there's more than one, you will need to determine which is the correct directory on your own by peeking into the save files in the `save` folder. Once you Determin which sub-directory 

| System | Location |
| ------ | -------- |
| Windows | `"%USERPROFILE%\Documents\My Games\TIS-100"` |
| macOS | `$HOME/Library/Application\ Support/TIS-100` |
| Linux | `~/.local/share/TIS-00` |
| Linux | `$XDG_DATA_HOME/TIS-100` |

## Install

1. Quit TIS-100 if it's running.
2. Get to the correct `TIS-100` directory for your system (table above).
3. Find the correct sub-directory (based on user/steam account, or just checking save contents).
4. Backup the `save` folder (if desired), then delete/move/rename it.
5. Run `git clone git@github.com:MatthewWritesCode/TIS-100-Solutions.git save`.
6. Run the game!
