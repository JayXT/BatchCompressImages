# BatchCompressImages
A simple ImageMagick-based script for compression of all images in a directory.

A couple of common image formats like jpg, png have been taken into consideration.
Script compresses images in the current directory using ImageMagick `convert` command.
The default quality level is 30, but a number suppplied as a first argument can override it.

The algorithm doesn't replace existing files, instead it creates files with the same name, but with added "_compressed" suffix.
All files containing "_compressed" substring are skipped.

The script has been tested in Debian 12.
