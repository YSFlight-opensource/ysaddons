Repainting:

Use a text editor with search and replace function, open the file called "eclipsecoloringbase.dnm". There are 8 different parts that needs to be colored before the aircraft can be used in YSFlight. To paint a part, search for the part name and replace it with the RGB value of the color you want. The part names are:

bodycolor
canopycolor
spinnercolor
line1color
line2color
line3color
line4color
line5color

The cheatline running along the fuselage is subdivided into 5 parts, numbered 1 to 5 from the top.

So if you want the body to be white, search for the string "bodycolor" and replace all instance of it with "255 255 255", the RGB value of white. Once you are done save it under a different name (e.g. "my_eclipse.dnm"). If you are using a text editor that can save in different formats (e.g. Windows WordPad or MS Word) make sure you save it as un-formatted text, and use DNM as the extention. Edit the line in the aircraft.lst file (step 3 above) so that the dnm file is using the one that you repainted.

If you want multiple versions of the aircraft just add another entry in the aircraft.lst file (see step 3 above), each pointing to a unique .dat and .dnm file. Make a copy of the original eclipse.dat file and rename it, and use a text editor to edit the first line the begins with "IDENTIFY" so that each version of the aircraft uses a different name. Be careful that YSFlight only recognizes the first 32 characters of the name.

You don't have to paint all the parts in different colors. For example if you paint the "line1color" and "line5color" colors with the same color as the body, then you will have a body with a narrower line running along it. Use you imagination!

-----------------------------------------------------

ALL FILES IN THIS ZIP (C)OPYRIGHT 2006 EDMUND HON
taskforce58@gmail.com
http://www.ysflight.ca



