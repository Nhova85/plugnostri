
 DragonFly´s Icon Format
-------------------------

This is a simple Photoshop Format Plug-in to read and write Windows Icon files (*.ico).

It should work with any photoshop 3.0+ compatible host under Windows 95/98/NT.

To install this plug-in simply copy it into your host´s (i.E. Photoshop)
standard Plug-In directory.

This plug-in is freeware.


I intended to make this Format Plug-in a usefull tool to edit Icon files and maybe
and other icon resources such as dll´s or exe´s.
Unfortunatly the photoshop filter format does not supply all the information i
need. So this version is only usefull for reading and writing *.ico files.

*******************************************************************************
* WARNING: This plug-in is NOT able to handle more than one icon image when   *
* saving. So when you save an image to an allready present icon file          *
* all images stored within this file will be lost! This Plug-in is only able  *
* to save images as single icons!!!                                           *
* This is because i found no way to get ps grant me access to the file to     *
* be overwritten.                                                             *
* I do not take responsibility for any loss of data this plug-in might cause! *
*******************************************************************************


You may redistribute this filter as long as you do two things:
1st: Mail me at 'DragonPhil@gmx.de' and tell me.
2nd: Distribute the unmodified files only together as one including this text file.

Until now i have not recieved any bug reports reguarding the read/write routines.
Anyway, i had no good description of the format so it might still be possible
there are bugs in there. Please mail me if you have discoverd any, or for any
other reason.

If you have a good idea for a new Plug-In.... i´m VERY interested.

Philipp Spöth
(DragonPhil@gmx.de)



------------------------------------------------
              USAGE

This Plug-in enables you to save your pictures either from RGB
or 8Bit(grayscale or indexed colors) mode.
Images saved from RGB pictures will be saved as 24 Bit Icons.
The other in 8 Bit.
Note that though the plug can read Icons with 4,2 or 1 Bit depth
there is no option to save them in those resolutions.

Icons are stored with additional transparency information so the
systems knows which pixels are visibile.
You can edit this layer by using an alpha plane where a non Zero
value indicates the corresponding pixel is transparent.
When saving the first alpha plane is considered the transparency layer.
If there is no alpha plane the whole image is considered opaque.

You can save images at all sizes, while windows seems not
to be able to display all of them properly.
I don´t know which resolutions are appropriate for which useage.
If anyone does he could mail me a description, so i could include
it here.



