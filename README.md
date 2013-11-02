m3tafs
======

A python fuse dynamically using media files meta data to create a directory structure.
The finished version is intended to allow for example:

to filter the media collection using metadata values:
cd [year:2001,year:2003]
cd [artist:"Some Artist"]

and to modify metadata by moving files
mv * [artist:"Some other Artist"]
