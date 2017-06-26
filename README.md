# Draw-Shapes-Using-Gesture-Opencv-Python
This program is develop to draw shapes using gesture , it detect three colors only GREEN , RED and BLUE and follow it.
Module requires are cv2 and numpy only.

# How it works
a. First image is filter by HSV color basis to detect any three color RED , BLUE and GREEN.</br>
b. Then with help of findContours we find shapes.</br>
c. Then take one of the coordinate and append it to list and so on.</br>
d. Take each item from list and plot 1unit radius circle.</br>
