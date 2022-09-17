# mpvreadtime
seek to times in mpv by typing them into the terminal window

the use case is when you have a list of times you want to play.   the easist way to do this is to type the time needed, and hit return.  the mpv player should instantly seek to that time.  
If you need changes, I'm willing to talk. 

## Usage 
**Run the script with the files you wish to play in mpv**.    
then close mpv when you're done. easy.

    $ mpvreadtime "file" "file2" file*

after this script runs mpv, mpvreadtime will give you a prompt, since it must be run in a terminal, at which time you can start seeking in the mpv window that's playing.

this stand-alone perl script should work on any linux-like system with mkfifo and socat.    
`mpvchapter` is provided as a demo how to play a random chapter
`mpvlink` is provided as a way to copy files which are deleted on disk, but still playing in mpv.
`mpvarguments` is provided as a way to list or rename files open in mpv.  requires the https://github.com/marcusbuffett/pipe-rename to rename automatically. 
