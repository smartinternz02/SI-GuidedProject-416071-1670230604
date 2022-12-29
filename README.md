
High Quality Facial Recognition System

# SI-GuidedProject-416071-1670230604
Overview
____________________________________________________________________________________________________________________
Facial recognition is the process of identifying or verifying the identity of a person using their face.
It captures, analyzes, and compares patterns based on the person's facial details. High-Quality Facial 
Recognition System has many applications starting from mobile phones to security cameras. The face 
detection process is an essential step as it detects and locates human faces in images and videos.

The objective of this project is to build a Facial Recognition application that can detect faces and recognize them. 
We are going to build this using dlib which uses 128 point face detectors which outputs these 128 points from all the
face and compares them with existing faces.


Learning Objectives/Prior Knowldge
____________________________________________________________________________________________________________________
Before we get started,make sure you have a dictionary understanding of following 
Concepts:
Python Basics
OpenCV
Deep Learning
Computer Vision
Command Line Arguments 
Flask Web Framework

Neccessary Installations
___________________________________________________________________________________________________________________
Python: https://www.python.org/downloads/
Anaconda:https://www.anaconda.com/downloads
OpenCV:https://pypi.org/project/opencv-python/
Imutils:https://pypi.org/project/imutils/
Argparse:https://pypi.org/project/argparse/
Dlib:https://pypi.org/project/dlib/
Cmake:https://cmake.org/download/


Task
____________________________________________________________________________________________________________________

  Phase-1
  _________
Import necessary packages
Construct an argument parser and parser the arguments
Initialize known encodings and known names lists 
Access the paths to the input images present in our data and loop over it 
Load each input image and convert it from OpenCv to dlib
Detect coordinates of bounding boxes
compute facial embedding and extract the names to store in the lists 
Write the encoding and names to the disk

  Phase-2
  ________
  Create a Flask App
  Save the uploaded image in uploads folder
  Read the image uploaded and convert its ordering 
  Load known faces
  determine the recognized face with largest count and update the name
  
  Run command
  _____________________________________________________________________________________________________
  
  1.Open the anaconda prompt cmd path
  Type:pthon flaskname.py
  Result
  ________________
  
Uploaded in outputimages Folder

