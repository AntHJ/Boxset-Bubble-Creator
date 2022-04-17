* The installed VPKs that this tool uses and creates was written in Lua Player Plus Vita (lpp-vita). [Learn more.](https://github.com/Rinnegatamante/lpp-vita)
* There is a Windows App include in my pack that was not created by me called tinyMediaManager. [Learn more.](https://www.tinymediamanager.org/)

![](https://github.com/AntHJ/Boxset-Bubble-Creator/blob/main/AppImage.png)

# About

VPK Video Boxset Bubbles are installable VPKs that contain a custom designed and created menu for your chosen movie collection. When used with the TinyMM tool (included) to search for movie information and images you can create a great looking installable bubbles. ideally to get the best look for your creation you need :
- an image for the bubble itself (ideally square or round)
- an image for the LiveArea launch page
- the Video file
- Cover/Boxart image for each movie
- Background image for each movie
- (optional) a default background
- (optional) an theme tune audio file

for the movie theme tunes you can goto [YouTube](https://www.youtube.com/results?search_query=Movie+OST) and search for the movies origional sound track (OST) and then use a YouTube to MP3 website to convert and download the audio track for use with this tool.

-----
![](https://github.com/AntHJ/Boxset-Bubble-Creator/blob/main/Boxsets.jpg)

![](https://github.com/AntHJ/Boxset-Bubble-Creator/blob/main/JW1.jpg)

![](https://github.com/AntHJ/Boxset-Bubble-Creator/blob/main/JW2.jpg)

>EXAMPLE BOXSET : [JOHN WICK](https://github.com/AntHJ/Boxset-Bubble-Creator/blob/main/JOHNWICK0%20-%20John%20Wick.vpk) (this does NOT contain any video files)

>EXAMPLE BOXSET : [SPIDER-MAN](https://github.com/AntHJ/Boxset-Bubble-Creator/blob/main/SPIDERMAN%20-%20Spider-Man.vpk) (this does NOT contain any video files)

------
## The Tools (main-menu)
there are quick launch links to the main features, otherwise all the functions of the tools can be accessed by the main menu.
- Option 1 is used to search for movie infomation and help prepare the files needed for the process, it will launch the TinMM application and help you to organise and find the artwork for your downloaded movie.. you have the option to press S during startup to skip the auto scan if you prefer. if you are running the app for the first time you will be asked where to search for your movies, i recommend you put them in a dedicated folder like for example C:\DownloadedVideos\
- Option 2 is used to create the Boxsets and has a few other options you can use if needed
- Option 3 is for preparing files for the MVPlayer.vpk and it also has a few other options
- Option 4 has a few other potentially useful tools to help you

![](https://github.com/AntHJ/Boxset-Bubble-Creator/blob/main/Menu.webp)

## The Tools (Boxset Builder)

![](https://github.com/AntHJ/Boxset-Bubble-Creator/blob/main/Builder.webp)

## The Tools (MVPlayer)

![](https://github.com/AntHJ/Boxset-Bubble-Creator/blob/main/Player.webp)

## The Tools (Extras)
- Option 6 can be quite useful as you can use it to batch convert videos (upto 10 at a time) so that you can have your movies pre-converted ready for when you want to build your Boxset. Alternitively you can use MVPlayer tools option 1 to batch create and convert the files (upto 10) and then use thoes files for the boxset creation.

![](https://github.com/AntHJ/Boxset-Bubble-Creator/blob/main/Extras.webp)

------
### Creation options
When creating a boxset you will have the option to either create a single VPK or a split VPK + MovieData.
- SINGLE - if you choose to create a single VPK then then menu and movie files will ALL be contained in the 1 VPK file so for example a trilogy box set like John Wick would potentially create a file of over 3gb. there is no issue here but it would mean that to install the boxset you need to transfer the 3gb file to the vita, then install it with VitaShell which could takea while and would require the same memory size again. so in another example a collection thats over 8gb would need 16gb of space to install and would take a LONG time to install.

- SPLIT VPK + MOVIEDATA - if you choose to create a split VPK + Moviedata (recommended) then you will have a 'TITLEID - Movie Name.VPK' of usually less than 20mb and then a seperate 'TITLEID - Movie Name(MovieData).zip' that can be extracted to the root of ANY of your storage media. (e.g. ux0:, uma0:, grw0:, xmc0)

Movie files are stored by default in ( ux0:/app/*BUBBLEID*/media/*Movie Name*/video.mp4 ) but if you prefer you can move them to an alternitive storage such as ( uma0:/app/*BUBBLEID*/media/*Movie Name*/video.mp4 ) as long as you keep the same file structure.

------
## How do i make the Boxsets ?
an example/tutorial of how this tool works can be seen [here](https://www.youtube.com/watch?v=0UBnZmmHM_I)

## Do i really need to convert my videos ?
Yes unfortunetly.. this is not because im forcing you to do this,  its due to fact that the Vita is an older system and doesnt understand modern video types and compression and simply cant properly handle anything it wasnt designed to view so this tool coverts your videos into the best possible resolution with minimal quality loss.

