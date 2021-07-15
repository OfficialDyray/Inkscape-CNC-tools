# Inkscape-CNC-tools
I will work on this extension more when I get the time. My goal for this is to develop tools for preparing paths to be CNC'ed. I also plan on updating it for the latest versions of inkscape.
## Rounded Corners
Inkscape extension for rounding off the corners of straight-edged polygons

Note: This plugin is not compatible with Inkscape 1.0+ due to plugin API changes.

Rounded Corners is an extension written for Inkscape.
This effect is designed to round off the corners on shapes made with the pencil tool. It will round off corners made of straight edges, while ignoring bezier lines. Corners that are too short for the desired radius will also be ignored. It does not work on Inkscape objects like the rectangle or star - the user must convert objects to paths before using this extension.

Installation:
Copy the files RoundedCorners.inx and RoundedCorners.py into the Extensions folder in your Inkscape directory. On windows, this is located at C:\Users[username]\AppData\Roaming\inkscape\extensions. Alternatively it can be copied to C:\Program Files\Inkscape\share\extensions.
on linux, the folder is generally located at ~/.config/inkscape/extensions.

Usage:
Select or create a polygon in Inkscape using the pencil tool
Click Extensions->Modify Path->Rounded Corners.
Fill out the options in the dialog that pop up
Choose the radius for rounding
Pick units (Inches, centimeters, etc.)
pick whether you want left corners, right corners, or both to be rounded
select "Live preview" to see how your selections affect the shape before applying
Click Apply.

MIT License
Copyright (c) 2018
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), 
to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, 
and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, 
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
