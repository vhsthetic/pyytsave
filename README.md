# pyytsave

Python3 script on your linux terminal for yt-dlp. I use this to archive youtube videos. User will be asked to enter a folder path to save files before pasting links to create a batch or single file download. Once everything is set, the script will run yt-dlp, downloading videos from each link provided. The best possible audio and video will be downloaded as well as video description, thumbnail, comments and subtitles. Once all the files are done downloading the user may add more links for download or exit the script. 

# dependencies

Python 3
Python OS module
Python subprocess module
yt-dlp (2024.08.06)

yt-dlp should be available in your software repository. If you have installed yt-dlp and the script does not function you may need to update yt-dlp
https://github.com/yt-dlp/yt-dlp

# to do

An option asking the user if they wish to save the video as separate chapters. Default will be no. 
