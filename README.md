♦♦♦♦__♦♦♦♦♦_♦♦♦♦♦_______♦___♦__♦♦♦__♦♦♦♦♦_♦♦♦♦____♦___♦___♦_______♦♦♦♦__♦♦♦♦____♦___♦___♦_♦♦♦♦♦_♦♦♦♦♦_♦♦♦♦__
_♦__♦_♦___♦___♦_________♦♦_♦♦_♦___♦___♦____♦__♦___♦___♦___♦________♦__♦__♦__♦___♦___♦♦__♦___♦___♦______♦__♦_
_♦__♦_♦___♦___♦_________♦♦♦♦♦_♦___♦___♦____♦__♦___♦____♦♦♦_________♦__♦__♦__♦___♦___♦♦♦_♦___♦___♦______♦__♦_
_♦__♦_♦___♦___♦_________♦_♦_♦_♦♦♦♦♦___♦____♦♦♦____♦_____♦__________♦♦♦___♦♦♦____♦___♦_♦_♦___♦___♦♦♦♦___♦♦♦__
_♦__♦_♦___♦___♦_________♦___♦_♦___♦___♦____♦♦_____♦____♦♦♦_________♦_____♦♦_____♦___♦_♦♦♦___♦___♦______♦♦___
_♦__♦_♦___♦___♦_________♦___♦_♦___♦___♦____♦_♦____♦___♦___♦________♦_____♦_♦____♦___♦__♦♦___♦___♦______♦_♦__
♦♦♦♦__♦♦♦♦♦___♦_________♦___♦_♦___♦___♦____♦__♦___♦___♦___♦________♦_____♦__♦___♦___♦___♦___♦___♦♦♦♦♦__♦__♦_
____________________________________________________________________________________________________________ 

This is simple javascript demonstration that let's you take an alphanumeric phrase and print it out in a matrix. 
You can view a functioning version of this code at http://technecreative.com under the Code section or a stand alone 
version at http://technecreative.com/DotMatrixPrint.html.

Unlike LED matricies where the display can rely on persistance of vision this example requires the entire character
to be stored as a set of 5 columns stacked 7 wide, plus one column for spacing. This creates a 5x7 dot matrix "font". 
This has been achieved using a 3 dimensional array. Each character has an array consisting of 5 columns. Each column 
is in turn a binary array of weather that "pixel" is on of off. Next the input string is parsed and compaired to each
character in the "font" array. Then each row is read, while jumping between each character so line breaks only happen 
at the end of the row. This has the advantage that if you want to copy and paste the phrase you can do so directly 
without any ordering issues as seen above. Also included in this repository is the array list for each character as 
well as the binaries (not literally binary just the list of 1s and 0s for each "pixel") written out without any commas 
or brackets.

Enjoy.
~Reversenorm


