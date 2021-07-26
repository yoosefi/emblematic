# emblematic

Nemo scripts to backup/restore folder `gio` metadata for icons and emblems inside the folders themselves.

Emblems are backed up to a file called `.emblems~` in each directory.
Custom icons are backed up to `.custom-icon~` in each directory.

## scripts

- `backup`: Recursively saves current `gio` emblem metadata of selected dirs (or current dir if none selected) to corresponding metadata backup files.

- `restore`: Recursively reads each metadata backup file in selected dirs (or current dir if none selected) and applies them via `gio`.

- `x-clear-active-x`: Clears the active icons and emblems of selected folders (non-recursive). Leaves backup files alone.

- `x-wipe-backups-x`: Recursively removes metadata backup files from selected dirs (or current dir if none selected). Asks for confirmation.

