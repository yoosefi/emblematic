# emblematic

Nemo scripts to backup/restore folder emblem settings inside the folders themselves.

Emblems are backed up to a file called `.emblems~` in each directory.

## scripts

- `backup`: Recursively saves current `gio` metadata of selected folders to a corresponding `.emblems~` backup file.

- `restore`: Recursively reads each `.emblems~` file and applies the metadata to its folder via `gio`.

- `x-clear-x`: Clears the active emblems of selected folders (non-recursive), leaves backup files alone.
