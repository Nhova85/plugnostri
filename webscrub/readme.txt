Web Scrub Filter

This filter protects images against the measels.  Images catch the measels
when viewed with Netscape in 256 colour mode.  If the image contains a
colour that is very close to the browser-safe 216 colours, the colour
will be lightely dithered.  This dithering causes most pixels of the
offending colour to change to a browser-safe colour, with a few not in
some different colour, to preserve the tone (see
http://www.verso.com/agitprop/dithering/ for more detail).

What this filter does is snap all colours that are "close" to the
browser-safe palette so that they are dead-on.  The Grit slider (ctl(0))
controls what is considered "close".  A grit of 10 will snap colours
that are 51+-5, 102+-5, 153+-5, 204+-5 to the respective center values.
Note that values greater 15 aren't very usefull and that values greater
than 51 make no sense.

Also, this filter only works with RGB images.  When you convert the
image to "Indexed color", Photoshop will shift the colours slightly,
which is EXACTLY what we're trying to avoid.  I here tell there's a way
to get Filter Factory to work with other image modes, but I haven't
looked into it.  So images should be converted from RGB to gifs with
another tool.

Algorythm orignaly developed by Verso (http://www.verso.com/).
