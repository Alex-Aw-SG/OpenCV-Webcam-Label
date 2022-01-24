# OpenCV-Webcam-Label

## **Project Overview**   
Using OpenCV package for image conversion, facial recognition, data training and identify images. Objective is to have the script correctly identify the person via live webcam and label it. The project is broken down into 4 tasks for different functionalities as described below. Each task is a build up to the subsequent task.    
For more information about OpenCV, please visit https://opencv.org.   
Used in this project was haarcascade_frontalface_default.xml. For more options visit https://github.com/opencv/opencv/tree/master/data.   
To replicate the script result, put training images into folder 'training_images', with sub-folders of 'data0', 'data1', etc, of different individuals in each folder, including your own.   

### **Task 1 - Face Recognition**   
Main functions will be built here that will be used for the subsequent tasks. The main objectives are as follows:   
- Converting images to gray scale   
-	Return face rectangle dimension   
-	Creating list for appending faces and labels   
-	Training haar classifier   
-	Append text/name on image   

### **Task 2 - Face Testing**   
The objective of this activity is to call the classifier to read through the database of image and save the training to yml file. Using a training image as sample, have the code to identify the image by putting a rectangle and name to the image.   

### **Task 3 – Video to Image**   
The code is to open the front facing camera and capture still images saving it to an output folder. Pressing SPACEBAR will terminate the function.   

### **Task 4 – Live Testing**   
Using the previously trained yml file, predict the identity of the image. When confidence level is above 40%, a label will be attached to the image on screen.
