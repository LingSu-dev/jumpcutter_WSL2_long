# jumpcutter_WSL2_long
Extends WyattBlue's Impl, but works better for longer videos. 

For videos >1h, use long_fast_video.py, command structure is the same as fast_video.

For instructions, python fast_video.py -h

Works exclusively with mp4. youtube-dl -f 22 <link> is the best way to convert youtube lectures. 

need ffmpeg and everything in requirements.txt

works exclusively in unix environment, tested with WSL2 ubuntu. 

make sure the script is in the same folder as video file

make sure the video file has no spaces in it, use "-" instead. 

Use my version only if you have low memory (<=8gb) and find the original crashes for you.

use this one: 

https://github.com/WyattBlue/jumpcutterV2

or this one:

https://github.com/seaty6/jumpcutterV3GUI

instead if you don't. 
