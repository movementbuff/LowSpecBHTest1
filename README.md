Basic Performance Configs 1920x1080 
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
I have been testing different cvars in configs in Bloodhunt for almost a year now. As it has been so long, I have decided to compile different configs and release them so that anyone can try them and provide feedback on the performance.
This feedback helps me immensely as it often takes hours to test just 1 CVAR since there is no way (Legally) to access the console in-game.
   That means to test and determine the impact of "GenericConsoleVariable=X", I need to add it to the config, load up the game, spawn into a solo match (tutorial does not perform the same as actual game), 
   play the match, traverse all around the map and observe for artefacts or glitches, check and log the FPS and other performance charts after the match, 
   then go back to the file and change "GenericConsoleVariable=X" to "GenericConsoleVariable=Y" et cetera... 
   It is a futile process that I would not continue if I was not pleased by the process of learning.
   
   I am not a software developer and have no knowledge of such languages. I simply enjoy engineering methods to get things to function the way I want them to.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
                                                                                          
                                                                                          
  GUIDE:
-
Make sure you download the files from the branch that corresponds to your resolution. There are two branches, 1920x1080 and 1920x810. This is the 1080 Branch, which is the default. Most likely this is the correct branch for you.
If you do not want 1920x1080 or x810 and prefer to use a different resolution; open the files in Notepad and Find and Replace (CTRL F) all instances of the values "1920" and "1080" with whichever resolution values you prefer.
Alternatively, you SHOULD be able to change to your preferred resolution in-game, however you will need to do this every time after launching Bloodhunt.
     
 --------------------------------------------------------------------------------------------------------------------------------------------------------------

- First, Press Windows Key + R and type %localappdata%\Tiger\ then press enter.
  
- Copy and Backup the folder "Settings" to somewhere memorable.
- Open the folder "Saved" then "Config" and copy the "WindowsNoEditor" folder, placing it with the other Settings backup.
- Leave your backups alone unless you seek to restore your previous settings. 

- Inside WindowsNoEditor folder ( %localappdata%\Tiger\Saved\Config\WindowsNoEditor ) replace your current "Engine.ini" ,  "DeviceProfiles.ini" and "GameUserSettings.ini" with the files you downloaded.
- After replacing, Right click each file and Select "Properties". Ensure that "Read Only" is ticked/enabled.
  
- Return to the Tiger folder ( %localappdata%\Tiger\ ) and open the "Settings" folder, then replace "DisplaySettings.json" and "GraphicsSettings.json".
- Perform the same check as early to validate that Read Only is enabled on both files.

- Finally, Use RTSS to cap Frame Rate at 120, 125, 144, 165, 180, 200 or use the in-game Frame Limiter to prevent the framerate from spiking and dipping  (RTSS is strongly preferred. It is free and simple to use)
  I recommend testing each Frame Rate cap over several matches until you can decide on which is the most consistent during fights.

-----------------------------------------------------------------------------------------------------------------------------
https://www.youtube.com/watch?v=ykGgOJMPcDk
Do everything in this video - it will improve the overall performance significantly unless you have a unique limiting factor.
-----------------------------------------------------------------------------------------------------------------------------


+ Twitch. https://www.twitch.tv/movementbuff

+ YouTube. https://www.youtube.com/@movementbuff

+ Join the Discord. https://discord.gg/a47PEhE8WE

