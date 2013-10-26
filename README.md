Drag(*)nBall Z: Epic Scripts
=========

configs.tin: all of your default #config settings
aliases.tin: all of your default #alias settings
triggers.tin: all of your default #trigger settings
connection.tin: the connection/session for the mud
defaults.tin: loads all of the default files, and gets linked in a race/character specific file
dbz-epic-human.tin: this is what you run when you want to play a human

Usage example: tt++ dbz-epic-human.tin

The idea is that you will have one file for each race, and those are the files you actually run with TinTin. All of the other files are your generic aliases, configs, triggers, etc. I load all of them within defaults.tin, and defaults.tin gets loaded in each of the individual race files. If you do want a custom trigger for say, only a saiyan, add that to the dbz-epic-saiyan.tin file.

I'll refine this more later.
