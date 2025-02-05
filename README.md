# Few of my personal scripts

the code should be reusable 
as long as you change the environmental variables
helper scripts like dmenu_pos rely on patched programs
or other programs as per usual

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
that an operating system should provide out of the box
or scripts that are used by other system-esque programs
eg. my file manager is a tui program that is barely usable
but extremely extensible

## utility

scripts that are either very simple or it doesn't make sense
to use them outside of other scripts
eg. delay_step for visual feedback of certain operations
or copy_last_command which copies last command to clipboard
