Theme 'ComicBook_4:3' v0.0 - 04-16-2017 by TMNTturtlguy
Theme File Structure based on "carbon" Eric Hettervik (Rookervik) RYOKAI.DEVIANTART.COM
Controller.svg from "carbon" Eric Hettervik (Rookervik) RYOKAI.DEVIANTART.COM
Theme Concept based on images posted by: lipebello on Retropie.org.uk/forum
For use with EmulationStation (http://www.emulationstation.org/)

This theme is designed for 4:3 aspect ratio only.

Theme is designed to be used with the slide transition.

This theme requires VRAM to be set to 120 for smooth operation (avoid white screen) when using several systems on older EmulationStation builds.  I have not tested on the new ES with maxSize.
-set gpu to 256

v0.0 is designed on EmulationStation version prior to maxSize for video and prior to carasoul updates.  Designed on @fieldofCows/@pjft ScreenSaver ES Build
-Video and images designed using the OMX player option on screensaver OS build.  All videos and images will retain proper aspect ratios with OMX player.
-Video and images will lose original aspect ration if played on vlc player (standard ES)
-Next update will include a build for the Main Branch of ES. 
-If running on Main Branch of ES with maxSize.  Edit line 78 of comic_book.xml to <maxSize>.  I still need to see if the locations of the images need to be adjusted.

Fonts:
Users can use any font they would like with the theme. Just copy your font to /etc/emulationstation/themes/ComicBook/art folder. 

Gamelist Font Size:
To change the font size of the Gamelist, open the "ComicBook.xml" with a text editor, look for the tag <gamelist> and find a tag inside called <fontSize>. The original value is 0.03. A small change makes a big difference in size. If you want smaller gamelist names, try 0.02. If you want larger, try 0.04. You can even go further by trying 0.015.

Colors:
To change the colors open ComicBook.xml with a text editor. Choose a color and find it's hexidecimal value. Some examples are found in the carbon.xml file. Find all occurances of "8b0000" and replace them with your chosen color. Such as Orange: ef710b. Save the carbon.xml and exit. To change the color to another color after the first change, search for your old color, and replace it with a new one.

Sounds:
- To change the sound effect, replace /art/scroll.wav with what ever WAV file you would like. ComicBook theme will play what ever is called "scroll.wav" in the /art folder.
- Some systems have launching sounds, for example NES plays a coin sound at launch.  To remove the launch sound, edit the theme.xml in the system folder within ComicBook Theme.
- To add launch sound add this to the theme.xml for the system:
		<sound name="launch">
			<path>./art/XXXX.wav</path>
		</sound>
XXXX = the name of the .wav file.  Add the .wav file to the art forlder for the system.

The theme is designed for use with video preview.  
-The detail (Video View) will play the preview video "md_video" in the large black box.
-Scraped art "md_image" wil be displayed in teh bottom gray box to the right of the video.
-YOU MUST HAVE AT LEAST 1 VIDEO in each systems gamelist in order for this to work.  If you do not have a video for a system YOU MUST:
-If you do not have a video for a system: Open the theme.xml in the systems folder.  Delete lines 53-57 "md_image"  The bottom gray box will be blank, but the scraped art will appear full size in the large black box.
-If you have at least 1 video, the scraped art "md_image" will appear in both the Large Black box and the small gray box for all games that are missing videos.
-Solution to issue: To solve this issue, change "md_image" on line 53 to "md_thumbnail"  add graphics to your gamelist for md_thumbnail.
     (future update may include this change so that the small gray box contains wheel art or game logos)
	 

Original Systems in Theme:
Aracde
Atari 2600
Atari 7800
NES
SNES
N64
GB
GBC
GBA
NDS
Genesis
Dreamcast
PSX
PSP
Retropie (menu)

All other themes are set to work with a generic comic background to match the rest of the theme.  The system logo will be the standard logo from the Carbon Theme.  On the detailed view  They sytem logo will appear twice at the top of the screen.


Changelog
=========



License
=======

-------------------------------------------------------------------------

Summary of the license below:

ALLOWED:      - Share and duplicate as it is
              - Edit, alter, change it

REQUIREMENTS: - Attribution, give credit to the creator
              - Indicate changes to it
              - Publish the changes under the same license

PROHIBITED:   - Commercial distribution

-------------------------------------------------------------------------

LOGO NOTICE

The used logos and trademarks are copyright of their respective owners.

-------------------------------------------------------------------------

