°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°
°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°
Advanced Country Flags by Commander (c)MaxMinds
°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°
°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°

-----------------------------------------------
General information concerning the properties
-----------------------------------------------
- 248 32/24bit flags
- the flag itself's size: 18*12 + each 2px transparent border at top and bottom (18*16)

-----------------------------------------------
Instructions to compile the countryflag libary
-----------------------------------------------

The problem:		
------------

- Win9x:	Win9x systems just support icons up to 24bit only. 

- WinXP/2000:	Windows XP and 2000 support icons up to 32bit + a special 'Alpha channel'.
		In contrast to Win9x and the 24bit version of the flags, these ones look much better and the wave-effect is perfectly drawn.


I.) Building the libary for Windows XP/2000

The name of the dir in the flag project is 'res'. There are actually 2 folders named 'res32' and 'res24'.
In order to compile the 32bit version just rename ~/res32/ to ~/res/, start the project and build the dynamic build of the libary.
After a few seconds, the compile process is finished and you will find the lib called 'countryflag.dll' in ~/Dynamic/.
In order to make Morph using it, you have to rename the 'countryflag.dll' to 'countryflag32.dll' and place it in your config dir of emule.

II.) Building the libary for Win9x (Windows 98,Windows Me)

The name of the dir in the flag project is 'res'. There are actually 2 folders named 'res32' and 'res24'.
In order to compile the 24bit version just rename ~/res24/ to ~/res/, start the project and build the dynamic build of the libary.
After a few seconds, the compile process is finished and you will find the lib called 'countryflag.dll' in ~/Dynamic/.
In order to make Morph using it, you have to place it in your config dir of emule.

Note: Morph will detect your OS version and choose the correct one automaticly.

-----------------------------------
For questions concerning the flags:
-----------------------------------
eMail:	commanderger@users.sourceforge.net 	

Last update: 23.07.2004
	

