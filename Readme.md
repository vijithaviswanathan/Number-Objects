Counting the objects in the iamge using Python and OpenCV

## Steps involved:

 1.Image Preprocessing

     Load the image using OpenCV's imread function and convert the loaded image to grayscale using cvtColor.

2.Object Detection
    
    Use the findContours function to detect contours in the binary image. Each contour corresponds to a detected object.

3.Counting Objects

    Loop through each contour and count them. Each contour represents a distinct object in the image.

4.Display Output