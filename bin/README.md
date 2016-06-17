these are a bunch of scripts that i use as shortcuts for some frequent text and
image processing i do. mostly, they're rsi-deterrents.

**body**
    a quckie daily body condition logger. assumes $BODYLOG is set to the
    location of a logfile.

**findex**
    aka 'fake index', generating a directory listing for the current directory
    to a slightly obfuscated .html, either provided as a command line argument,
    or defaulting to `dickcheney.html`.

**picsplz**
    makes an html gallery of pictures, printed to index.html of the given
    directory.
    flags:
        * -t, 'thumbnails', makes a thumbnailed gallery
        * -h, 'hardlinks', uses $WWW to make hardlinked urls

**shrinkydink**
    shrinks given file to 1000px wide and saves as lr-*filename*
