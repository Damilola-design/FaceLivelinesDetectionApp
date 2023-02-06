# FaceLivelinesDetectionApp
Face Liveliness Detection Application with CNN 


## Description
CRMNet: A deep-learning pipeline capable of spotting fake vs legitimate faces and performing anti-face spoofing in face recognition systems. It is built with the help of Keras, Tensorflow, and OpenCV. A sample dataset is uploaded in the dataset.

## Method
The problem of detecting fake faces vs real/legitimate faces is treated as a binary classification task. Basically, given an input image, we’ll train a Convolutional Neural Network capable of distinguishing real faces from fake/spoofed faces. There are 4 main steps involved in the task:
 1. Build the image dataset itself.
 2. Implement a CNN capable of performing liveness detector(Livenessnet).
 3. Train the liveness detector network.
 4. Create a Python + OpenCV script capable of taking our trained liveness detector model and apply it to real-time video.
 5. Create a webplatform to access the liveness detection algorithm in an interactive manner.
 6. To run the program cd to face_liveness_detection then run "python3 face_recognition_liveness_app.py -m MODEL -l LE -d FACE_DETECTOR"
