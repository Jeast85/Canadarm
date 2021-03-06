Canadarm v1.71
========================================
Canadarm 1 for KSP.
This is the Space Shuttle Canadarm. Compatible with the stock cargobay (long verion), Decqs Space Shuttle System, CSS by Dragon and the One Piece Shuttle by MIKE-NZ.
ModuleManager adds a node to the cargobays for attachement.

********************************
****** LICENSE ******
*******************************
http://creativecommons.org/licenses/by-nc-sa/4.0/


********************************
****** DEPENDENCIES ******
*******************************
-	Modulemanager (included)
-	Infernal Robotics (https://github.com/MagicSmokeIndustries/InfernalRobotics/releases/latest)
-	Kerbal Attachment System (http://forum.kerbalspaceprogram.com/threads/92514-0-24-2-Kerbal-Attachment-System-%28KAS%29-0-4-8-Fixed-for-0-24-2-x86-x64-%29)

********************************
****** RECOMMENDED ******
*******************************
-	Rasterpropmonitor (https://github.com/Mihara/RasterPropMonitor/releases/latest)
-	Kerbal Joint Reinforcement (http://forum.kerbalspaceprogram.com/index.php?/topic/50911-112-kerbal-joint-reinforcement-v317-43016-now-with-win64-compatibility/)

********************************
****** INSTALLATION ******
*******************************
-	Install all dependencies
-	Extract folder content to your KSP/Gamedata folder
-	(optional) Extract subassembly file to your KSP/saves/profilename/subassemblies folder

********************************
****** ASSEMBLY ******
*******************************
-	Nodes are automaticly added to the stock, CSS and Space Shuttle Pack cargobays
-	Attach the Shoulder part to the node
-	Attach the Upperarm to the shoulder
-	Attach the Lowerarm to the upperarm
-	Attach the Wrist to the lowerarm
-	Attach the Endwrist to the wrist
-	Attach the End to the endwrist
-	(Optional) Attach the grapple port to the object you want to lift

-	Change the camera id's on the End and Lowerarm parts (right click on them), they both are 1 at default. Make sure they have unique id's.


********************************
****** FEATURES ******
*******************************
-	Working smooth, no wobble!
-	Camera in effector and on lowerarm, for IVA use (optional by using RPM)
-	Effector uses magnet. This is not realistic but this is the reason there is no wobble. And you can pick up Kerbals with the arm!


********************************
****** USAGE ******
*******************************
The mod adds an attachment node to the CSS, Onepiece and stock cargobays. This is where you should attach the Shoulder part. The shoulder part cannot be surface attached!
The Canadarm uses IR for the moving parts and KAS for the effector magnet. You can create presets in the VAB (recommended).
To "grab" stuff with the effector you have to enable the magnet. It is recommended to map this to an action group in the VAB.
The arm and the magnet both use electrical power so keep this in mind when using the arm. There is a camera mounted in the effector wich you can use via Rasterpropmonitor
Beside the magnet you can also use the supplied grappling port instead.


********************************
****** KNOWN BUGS ******
*******************************


********************************
****** CHANGELOG ******
*******************************
v1.71

		BugFixes
		--Fixed incorrect version
v1.7

		Features
		--Grappling port added
		
		BugFixes
		--RPM fixed and enabled
v1.62

		BugFixes
		--Disabled RPM temporary due to shifting CoM
v1.61
		
		BugFixes
		--Changed textures from MBM to DDS to fix the black textures and reduce size
v1.6

		Features
		--Updated to KSP 1.1
		--Model reworked from scratch
		--Textures redone from scratch
		--Optimized by reducing texture numbers, all parts use one texture now
v1.51

		BugFixes
		--MikeNZ's shuttle cargobay node fixed
v1.50

		Features
		--added new meshes and textures
		--added rotation joint axis to the lowerarm
		--removed angle lock on upperarm pitch
v1.00

		BugFixes
		--fixed black lines on textures
		--removed extender
		
		Features
		--added camera to lowerarm
v0.96

		BugFixes
		--parts unclickable in VAB and 3d world. Colliders fixed
		
		Features
		--added mini AVC for version checking
v0.95

		Features
		--release version
