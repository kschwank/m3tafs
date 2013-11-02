m3tafs
======

A python fuse, dynamically using media files metadata to create a directory structure.
The finished version is intended to allow for example:

to filter the media collection using metadata values:
<pre>
$ cd year:2001-2003
$ cd artist:Some_Artist
</pre>

and to modify metadata by moving files
<pre>
$ mv artist:Some_Artist/* artist:Some_other_Artist/
</pre>

##Note: This is pre-alpha code, not working at all yet!

to mount m3tafs do:
<pre>
$ ./m3tafs mediaCollection mountPoint
</pre>
