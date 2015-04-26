# Sublime Text 3 support for "Positive" DSLs
## XP and CO
There are two twin-mini-languages, say XP and CO, used to describe normalization instructions and correlation rules in the PTSIEM platform. This project implements Sublime Text 3 syntax definition and some settings for them.

Folders info:

### src
Source files in YAML format. They are to be converted to TM-PList with AAAPackageDev. TM-PList is a PropertyList format used by TextMate and Sublime Text.

### built_stuff
Files that ready for copy-to-use. Just copy them to the `Packages\User` directory (relative to ST3-AppData) and restart ST.

> hint: ST3 menu: `Preferences -> Browse packages...` opens the path `%appdata%\Sublime Text 3\Packages` (`AppData\Roaming\Sublime Text 3\Packages`)

### samples
Playground, nothing more.
