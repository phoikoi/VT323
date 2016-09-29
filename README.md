# VT323 Font Project
by Peter Hull

<p>This font was created from the glyphs of the DEC VT320 text terminal, which I used in college, and for which I have retained an unaccountable nostalgia.</p> <p>I used a variety of tools, including Gimp, Python/PIL, and of course, FontForge.  The VT320 glyphs were designed with a nonrectangular pixel aspect ratio to fit the way the terminal scanned the CRT, so for this VT323 variation I had Python munge the locations and attempt to emulate the way the electron beam actually illuminated the phosphor and smeared the pixels horizontally on the terminal's CRT, so it looks more like what the actual glyph looked like on the screen. Python then drew the proper pixels into a 1:1 pixel grid as a monochrome PNG, which FontForge autoscanned into outlines.  I have attempted to support most of the glyphs available on the VT320, but that is a limited set to begin with, so please don't be disappointed that I haven't supported Esperanto or Riograndenser Hunsrückisch or whatever.</p> <p>There is another earlier variation called "VT321" that uses a more standard 1:1 pixel drawing technique, if you want to grab that as well.  I personally like VT323 better, and actually use it as my terminal font when cruising on the command line.</p>

This font is [available on Google Web Fonts.](https://fonts.google.com/specimen/VT323)

Contributions are welcome, subject to the SIL Open Font License v1.1, as set forth in OFL.txt in this repo.

I'm sorry I can't provide more of the original Python source for this
typeface, but a disk crash consigned the source to the great bit bucket
in the sky, in the era before I started using Github.

