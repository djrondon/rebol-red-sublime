Rebol syntax highlighting for Sublime Text 2/3
----------------------------------------------

It is based on the [TextMate Bundle](https://github.com/rgchris/rebol-tmbundle)
made by [@rgchris](http://chat.stackoverflow.com/users/292969/rgchris)

Currently the only difference is that the `Preferences/Symbols.tmPreferences`
has been removed since it was throwing an error at load time.

Installation:
-------------

### ST3 on Mac OS X ###

    cd ~/"Library/Application Support/Sublime Text 3/Packages"
    git clone git://github.com/onetom/rebol-sublime Rebol

### ST2 on Windows / Linux ###

Please refer to the [documentation](http://docs.sublimetext.info/en/latest/basic_concepts.html#the-data-directory)
regarding the configuration pathes.

Notes:
----------

Commands assume Rebol is installed in `/usr/local/bin` as `rebol` (Rebol/Core) or `rebview` (Rebol/View).
