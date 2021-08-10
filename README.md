# Fruit_Detection

The HoughCircles() function finds circles on grayscale images using a Hough Transform.
The name is the same in both python and c ++, and the parameters it takes are the following:

image – Grayscale input image
circles – Output vector of found circles. This vector is encoded as 3-element floating-point vector (x,y,radius). This is only needed in c++
method – Detection method to use. CV_HOUGH_GRADIENT is currently the only available method
dp – Inverse ratio of the accumulator resolution to the image resolution
minDist – Minimum distance between the centers of the detected circles
param1 – In case of CV_HOUGH_GRADIENT , it is the higher threshold of the two passed to the Canny() edge detector
param2 – In case of CV_HOUGH_GRADIENT , it is the accumulator threshold for the circle centers at the detection stage
minRadius – Minimum circle radius
maxRadius – Maximum circle radius.
