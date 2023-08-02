______               _                
| ___ \             | |               
| |_/ /___  __ _  __| |_ __ ___   ___ 
|    // _ \/ _` |/ _` | '_ ` _ \ / _ \
| |\ \  __/ (_| | (_| | | | | | |  __/
\_| \_\___|\__,_|\__,_|_| |_| |_|\___|

Please the changelog section carefully.

--------------------------------------
     Charamile Designs Skewer 1.1p
            PUBLIC RELEASE
--------------------------------------

LICENSE INFORMATION:

	https://creativecommons.org/licenses/by-nc-sa/4.0/

	This work is licensed under a Creative Commons Attribution NonCommercial ShareAlike 4.0 International Liense. (CC BY-NC-SA 4.0)

	You are free to modify the files and share them IF CREDIT IS GIVEN AND THIS SAME LICENSE IS APPLIED.

	You are NOT free to sell these files or otherwise use them to make profit without contacting me and getting explicit permission from me.

--------------------------------------

Changelog
	
	1.1p - Several changes were made. Reprints aren't strictly necessary if you are happy with your blaster as-is but recommended for points [A], [B], and [C].
	
			- PLUNGER HEAD NOW ACCEPTS A CALIBURN SHOCKPAD.
	
			- [A] Rambase no longer explodes if you fire with an open bolt. 
				This was a common issue that has finally been fixed with some part tweaks. PRUSASLICER USERS SHOULD REFER TO THE NOTE IN THE NEXT SECTION FOR IMPORTANT INFORMATION.
				
			- Magwell and frontcap now self-align during assembly.
				This just makes the blaster look a bit neater for anybody who doesn't like slightly misaligned parts.
				
			- Sacrificial bridges added to certain parts with counterbored screwholes so they print with less mess.
				Solves a common problem that didn't really hurt anything but still looked bad even though it wasn't visible.
				
			- [B] Plunger spring cup guide post shortened to stop it from smashing into the guide post on the backcap. 
				Stops a rare failure where unreasonably aggressive priming can cause the back of the blaster to explode when the two posts collide after extended abuse.
				
			- [C] Hex nut sockets in backcap adjusted to stop hex nut rotation.
				Due to the shape of the lower sockets on the backcap, hex nuts were able to rotate in some cases and loosen over time. This has been remedied and the blaster should stay tight now.
				

	1.0p - Initial public release

--------------------------------------

IMPORTANT NOTE FOR PRUSASLICER AND SLIC3R USERS:

	The rambase will not slice properly unless you find the "Slice Gap Closing Radius" option and set it to zero (0).

Like, seriously. It will do some really freaking weird stuff if you don't turn that off. 

That gap setting is designed to remove/ignore any weird cuts in models that would normally appear if somebody made a bad mesh, but in this case the part has some very important ones that are INTENTIONAL and should not be ignored.
The slices are intended to force the slicer to make walls in a specific pattern to stop the rambase from breaking. 100% infill causes too many dimensional accuracy issues and just wastes material.

---------------------------------------

JOIN THE DISCORD FOR HELP, SOURCE CAD, AND FILE UPDATES -> https://discord.gg/qTqGzzkx7q

Thanks for sticking with us for 1.1! 
If this is your first download, welcome! Thank you for taking interest in the project, it means a lot! 

All of the STLs should be oriented properly for printing. 
Nothing requires supports though depending on your printer, a brim may be required for a few pieces.

gripback.stl has a tendency to fail or print poorly on machines with bad cooling. When in doubt, add a large brim.

--------------------------------------

Please read all of the instructions CAREFULLY.
Follow everything to the best of your ability. 

Due to the nature of this blaster it may not function properly if things aren't lubricated properly or if you get lubricant into places it does not belong.

Be careful, and have fun!

--------------------------------------
