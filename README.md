# Finding Lane Lines on the Road 
<img src="laneLines_thirdPass.jpg" width="480" alt="Combined Image" />

## Overview
In `P1.ipynb` we implement a basic lane line detector for straight lane lines
The steps involve 
* conversion to gray scale
* masking a region of interest
* applying Canny edge detection 
* using a Hough transform to collect lane line segments
* reprojecting the detected lane lines back onto the original image
* applying the pipeline to a sample video


When we drive, we use our eyes to decide where to go.  The lines on the road that show us where the lanes are act as our constant reference for where to steer the vehicle.  Naturally, one of the first things we would like to do in developing a self-driving car is to automatically detect lane lines using an algorithm.
In this project we will detect lane lines in images using Python and OpenCV. All documentation is provided in the notebook
`P1.ipynb`. The result of the pipeline on videos can be seen for a white lane lines in `white.mp4`, for yellow lane lines in `yellow.mp4` and for a more complicated example with shaded areas in `extra.mp4`, which illustrates the problem with this approach under changing lighting conditions.


## Dependencies
* Python 3
* numpy, matplotlib, opencv, jupyter
