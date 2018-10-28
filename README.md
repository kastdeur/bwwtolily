Convert Bagpipe Reader to Lilypond
==================================

This is a utility to convert a .bww or .bmw file to a [lilypond](https://lilypond.org) parsable file.
Not all of the embellishments get converted properly, this is espessially true with piobaireachd, 
and the program will list the embellishments that were not converted.

If you recognize an embellishment that isn't being parsed, please 
create an [issue on github](https://github.com/kastdeur/bwwtolily/issues)

usage:
```
$ bwwtolily /path/to/a/bww/file
```

optionally, using the "-l" flag will try to run lilypond on the
created .ly file
example:
```
$ bwwtolily  /path/to/bww/file -l
```
