Forked from http://sourceforge.net/projects/p7zip/

p7zip_explode
=============

Modified version of p7zip which supports archive exploding, that is, creating a new 7z archive for each of an archives blocks.

Use command line p for exPloding.

If a block only has a single file, the resulting 7z archive is named according to the contained file.
If there are various files in the block, the resulting archive is given a generic name of type: original_archive.7z_folderx.7z

To build:
cd CPP/7zip/Bundles/Alone
make -B

output in p7zip_explode/bin

Usage example
./7za p archive.7z

Outputs relative to the working directory at the moment. Use -o switch to change. 
