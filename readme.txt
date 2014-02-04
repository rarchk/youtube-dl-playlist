youtube-dl-playlist(Behind Proxy)

This is forked version of youtube-dl-playlist by Jordon Mears, and designed to use behind proxy. 	

Usage: youtube-dl-playlist PLAYLIST_ID [DESTINATION_PATH]

This utility allows you to download all the videos from a playlist on Youtube. 
It creates a folder in the current directory (or in the specified path) named 
after the playlist name and then downloads each video in order and places it 
within the folder.

If the script fails in the middle of the playlist you can restart it with the 
same options and should pick up where it left off.

Depends on:
 - Python (should be available on Linux/Unix/Mac by default)
 - youtube-dl (avaliable at http://rg3.github.com/youtube-dl/ and in repos for 
   most Linux distros)

