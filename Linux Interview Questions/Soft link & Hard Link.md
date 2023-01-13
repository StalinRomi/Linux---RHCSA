## Hard Link ->

Hard link have **actual file contents**.
Modifying / Deleting the newly created file will **not** have any effect on original file.

**ln** file name

## Soft link ->

Soft Link contains the **path for original file** and not the contents.
Modifying / Deleting the newly created file will have any effect on original file

**ln -s** file name
