LOG SCRIPTS
===========

Some scripts for log analysis.

## Help

datelog

    Usage: datelog [-s START-DATE][-e END-DATE][-p] < LOG > OUT
    
    Read the first line from log and determine how the date can
    be extracted. Then print the input log by prepending the date.
    
    Supported dates are:
    
    (1) YYYY/MM/DD HH:MM:SS      (5) time="20YY-MM-DDTHH:MM:SS...Z"
    (2) DD/MM/YYYY:HH:MM:SS      (6) at 20YY-MM-DD HH:MM:SS
    (3) 20YY-MM-DD"T"HH:MM:SS"Z"
    (4) 20YY-MM-DD"T"HH:MM:SS.
    
    With -s and -e you can select a section of the log. With -p
    the date is not prepended.

gzlog

    Usage: gzlog [-n NUM][-r] LOG
    
    Print LOG file and also LOG.<n>.gz files to standard output.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
