Theme 'ComicBook_4:3' v0.5 - 06-13-2017 by TMNTturtlguy
Controller.svg from "carbon" Eric Hettervik (Rookervik) RYOKAI.DEVIANTART.COM
Theme Concept based on images posted by: lipebello on Retropie.org.uk/forum
For use with EmulationStation (http://www.emulationstation.org/)


Special thanks to all who helped:
- pjft - for all the support throughout the build, testing, and work on the pixel effect
- Nismo - for all of the testing, input, and suggested improvements
- Ruckage - for updating font characters to support multiple languages.

This theme is designed for 4:3 aspect ratio only.

Thanks to new optimization and ES updates by @pjft there are no issues with performance.  VRAM should be set to 100.

See UserModInstruct.txt for instructions on available user modifications.

v0 is designed on EmulationStation with maxSize for video and carasoul updates.  It also works on the udpated Screensaver OMX build by @pjft on Apr2017
-Video and images will work properly on both VLC and OMX players. 
-If running on an older of ES without maxSize.  Edit <maxSize> of comic_book.xml to <size>.

Game Hacks Sytem views Available:
- add the following to your roms foler and es_systems.cfg. The abbreviation letters should be the name of the rom folder and the name of the theme in the es_system.cfg Simply copy your roms from the regular system into tne roms folder and apply hacks.
- gbh (game boy)
- gbah (game boy advanced)
- nesh (nes)
- snesh (snes)
- ggh (game gear) - not yet available on 4:3 version
- genh (genesis)

Capcom Systems Available (copy your arcade system from es_systems.cfg)
- cps1
- cps2
- cps3
- capcom

Custom Systems Available
- All Games (all games)
- Batman (batman)
- Beat'em Up (btmups)
- Favorites (favorites)
- Fighting (fighting)
- Kids (kids)
- Last Played (last played)
- Light Gun (lightgun)
- Mario (mario)
- Mega Man (mega man)
- Racing (racing)
- Shoot'em Up (shmups)
- Sonic (sonic)
- Sports (sports)
- TMNT (tmnt)
- Trackball (trackball)

Example for es_systems.cfg - copied gba and modified <name>, <path>, <platform>, and <theme> to gbah
<system>
    <name>gbah</name>
    <fullname>Game Boy Advance Hacks</fullname>
    <path>/home/pi/RetroPie/roms/gbah</path>
    <extension>.7z .gba .zip .7Z .GBA .ZIP</extension>
    <command>/opt/retropie/supplementary/runcommand/runcommand.sh 0 _SYS_ gba %ROM%</command>
    <platform>gbah</platform>
    <theme>gbah</theme>
  </system>

The theme is designed for use with video preview.  
-The detail (Video View) will play the preview video "md_video" in the large black box.
-Scraped art "md_image" wil be displayed in the large black box if a video is not available.


Systems in Theme:
3DO
AGS
All Games
amiga
amstrad pc
apple 2
Aracde
atari 800
Atari 2600
atari 5200
Atari 7800
atari jaguar
atari lynx
atari st
Batman
bbc micro
Beat'em Up
c64
capcom
channel f
coco (tandy)
colecovision
CPS I (cps1)
CPS II (cps2)
CPS III (cps3)
daphne
Dreamcast
dragon 32
Famicom
Favorites
Fighting
GB
Game Boy Hacks
GBA
Game Boy Advance Hacks
GBC
game gear
Game Gear Hacks
Game and Watch
GC
Genesis
intellisvion
Kids
Kodi
Light Gun
macintosh
Mario
master system
mega drive
Mega Man
msdos
msx
msx2
N64
NDS
neo geo
NES
NES Hacks
ngp
ngpc
odyssey2
oric
pc engine
pce-cd
ports
PSP
PSPminis
PSX
PS2
Racing
residualVM
Retropie (menu)
saturn
scummvm
Sega 32X
Sega CD
Sega Genesis Hacks
SG-1000
Shoot'em up
SNES
SNES Hacks
Sonic
Sports
steam
stratagus
Super Famicom
Super Grafx
TMNT
Trackball
Turbo Grafix 16
Turbo Grafix CD
vectrex
videopac
Virtual Boy
Wii
WiiU
wonderswan
wonderswan color
ZX Spectrum

All other themes are set to work with a generic comic background to match the rest of the theme.  The system logo will be the standard logo from the Carbon Theme.  On the detailed view  They sytem logo will appear twice at the top of the screen.


Changelog
=========
v0.1_4-19-17
	Marquee conflict resolved
		Marquee removed from all systems except actual arcade cabinet systems
		2nd System Logo removed from arcade cabinet systems
		md_marquee deleted from comic_book.xml and moved to theme.xml
	launch sounds added to all sega systems
	comic backgrounds updated for FB Alpha and all Mame systems to match the Arcade background for the time being.
	Comic background updated for all sega systems to match sega genesis background for the time being.
	
v0.3_5-19-17
	Major update to all systems, added new systems, to many to list.  Basically a whole new theme.
	Fully optimized

v0.4 5-21-17
	cleaned up folder structure.
	
v0.5 6-13-17
	Changed comic rip for Sega CD and Sega 32x
	Corrected controller in system background
	Renamed trs80 to trs-80 to match es_systems.cfg
	Updated all backgrounds to fix pixelation clarity
	Updated font to allow special characters for different languages - Thank you to Ruckage for supplying the font!
	Updated size of video and image in black box
	Updated to better support detailed view
	Update for color support on ratings
	Added the following Themes:
			- All Games
			- Batman
			- Beat'em Up
			- Favorites
			- Fighting
			- Gamecube
			- Kids
			- Last Played
			- Light Gun
			- Mario
			- Mega Man
			- MSX2
			- PS2
			- PSP Minis
			- Racing
			- Shoot'em Up
			- Sonic
			- Sports
			- TMNT
			- Trackball
			- Wii
			- WiiU
		
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

