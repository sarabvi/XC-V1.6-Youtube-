# XC-V1.6-Youtube-
add youtube channel to xc

To install the YouTube version of Xtreme Code 1.6 we use the command

"wget https://yt-dl.org/downloads/latest/youtube-dl -O /usr/local/bin/youtube-dl
chmod a+rx /usr/local/bin/youtube-dl"

Get the youtube channel's formate and qulaity
"youtube-dl --list-formats https://www.youtube.com/watch?v=8LbEoZ6ok9w"

After that all kinds of resolution will appear for the video or broadcast in YouTube

format code  extension  resolution note
91           mp4        256x144    HLS  269k , avc1.4d400c, 30.0fps, mp4a.40.5@ 48k
92           mp4        426x240    HLS  507k , avc1.4d4015, 30.0fps, mp4a.40.5@ 48k
93           mp4        640x360    HLS  962k , avc1.4d401e, 30.0fps, mp4a.40.2@128k
94           mp4        854x480    HLS 1282k , avc1.4d401f, 30.0fps, mp4a.40.2@128k
95           mp4        1280x720   HLS 2447k , avc1.4d401f, 30.0fps, mp4a.40.2@256k
96           mp4        1920x1080  HLS 4561k , avc1.4d4028, 30.0fps, mp4a.40.2@256k (best)


Here we observe the best quality number 96 which is the best taking number
Put the link like this in the panel

"`youtube-dl -f 96 -g https://www.youtube.com/watch?v=8LbEoZ6ok9w`"
without qoutes but keep the single one.
