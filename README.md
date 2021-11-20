# OBS-Youtube-Player

Designed for OBS Browser source to display/play a song/playlist fully automaticly with customs fixed params.

## Usage : add ? at the end of the link and copy Youtube link from "watch?v=XXXXX" or "watch?v=XXXXX&list=XXXXX")

exemple : https://leonwong93.github.io/OBS-Youtube-Player/?watch?v=lSqnqSSXTUI&list=RDlSqnqSSXTUI \
*enhanced now support ?t= or &t= correctly\
*removed list detection, it will stop once the video is ended\
*by stop,i make it redirect to about:blank as original code from hopollo i was facing issue on it keep on looping

## Features :

**volume :** Volume of the video player : &volume=VALUE (0 to 100, default is 100)\
 **w:** Width of the video player : &w=VALUE (default is 535) \
 **h:** Height of the video player : &h=VALUE (default is 300)\
 **hide:** Hide the video player : &hide=true|false (default is false)\
 **quality** Video quality of the player : &quality=small|medium|large|hd720|hd1080|highres|default (default is default)\
 **forcequality** Enforce choosen video quality : forcequality=true|false (default is false)\
 **fade:** Enable the volume fade on song start & end : &fade=true|false (default is true)\
 **debug:** Enable debug mode & show info on console : &debug=true|false (default is false)\
 **pic:** instead of redirect to about:blank, show end.jpg instead : &pic=true|false (default is false)

## Built-in features by default :

autoplay = enabled,\
Video controls (play,next, etc..) = hidden,\
Fullscreen button = hidden,\
Video info = hidden,\
Fade = enabled,\
Video annotation = disabled,\
and more....
