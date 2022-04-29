# rubiks-cube-scanner
It uses opencv python to take images of a jumbled rubiks cube from webcam and gives a series of solution to solve it

You must scan the sides in U,L,F,R,B,D
(Upper center): WHITE
(Left center): ORANGE
(Front center): GREEN
(Right center): RED
(Back center): BLUE
(Down center): YELLOW

Press ENTER after scanning all sides
Solution will apppear on command line

If the colors are not calibrated properly for your cube and camera use hsv_trackbar.py file 
to calculate the upper and lower hsv limits of each color and change them in the main.py
color_detect(h, s, v) function for each color
