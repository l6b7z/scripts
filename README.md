# Few of my personal scripts

the code should be reusable, you should only keep in mind
the environmental variables and a helper scripts like dmenu_pos
that might work differently based on operating system or software

## dmenu_pos

dmenu is a program that is a very basic launcher
think about this like a menu creator
hence the input may very in size I created this script
to easily change the coordinates or size of said menu
it won't work with a standard version of dmenu as I patched mine to
be more flexible

## statusbar

scripts that produce basic output (string)
and send a signal to change a state of the system
eg. changing the volume with mouse scroll

keep in mind some scripts use other scripts or programs
such as 7z (for archives) or pamixer (for volume) 

## system

these are resposible for basic funtionality
that an operating system provides out of the box
or scripts that are used by other programs
eg. my file manager is a tui program that is barely usable
but extremely extensible

## utility

scripts that are either very simple or it doesn't make sense
to use them outside of other scripts
eg. delay_step for visual feedback of certain operations
or util_loop_cmd that just runs a script in a loop
(helpful when constant feedback is necessary)
