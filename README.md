Dead simple journaling with your favourite editor, from and using your shell
============================================================================

Installation
------------

Clone it, then add it to your path or symlink it. It requires only a bourne-compatible shell. (bash, dash, zsh, etc all acceptable)

Usage
-----

    $ jn Went to the post office

    $ jn -j changelog.txt Removed libc6

    $ jn

> Brings up your $EDITOR with a datestamp. Saving and quitting adds to journal.

    $ jn -e

> Brings up the whole journal in your $EDITOR.

    2015-06-25
    I did stuff
    
    2017-08-12
    I did more stuff
    
    2017-09-20
    I was sad
    ...


