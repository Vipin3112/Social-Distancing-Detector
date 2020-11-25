# Social-Distancing-Detector
Social Distancing Detector using yolov3 convolutional neural network

1. Detect the humans in the frame with yolov3 convolutional neural network.
2. Calculate the distance between all the instances of humans detected in the frame.
3. Classify the determined distances as 'Alert' or 'Ok' for social distancing.



# Requirements

Numpy
Time
OpenCV
OpenCV_contrib
Math
Download yolov3.weights for COCO dataset from this link and add it to the yolov3 directory,
 https://pjreddie.com/darknet/yolo/
 
 
# Steps to run the code:

cd social-distance-detector

To deploy algorithm, python3 detection.py.py

social_distancing_config.py: A Python file holding a number of constants in one convenient place.

detection.py: YOLO object detection with OpenCV involves more lines of code that some easier models. 
I’ve decided to put the object detection logic in a function in this file for convenience. 
Doing so frees up our driver script’s frame processing loop from becoming especially cluttered.
