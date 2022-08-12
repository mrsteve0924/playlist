## playlist  
A few shell scripts to play your audio collection and provide artist &amp; song title with timer in your panel

Requirements  
VLC. Using cvlc command to play audio files as well using vlc's media server to get song information.  Go into VLC ALL preferences, main interfaces, and select web. Then create Lua HTTP password.

I wrote these scripts so I can quickly start listening to my locally stored music without having to open up the VLC gui or type a string of commands in the terminal. mapped the play script to a keyboard shortcut for quick launching. 

subsequently addded the nowplaying script so i can see song info and time remaining easily.  using generic monitor plugin (xfce) to display a /tmp file with the media information.

From Terminal  
play will queue up your locally stored audio files and play them  
play- will allow you to choose a specific artist or song

![screenshot1](https://user-images.githubusercontent.com/37476191/136313827-3cd7d369-228f-4d6f-a29f-65fe40042ce8.png)

Displayed on panel  
![songtime](https://user-images.githubusercontent.com/37476191/184282760-daebff89-25c8-4313-85ac-0ff7e549f2cb.png)
