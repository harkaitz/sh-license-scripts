LICENSE SCRIPTS
===============

Scripts that help licensing software projects.

## Help

find-h-print-licenses

    Usage: find-h-print-licenses DIR FIND-ARGS...

find-h-readme

    Usage: find-h-license
    
    Print the current project's license file.

license

    Usage: license [LICENSE|calc] [show|notes|shell|file|long|short|update]
           license owned
           license show
    
    Calculate and create licenses from template "license--NAME" scripts.
    
    Calculation : license--NAME check FILE
    Generation  : license--NAME long (With "lLT:" line prefixes)
                  l: Show in help
                  L: Put line in header.
                  T: Put line only in the LICENSE file.
                : license-NAME notes : Print notes for the readme.
    
    Environment variables: LICENSE_YEAR, LICENSE_GREP_OWNED, PATH

license--gplv2

    Usage: license--gplv2 long|notes|check FILE

license--gplv2-git

    Usage: license--gplv2-git long|notes|check FILE

license--isc

    Usage: license--isc long|notes|check FILE

license--isc-openbsd

    Usage: license--isc-openbsd long|notes|check FILE

license--mit

    Usage: license--mit long|notes|check FILE

make-h-license

    Usage: make-h-license ...
    
    ... get-license  : Get license file.
    ... get-readme   : Get readme file.
    ... makefile     : Print 'Makefile'.

make-h-man

    Usage: make-h-man
    
    Convert markdown files with "*.[NUM].md" format to man pages.
    
    ... mds        : List markdown files.
    ... mans [NUM] : List man files.
    
    ... update    : Generate man pages from markdow files.
    ... makefile  : Print makefile section (used by make-h) (for installation).
    ... gitignore : Print gitignore section (used by make-h).

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
