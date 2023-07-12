# Licence-Plate-Characters-Recognition-and-Sorting using YOLO-V7

# Introduction : 
In this project i will implement the Characters Detection and Recognition using state of Art Algorithm Using YOLOv7. This is a part of my project for detection of Vehicle and Licence Plate Recognition for Loggong Maintanance to show how I did the licence Plate Characters Sorting.

# Problem Statement :
Although YOLOv7 is responsible for accurrate detection which it does but it sort the detected characters by measure of confidence so we are chalenged to sort them accurately by reference of their position to maintain accurate information of Vehicles.

# Methodology :
1 . Detect the characters individually
2 . Get the position of Detected Characters using tensor xyxy
3 . Sort them according to postion
4 . Separate Alphabets and Numbers

# How To Run Inference :
You can run inference with your own image by following Steps
Make sure you have fulfilled all the requirements
1 . Import your images to testimages.
2 . Goto lp_characters.py python file and change the image name accordingly.
3 . If you want to test it with your own trained model name your model by char-tiny.pt and insert it in main directory.
4 . Run directly the lp_characters.py or by cmd.
