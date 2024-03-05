# countdown.sh -- display a running countdown time

This is a simple Bash script for the Linux console, that displays a running
time until some specific event. 

Usage:

    countdown.sh "date/time string"

 The date/time string is parsed by the 'date' utility, and can be any format
 that utility understands. FOr example:

    countdown.sh "dec 18 2024 4:00pm"

Don't forget the quotes around the date/time string. Note that this script
assumes conventional Linux terminal handling of \r and \n -- it might not
work with a serial terminal.


