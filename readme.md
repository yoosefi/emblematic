# emblematic

Nemo scripts to backup/restore folder emblem settings inside the folders themselves.

Emblems are backed up to a file called `.emblems~` in each directory.

## scripts

- `backup`: Recursively saves current `gio` emblem metadata of selected dirs (or current dir if none selected) to a corresponding `.emblems~` backup file.

- `restore`: Recursively reads each `.emblems~` file in selected dirs (or current dir if none selected) and applies them via `gio`.

- `x-clear-active-x`: Clears the active emblems of selected folders (non-recursive), leaves backup files alone.

- `x-wipe-backups-x`: Recursively removes backups from selected dirs (or current dir if none selected). Asks for confirmation.

