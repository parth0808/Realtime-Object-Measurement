# Realtime-Object-Measurement


# Object Measurement
Using the warped image we will find the contours of our objects.
Given that we have a list of contours and their bounding boxes, we can now find the width and the height of our contours. But the problem here is that the object might be tilted so we can just take the width and height of our bounding box. So we can simply find the magnitude using 2 points and a bit of math.

# Contours Function
Contours are defined as the line joining all the points along the boundary of an image that are having the same intensity. Contours come handy in shape analysis, finding the size of the object of interest, and object detection. OpenCV has findContour() function that helps in extracting the contours from the image.

