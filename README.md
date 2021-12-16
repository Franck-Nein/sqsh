# sqsh

Poorly done script to easily compress a file or folder using mksquashfs with (probably) the best compression ratio(still needs more testing).

By default, the output file will be created on your current directory using the name of your target + .sqsh unless you specify an output file, it will overwrite it if it already exists.

## Usage

Currently, the only options are Input and Output, input can be either a file or a directory.
Examples:
```
sqsh file.txt
```
Will create file.txt.sqsh
```
sqsh directory/
```
Will create directory.sqsh
```
sqsh directory archive
```
Will create archive.sqsh
```
sqsh directory/subdirectory
```
Will create directory-subdirectory.sqsh (This probably should be changed, but i couldn't think of a better solution)
```
sqsh directory/subdirectory directory/output
```
Will create directory/output.sqsh
