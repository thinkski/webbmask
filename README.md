webbmask
========

A Webb mask is a transparency that you overlay on the screen of an oscilloscope
to be able to measure the phase between two signals. Newer digital scopes have
this functionality built-in, but older analog scopes need a Webb mask.

This tool prints such a Webb mask customized to the size of your scope screen.
It is written in PostScript, a language in which it is straight-forward to
specify actual printed sizes. It was written as an extra credit assignment for
EE 113: Feedback and Control Circuits.

To customize the mask for your oscilloscope, measure the size of your display.
It is assumed the size is square. Then open the webbmask.ps file in a text
editor and look for the following lines:

 % screen size in inches
 /screen 5 def

 % display size in inches
 /screen 4.5 def

Change these to match your oscilloscope. Then open the file with your favorite
Postscript or PDF viewer and print it onto a transparency. Cut it out and lay
it on your oscilloscope screen, using a bit of tape if necessary to keep it
in place.

Contact
=======

Questions, feedback, etc. should be sent to Chris Hiszpanski <chiszp@gmail.com>
