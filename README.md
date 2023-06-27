# OnlineStatusChanger

This plugin was developed to handle a GUI method of changing a user's in-game status.
Due to how textboxes need to work in BakkesMod, the game would crash any time an edit was made.
This adds a temporary cvar textbox, then applies the temp string to the final cvar when the user clicks Apply.

# How to Fix the blocked plugin

1. Replace `OnlineStatusChanges.dll` in `%APPDATA%\bakkesmod\bakkesmod\plugins` with the new one in the root of this project.
2. Replace `OnlineStatusChanger.set` in `%APPDATA%\bakkesmod\bakkesmod\plugins\settings` with the one in `OnlineStatusChanger` directory.
