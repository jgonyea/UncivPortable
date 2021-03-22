# General note about the App directory

This directory contains files used by the portable app.
They should generally not be accessed directly by users.

User data or settings should not be stored within the App
directory or its sub-directories.  Any data stored here
will likely be deleted on upgrades.

# Specific Note about Unciv Data

All Unciv data lives next to its executable jar in the App directory due to how Unciv was built.

This data (game saves, music, mods, GameSettings.json, etc.) is not expected to be lost during an upgrade.  Future releases of this portable app may move this data to a more PAF-compatible location (`UnCivPortable\Data` folder).
