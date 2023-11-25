# C-Xbox Tool 2.0.7
******************************************************************************************
******************************************************************************************
Use this program for your own risk. I cannot be held responsible for any kind of 
damage this program might have caused to any kind of stuff(pc, xbox, etc...). 
******************************************************************************************
******************************************************************************************

This tool is most complete tool until now. 
You can Make/extract XISO's, FTP your folders/ISO's to Xbox (ISO's on the fly, without
any temp files, not even in memory), You can patch and edit XBE-Titles, Explore an iso,
scan a folder for XISO-images, MXM and Menux Multigame wizards... and more(or there will 
come more).

Why this tool while there are lots of tools?
This is a tool with the most options to use and I'm trying to make it an All-in-One tool.
If you have a suggestion, an idea or tip just call it.

There are a few languages supported but if you can translate it to another language, feel
free to email me, there is a translation tool available to download but it does not add 
languages automatically untill now. I need to add the translated language by myself but 
in one of the next versions it wil add your translated language by it's self.

******************************************************************************************
******************************************************************************************

version History
Version 2.0.7
-------------------------------------------------------------------------------------------
* Multiple FTP up/download and remove (explore)
* Shell extensions; Extract to .. option with a selection window
* Shell extensions; 	Making an iso file of a folder using rightclick
			extracting of an iso file
* Multiple FTP connections; Batchmode uploads ability to upload to 
			    several servers in one upload action
* FTP Explore; select a connection and connect

* options: add/delete/modify connections
-------------------------------------------------------------------------------------------
version 2.0.6
-------------------------------------------------------------------------------------------
***	New logo for the tool created by "Can-Polat" from Beceriksizler Board. 

***	Bugfix "range check error" while creating multigame iso's. 

***	Bugfix Aborting transfer in boostmode. If you abort while transferring in boost
	mode, you should reset xbox(unleashx provides network reset, no need to reset xbox)

***	Variable FTP-Buffersize, min 32kb max 1024 kb. Application tries to select the best
	buffersize according to the transferspeed.

***	Portuguese language added.

***	Ability of disabling freespace checking. For some reason it didn't work on Win2k 
	machines and I didn't have time to check why. 

***	Ability of disabling filesystem checking, this was interesting for Linux users 
	because they don't have NTFS file system.

***	Some other bugfixes
-------------------------------------------------------------------------------------------
version 2.0.5
-------------------------------------------------------------------------------------------
***	Boost Mode support implemented. This feature can be enable from options-preferences.
	This feture does not work with FTP-Explore and works only for uploading ISO's or 
	directories from FTP-tab. This feature is default disabled, to enable it, go to 
	options-preferences. It must be allso enabled on your dash.

***	Ability to Create ISO-images from your (XBOX)FTP-server.

***	A new tab added named "FTP Explore" which is acting just like a FTP-Client. With
	this option you can; tranfer to/from (XBOX)FTP-server, delete, rename and move(this 
	means "cut/paste" but only in the same partition). It's simple but very usefull.

***	Bugfix while transferring to XBox which uses XBMC, Avalaunch, and UnleashdX as dash.	


***	Ability to remove the source-folder when the iso-file is extracted(immediatly, 
	before the batch is completed)
 
***	Ability to remove the iso-file when the file is extracted(immediatly, before the 
	batch is completed) 

***	Checkin for necessary space before adding/editing Createion/extraction items. 
	If remove option is used for extracting or creating, the checking will be done just 
	before creating or extracting one iso-item. This because after creating or extracting
	the item, the source will be deleted and there will be more space available again.
	Checking, just before creating/extracting, will be done even if the remove option is 
	selected this because you need some free space for the first extraction or creation.

***	On the multigame tab you can select up to 9000 mb discsize. No idea if a dual layer 
	disc burnt (for example) for 8000 mb's should work, but no problems creationg that 
	sized iso-images.

***	Checking for necessary free space for multigame-iso. 

***	4 More languages are added: Swedish, Italian, Finnish and Spanish.

-------------------------------------------------------------------------------------------

version 2.0.4
-------------------------------------------------------------------------------------------
***	Bugfix "on the fly" multigame-iso creation from other iso files. 

-------------------------------------------------------------------------------------------

version 2.0.3
-------------------------------------------------------------------------------------------
***	Adding ISO's by creating multigames. If you add a iso-image to a MenuX multigame,
	you'll not be able to create "Files only", you've to create an iso image. Creating
	multigame iso from iso's WITHOUT MAKING TEMPFILES !!

-------------------------------------------------------------------------------------------

version 2.0.2
-------------------------------------------------------------------------------------------
***	Exploring an XISO Disk and extracting
	
***	Bugfix reading Title from ISO when adding to FTP-list

***	French language added

***	Danish language added

***	Aspi.zip added for, necessary for exploring/extracting xiso discs.
-------------------------------------------------------------------------------------------

version 2.0.1
-------------------------------------------------------------------------------------------
*** 	Drag and drop files/folders from Windows exlorer to Extraction, creation and FTP.

***	A tray-icon is placed so that if the program will be working for a long time you
	can minimize it to system tray.(in case of transferring a lot of folders/iso-images
	or extracting/creating a set of iso-images)

*** 	German language is added

*** 	FTP buffer size was 32kb it's now 128 kb 

***	With an update of Lang.clf file Danish will allso be supported

***	Replace a file in ISO-Explore

*** 	A few bugfixes
-------------------------------------------------------------------------------------------


version 2.0.0
-------------------------------------------------------------------------------------------
***	Job save/load, you can make a job of an extraction, Creation and FTP transfer and
	save them so you can load later and execute.

***	Another way of downloading and installing of themes. 

*** 	FTP is added to make it possible to FTP folders and ISO images to XBox. By 
	transferring ISO-images the files from the images will be transferred "on-the-fly",
	without making any temp files !not even in memory!.

*** 	Scan Folder; this option scans a selected drive or folder for existing and VALID
	Xbox ISO-images. You can select some files and FTP the selected or extract them.

***	ISO-Explore; An ISO file can be explored and extracted. Possibility of extracting
	one or more folders.
	 
***	Editing of XBE-Titles, a tab is placed for this option

***	Patching of XBE-Files, another tab is placed for this option

***	Image Editor, this is a simple image editor for copying, pasting, rotating, 
	resizing and converting of image-files. It's fast, easy and simple, D not expect 
	advanced things like photoshop has :)

***	MenuX and MXM multigame wizards, now they have their own tabs

***	ISO creation and extraction, a better way of creating of true xbox iso images and
	extracting them.

***	Aborting of a progress at any time is now possible. In the item list you can see
	the status of an item(waiting, done, error, aborted, active)

-------------------------------------------------------------------------------------------

version 1.x.x
-------------------------------------------------------------------------------------------
This version began with Multigame Wizard then it became a simple extractor/creator program
with multigame option.
