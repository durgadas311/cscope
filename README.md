# cscope
## Enhancements to sourceforge cscope project

New options:

**-z**
-   Use legacy cscope behavior, suited to code exploration vs. code editing.
    Cursor stays in search panel after displaying results, and digit keys
    select the first ten results (digits as first char of search criteria
    require escape).

**-x**
-   Interpret files in -i namefile exactly, do not scan for options.
    Allows blanks or other chars in file names without causing problems later.
    Each line in 'namefile' is taken as a complete file/path.

**-H file**
-   Use file to load and save cscope history. Limited to 100 lines (history items).

**-N title**
-   Display title on screen, to differentiate windows using different cscope databases.
    In rare cases, may obscure part of status string.

See also [original sourceforge README](/README)
