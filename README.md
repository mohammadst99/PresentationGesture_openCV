# PresentationGesture_openCV
in this prj you can control your presentation Slide with just your hand to present better in quality 

# Libraries

from cvzone.HandTrackingModule import HandDetector

import cv2

import os

import numpy as np

> you have to install ( opencv-python , pip , numpy )
> my python version was 3.8

# Test Video
gesture is :
> thumb finger to back (previous slide)
> 
> small finger to go to the next slide
> 
> index and middle finger to show curser on the page
> 
> index finger to writing
> 
> three finger to clear your writing 


![](https://github.com/mohammadst99/PresentationGesture_openCV/blob/main/test.gif)


# Explain Code

first we have to import our webcam using cv2 

then we have to use the nodule handTracking that we wrote before 

then we have to detect the hand ( is there any hand or not)

is the hand was available we have to detect which finger is up 

then we can do diffrent command for each finger position
