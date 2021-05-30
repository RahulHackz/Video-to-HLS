# Video-to-HLS

Create video into HLS easily!<br>
This uses FFMPEG.<br>

It generates video with these resolutions, bitrate and audio-rate<br>

  resolution | bitrate |  audio-rate<br>
  426x240    |  400k   |  128k<br>
  640x360    |  800k   |  128k<br>
  842x480    |  1400k  |  192k<br>
  1280x720   |  2800k  |  192k<br>
  1920x1080  |  5000k  |  256k<br>

How to use:<br>
1. Download/Clone this repo
2. Run the main script which converts video into HLS (.m3u8) as shown below, <br> bash video-to-hls.sh video-file.mp4 /output/folder
      
NOTE (for Linux newbies):
Make sure you have installed FFMPEG in your Linux system, and also you should give the correct path or video file name.
