# Bachelor_Game
This game was created for my Bachelor Thesis "Interactive Visualisation to assess Hand Kinematics" at Heidelberg university
and can be played by anyone who ownes a Leap Motion Controller.

## Requirements 
 Leap Motion V2 with v2.3.1 Tracking SDK 
 A physical Leap Motion Controller 
 Tested on Windows 7 and Linux Ubuntu 18.04
 Process "leapd" must be running (either from Terminal on Linux or via the Leap Motion Controll panel on windows)
 
## Notes 
If tracking appears to be very unstable check the quality via the "Visualizer" (Leap build-in Tool) and ensure the Leap Motion 
Controller is calibrated to a value of at least 90. 
Mark the game as executable for Linux via "chmod +x GameLinux.x86_64" or via "rightclick -> mark as executable file"


## FAQ: 
F: Where is the captured data stored? 

A: For the Linux Build in the GameLinux_Data/Captured folder
   For the Windows Build in the Hand_Kinematics_Game_Data/Captured folder

F: How to change handmodels?

A: Press left or right arrow key in a level (won't change in the menus)

