# UMD-replace_x64
A modified version of UMD-REPLACE by CUE that supports PS2 DVDs as well. The latest version of UMD-REPLACE had PS2 DVD support by surprise, but the tool would only work with ISO images below 4GB in size. This version corrects that, making it compatible with PSP ISOs, PS2 DVD-5 ISOs, as well as only the layer0 of PS2 DVD-9 ISOs.

# Author
Copyright (C) 2012-2015 CUE  
Copyright (C) 2022 Snake128

# Use

Usage: UMD-REPLACE imagename filename newfile

- 'imagename' is the name of the ISO image
- 'filename' is the file in the ISO image with the data to be replaced
- 'newfile' is the file with the new data

* 'imagename' must be a valid UMD/PS2 ISO image
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
  - fixed to use files larger than 4GB
