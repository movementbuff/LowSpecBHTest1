Huge shoutout to EvilQuaint!

**UPDATED 26th November, 2024: Removed Shader commands from DeviceProfiles.ini as causes issues.
-

UPDATED 2nd of July, 2024. Added Antialiasing to clean up the image. Very Minor FPS reduction as a result - check base of guide to remove it if desired.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
UPDATED 25th June, 2024. Responsiveness increased via several methods. Basically a comp config at this point. 
----------------------------------------------------------------------
I have been testing different cvars in configs in Bloodhunt for 2 years now. As it has been so long, I have decided to compile a low spec config and release it so that anyone can try and provide feedback on the performance.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
                                                                                          
-----------------------------------------------------------------------------------------------------------------------------------------------------                                                                                      
GUIDE: - (Optional) Follow along here with Video Guide https://www.youtube.com/watch?v=7SXHlt0s8yA
-----------------------------------------------------------------------------------------------------------------------------------------------------
- First, Press Windows Key + R and type %localappdata%\Tiger\ then press enter.
  
- Copy and Backup the folder "Settings" to somewhere memorable.
- Open the folder "Saved" then "Config" and copy the "WindowsNoEditor" folder, placing it with the other Settings backup.
- Leave your backups alone unless you seek to restore your previous settings. 

- Inside WindowsNoEditor folder ( %localappdata%\Tiger\Saved\Config\WindowsNoEditor ) replace your current "Engine.ini" ,  "DeviceProfiles.ini" and "GameUserSettings.ini" with the files you downloaded.
- After replacing, Right click each file and Select "Properties". Ensure that "Read Only" is ticked/enabled.
  
- Return to the Tiger folder ( %localappdata%\Tiger\ ) and open the "Settings" folder, then replace "DisplaySettings.json" and "GraphicsSettings.json" with the 2 from inside this github's "Settings" folder.
- Perform the same check as you did before to verify that Read Only is enabled on both files.

- Finally, Use RTSS to cap Frame Rate at 120, 125, 144, 165, 180, 200 or use the in-game Frame Limiter to prevent the framerate from spiking and dipping  (RTSS is strongly preferred. It is free and simple to use)
  I recommend testing each Frame Rate cap over several matches until you can decide on which is the most consistent during fights.

Want more FPS or is your PC too Low Spec? Use this DeviceProfiles at this link: https://github.com/movementbuff/lowspecbh


IF YOU WANT TO FURTHER INCREASE FPS YOU CAN REMOVE THE ANTIALIASING I HAVE ADDED BUT IT WILL MAKE THE IMAGE LOOK VERY HARSH.
To do so, remove these commands from your Engine.ini underneath " [SystemSettings] " if you wish to remove AntiAliasing.

r.PostProcessAAQuality=3

r.Tonemapper.Quality=2

r.Tonemapper.Sharpen=4

r.TonemapperFilm=1


-----------------------------------------------------------------------------------------------------------------------------
https://www.youtube.com/watch?v=ykGgOJMPcDk
Do everything in this video - it will improve the overall performance significantly unless you have a unique limiting factor.
-----------------------------------------------------------------------------------------------------------------------------


+ Twitch. https://www.twitch.tv/movementbuff

+ YouTube. https://www.youtube.com/@movementbuff

+ Join the Discord. https://discord.gg/a47PEhE8WE

