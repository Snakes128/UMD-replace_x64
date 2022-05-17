# UMD-replace_x64
A UMD-replace for files more than 4gb

# Author
Copyright (C) 2012-2015 CUE

# Use
UMD-REPLACE is a tool to replace data files in a PSP UMD ISO image and a PS2 ISO game.

Usage: PSP/PS2-REPLACE imagename filename newfile

- 'imagename' is the name of the UMD image
- 'filename' is the file in the UMD image with the data to be replaced
- 'newfile' is the file with the new data

* 'imagename' must be a valid UMD ISO image
* 'filename' can use either the slash or backslash
* 'newfile' can be different size as 'filename'

Source code and executable files are included, with GNU General Public License.

# History
version 2012-10-25
------------------
  - first public version

version 2013-03-15
------------------
  - solved a bug in the total sectors

version 2015-03-03
------------------
  - 64bits offsets to use files larger than 2GB

version 2022-05-17
------------------
  - fixed to use files largen than 4GB
