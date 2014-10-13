
DragonFly´s Shear
-----------------

Toy Filter I made some once upon a time for AfterFx. I transfered it
to my new Photoshop framework and added support for selection which results
in nice distortions.

The Fitler just performs a Shift on the input image.
You can sepcify the line along which the shift is performed a well as the strength.
If the input image comes with a feathered selection the selection intensity
is multiplied with the strength parameter locally resulting in interesting distortions.
Thus: Please try it with a feathered selection!!!



This filter is free but...

If you intend to redistribute this filter in any commercial way you need my permission first!!!

In all other cases you may redistribute this filter as long as you:
 - Mail me at 'Philipp@Philipp-Spoeth.de' and tell me!!!
 - Distribute the unmodified files only together as one including this text file!

Mail me for any comments, suggestion, bug reports, etc.
I am also interested in good ideas for new Plug-Ins.

Philipp Spöth
(Philipp@Philipp-Spoeth.de)



Features:
---------
  - 16Bit support
  - Scripting Support making it actionable in Photoshop.


Requirements:
-------------
  Photoshop 3.01 compatible host or better.


Problems:
---------
  If this Version of Sinedots does not work with your host Programm please take a
  look at my page at www.Philipp-Spoeth.de for a new Version. I trying to make my
  plugins compatible with as many hosts as possible.


Parameters:
----------

direction:   Direction of the line along the shift takes place
origin:      Origin of the line along the shift takes place.
strength:    Strength of the Shear effect

antialias:   extra antialiasing.
color:       color that is assumed outside the input picture if choosen below
outside:     determines what is assumed outside inputiage


Interface:
----------

Leftclick into the preview image will set the Origins Position.

'+' and '-' buttons increase/decrease the zoom on the preview image.
Right mouse button can be used to drag the image when it is larger than
the preview window.

Leftclick the Color Field to bring up a color requester or
rightclick it to bring up a pippette wich can be used to select colors
from the preview window.

'undo' and 'redo' do what they say.



Loading and Saving of Settings:
-------------------------------

Using the dropdown box at the bottom of the Interface window
and the three butons below it is possible to load and save the
parameters current state in a setting.

The first time you are using it you need to specify the name and position
of a new Settingsfile using the open button.
If you specify a new name that file will be generated. If you use an
existing setting file that one will be opened. This way you can build
different setting files and switch between them.

Pushing the save button will bring up a dialog to request a settings name.
That setting will then be save into the settings file currently opened.

Selecting an entry from the dropdown box will load that setting.

You can open the setting files in a texteditor and see their structur.
If you mess around with them keep in mind that a settings file will not
be recognized unless the first line reads:

'FileOwner Shear'


Installing:
----------

Just copy it to your plugins directory and restart Photoshop or
whatever host application you are using.


Deinstalling:
-------------

In addition to removing the file from your plugins directory you can
remove the follwing registry entriy from your system:

"HKEY_CURRENT_USER\SOFTWARE\DragonFly\Photoshop\Shear"

The settings in that directory have been used to keep the position
of the interface windows and the location of the current setting file.
Those entries won't harm your system but will slightly increase the
size of your registry files.

In order to remove this key click 'Start', select 'run' and enter
'regedit. In that app browse the key and delete it.




History:
--------

// 
// 25th of October 2001:
//   Initial release
//
