# rubiks-cube-scanner
It uses opencv python to take images of a jumbled rubiks cube from webcam and gives a series of solution to solve it

You must scan the sides in the order U,R,F,D,L,B

(Upper center): WHITE   Press U for scanning

(Right center): RED     Press R for scanning

(Front center): GREEN   Press F for scanning

(Down center): YELLOW   Press D for scanning

(Left center): ORANGE   Press L for scanning

(Back center): BLUE     Press B for scanning

Press ENTER after scanning all sides
Solution will apppear on command line

If the colors are not calibrated properly for your cube and camera use hsv_trackbar.py file 
to calculate the upper and lower hsv limits of each color and change them in the main.py
color_detect(h, s, v) function for each color
