# Bachelor_Game

This game was developed as part of my Bachelor Thesis titled "Interactive Visualization to Assess Hand Kinematics." The game is designed to be played using a Leap Motion Controller, and this repository includes all the necessary files for running the game as an executable.

## Requirements 
* Leap Motion V2 with v2.3.1 Tracking SDK 
* Physical Leap Motion Controller 
* Tested on Windows 7 and Linux Ubuntu 18.04
* Ensure the "leapd" process is running (either from Terminal on Linux or via the Leap Motion Control Panel on Windows)
 
## Notes 
If tracking appears unstable, check the quality using the "Visualizer" (Leap's built-in tool) and calibrate the Leap Motion Controller to a value of at least 90. 
For Linux, mark the game as executable via "chmod +x GameLinux.x86_64" or by right-clicking and selecting "mark as executable file."

## Funding 
This project received funding from EIT Health under grant id: 19340.
Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a [Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

## FAQ 
**Q:** Where is the captured data stored?  
**A:** For the Linux Build, in the GameLinux_Data/Captured folder. For the Windows Build, in the Hand_Kinematics_Game_Data/Captured folder.

**Q:** How to change hand models?  
**A:** Press the left or right arrow key in a level (won't change in the menus).

**Q:** How to improve gameplay?  
**A:** Move slowly, avoid obstructing the Leap's view of the fingers, spread unused fingers apart, and use only pinch grips. Pay attention to the visual feedback, especially the changing colors.

## Further Work

The Unity Project for the game is available in a separate repository, allowing for modifications and extensions. Contact me for access to the Unity project data.

As part of the Thesis, an abstract was submitted for participation in the ISB 2021 Conference. The abstract was accepted, and a poster presentation is scheduled for 29.07.2021. Materials related to this participation can be found in the ISB Folder.
