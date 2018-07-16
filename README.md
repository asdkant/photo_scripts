# photo_scripts
Some scripts I made related to photography (mostly SD card / raw files management)


### newdir
**made in:** `bash`

**what it does:**
> Creates a new directory in the mounted SD card if the last one is not empty.
> You can pass the path of the SD card as an argument, if not it looks at the 
> current working directory.
>
> Assumes the [DCF standard](https://en.wikipedia.org/wiki/Design_rule_for_Camera_File_system)
> for the directory names.


### rdr
**made in:** `python`

**requires:** I think nothing besides the usual python distro

**what it does:**
> Adds a prefix to raw files indicating the date in `YYYY-MM-DD` format. You 
> can give it a list of files, but most likely you'll want to use shell glob
> patterns (for example: `rdr *.RAW`)
