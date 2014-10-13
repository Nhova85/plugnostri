
DragonFly´s Sinedots II V1.03
------------------------------

This Filter is an extended Version of my first Filter called Sinedots.
Mayor new features are Antialiasing, color support and slightly more control.
I decided to enhance it due to the enourmous positive response.

If you do some interesting work with this filter I am interested to see
the results. So please don't hesitate to show me. Interesting settings are
also welcome.

Another very important part is the Interface. Actually this filter is a
testbed for the framework of my forthcoming commercial filterpack.

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
  look at my page at www.Philipp-Spoeth.de for a new Version. I'm trying to make my
  this plugin compatible with as many hosts as possible.


Parameters:
----------

The filter calculates picture positions from a simple mathematical formula.
The image is then altered at those positions according to the selected color.

add factor:     determines how much of the color value is added to the image
                at each calcualated position.

inner density:  how much positions are calculatd on the 'inner dimension'
outer density:  how much positions are calculatd on the 'outer dimension'

Inner Angles
Outer Angles:   Determines the positions distribution pattern.

Offsets:        Angle Offsets

weight x1-x2
weight y1-y2:   Defines the influence of X-1/Y-1 values relativ to X-2/Y-2

Randomize:      The Randomize button generates random values for each of the
                Angle Parameters and the both Weight Values.
                The Randomize Sliders determins the maximum random value
                that will be generated in terms of rounds.

antialias:      enables non perfect antialias
clip color:     color is not allowed to exeed the selected color.

gamma:          gamma correction
blend:          the Filter generates the sinedots pattern on a black background.
                the blend modes determines how that image is blended the the
                input image.
color:          :) color


Interface:
----------

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

'FileOwner SinedotsII'

Unfortunatly it is not possible to load settings from the old Version of Sinedots.



Installing:
----------

Just copy it to your plugins directory and restart Photoshop or
whatever host application you are using.

In 'Sinedots' there was an installer and an exe that created some
extra registry entries. That was a clumsy solution and therefor
they are now created automatically from within the plugin itself.


Deinstalling:
-------------

In addition to removing the file from your plugins directory you can
remove the follwing registry entriy from your system:

"HKEY_CURRENT_USER\SOFTWARE\DragonFly\Photoshop\SinedotsII"

The settings in that directory have been used to keep the position
of the interface windows and the location of the current setting file.
Those entries won't harm your system but will slightly increase the
size of your registry files.

In order to remove this key click 'Start', select 'run' and enter
'regedit. In that app browse the key and delete it.




History:
--------

// 
// 13th of October 2001 - Version 1.02 :
// - added compatibilty with several new host applications
// - fixed Offset dials not moving on windows 98, me
// - fixed preview mask error in psp
// - fixed double mask blending bug in psp
// - added undo/redo
// - last used settings are now loaded on start
//   for hosts besides Photoshop.
// - added settings file with the entries of the PSP_Pluggers newsgroups
//   Sinedots settings contest
//

// 
// 11th of October 2001 - Version 1.01:
// - added Randomize Button
// - fixed windows initial starting positions
// - fixed a couple of smaller and one serious bug.
//

//
// 10th of October 2001 - Version 1.0:
//   Initial release
//




