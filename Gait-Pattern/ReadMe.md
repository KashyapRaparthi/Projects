# Description
Gait analysis is an assessment of the way the body moves, usually by walking or running, from one place to another.
The purpose of gait analysis is to detect any abnormalities in locomotion. The proposed project aims to develop a computer vision
based camera system for capturing gait patterns of human subjects. A Python script will be used to estimate human pose from the 
live feed of the camera, and the obtained pose estimate will be used to calculate the angle between different joints. Here we used
MediaPipe library to abstract the features/coordinates of the joints from live feed.The estimated pose will then be exported 
to the Unity platform to create a human skeleton. 
