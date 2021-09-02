# mpvreadtime
seek to times in mpv by typing them into the terminal window

the use case is when you have a list of times you want to play.   the easist way to do this is to type the time needed, and hit return.  the mpv player should instantly seek to that time 

## Usage 
run the script with the files you wish to play in mpv.  then close mpv when you're done. easy.
`$ mpvreadtime "file" "file2" file*

after this script runs mpv, mpvreadtime will give you a prompt, since it must be run in a terminal, at which time you can start seeking in the mpv window that's playing.

this stand-alone perl script should work on any linux-like system with mkfifo and socat.
