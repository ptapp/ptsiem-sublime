# Sublime Text support for some Positive Languages

## XP and CO
There are two mini-languages, say XP and CO, used to describe normalization instructions and correlation rules for the PTSIEM platform. This project implements Sublime Text (3) syntax definition and some settings for them.

Syntax definitions provide syntax highlighting for our DLSs, but there is no special color scheme enclosed herewith.

##Repository folders info:

### src
Source files in YAML. They are to be converted to TM-PList with AAAPackageDev. TM-PList is a PropertyList format used by TextMate and Sublime Text.

### built_stuff
Files that ready for copy-to-use. Just copy them to the `Packages\User` directory (relative to ST3-AppData).

> hint: ST3 menu: `Preferences -> Browse packages...` opens the path `%appdata%\Sublime Text 3\Packages` (`AppData\Roaming\Sublime Text 3\Packages`)

### samples
Playground, nothing more.
