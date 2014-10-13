
 DragonFly´s Cursor Format
-------------------------

This is just a quick hack of the icon plug-in. It only needed minor changes to
allow it to process *.cur files.

This is a simple Photoshop Format Plug-in to read and write Windows Cursor files (*.ico).

It should work with any photoshop 3.0+ compatible host under Windows 95/98/NT.

To install this plug-in simply copy it into your host´s (i.E. Photoshop)
standard Plug-In directory.

This plug-in is freeware.

*******************************************************************************
* WARNING: This plug-in is NOT able to handle more than one cursor image      *
* when saving. So when you save an image to an allready present cursor file   *
* all images stored within this file will be lost. This Plug-in is only       *
* able to save images as single cursors!!!                                    *
* This is because i found no way to get ps grant me access to the file to     *
* be overwritten.                                                             *
* I do not take responsibility for any loss of data this plug-in might cause! *
*******************************************************************************

You may redistribute this filter as long as you do two things:
1st: Mail me at 'DragonPhil@gmx.de' and tell me.
2nd: Distribute the unmodified files only together as one including this text file.

Philipp Spöth
(DragonPhil@gmx.de)

------------------------------------------------
              USAGE

This Plug-in enables you to save your pictures either from RGB
or 8Bit(grayscale or indexed colors) mode.
Images saved from RGB pictures will be saved as 24 Bit Cursors.
The other in 8 Bit.
Note that though the plug can read Cursors with 4,2 or 1 Bit depth
there is no option to save them in those resolutions.

Cursors are stored with additional transparency information so the
systems knows which pixels are visibile.
You can edit this layer by using an alpha plane where a non Zero
value indicates the corresponding pixel is transparent.
When saving the first alpha plane is considered the transparency layer.
If there is no alpha plane the whole image is considered opaque.

The second alpha plane is used for the cursors hotspot. Simply
put a single pixel where you want the hotspot to take effect.
(the brightest pixel is used as hotspot.)
If no second alpha plane is available tthe hot spot is set
to the upper right corner.

You can save images at all sizes, while windows seems not
to be able to display all of them properly.
I don´t know which resolutions are appropriate for which useage.
If anyone does he could mail me a description, so i could include
it here.




