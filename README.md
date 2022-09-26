# man-dirs

This repo will hopefully contain descriptions for various files and directories in Ubuntu and in common Linux systems in general.

## Format

* A description for a file `/path/to/file` on the system will be in `path/to/file.mandir`
* A description for a directory `/path/to/dir/` on the system will be in `path/to/dir/.mandir`

The reason for this convention is so that the description files themselves can be integrated into the system path, so if one encounters an unknown file or directory, the .mandir file can be easily searched for in the same place.

For pseudo file-systems (like /proc and /sys) it's impossible to keep the .mandir file in the system path, so we will need to find a solution for those.
