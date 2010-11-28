Repainting:

Use a text editor with search and replace function, open the file called "kingair200coloringbase.dnm". There are 13 different parts that needs to be colored before the aircraft can be used in YSFlight. To paint a part, search for the part name and replace it with the RGB value of the color you want. The part names are:

fuselage_color
wing_color
engine_color
tail_color
horizontal_stab_color
window_color
prop_spinner_color
body_line_top_color
body_line_bottom_color
engine_line_top_color
engine_line_bottom_color
rudder_line_top_color
rudder_line_bottom_color

So if you want the fuselage to be white, search for the string "fuselage_color" and replace all instance of it with "255 255 255", the RGB value of white. Once you are done save it under a different name (e.g. "my_kingair.dnm"). If you are using a text editor that can save in different formats (e.g. Windows WordPad or MS Word) make sure you save it as un-formatted text, and use DNM as the extention. Edit the line in the aircraft.lst file (step 3 above) so that the dnm file is using the one that you repainted.

If you want multiple versions of the aircraft just add another entry in the aircraft.lst file (see step 3 above), each pointing to a unique .dat and .dnm file. Make a copy of the original kingair200.dat file and rename it, and use a text editor to edit the first line the begins with "IDENTIFY" so that each version of the aircraft uses a different name. Be careful that YSFlight only recognizes the first 32 characters of the name.

You don't have to paint all the parts in different colors. For example if you paint the two "body_line" colors with the same color as the fuselage, then you will have a fuselage with no lines running along it. Use you imagination!

update:

1 Feb 2006: Improved flight dynamics, mainly to make it more recoverable in a stall. Thanks to Hotelfox of www.cleared4takeoff.de

-----------------------------------------------------

ALL FILES IN THIS ZIP (C)OPYRIGHT 2006 EDMUND HON
taskforce58@gmail.com
http://www.ysflight.ca



