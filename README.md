# Contactless-Biometric-Attendance-System

Contactless Attendance recording is a three-step process namely face detection, followed by face recognition and finally if a registered person then marks the attendance. This proposed system detects and recognises faces using deep learning algorithms by using a camera to take pictures of an individual. When a match is made in the face database, then attendance is marked of the recognised person with name, date and time. Deep learning method ie.e MTCNN is used to compute and compare features of different real-time input images to accurately recognize them. Once the recognition step is done, attendance of the respective recognized person will be marked in an excel sheet. 

## Environment Setup

The virtual environment used for the application contains the following version of dependencies:

1. Python : version  '3.7.10’'
2. Tensorflow : version  '1.15.0'
3. Keras : version  '2.3.0' 
4. Pandas: version ‘1.2.4’
5. SqlLite3 : A module named "sqlite3" which is a transactional, self-contained, serverless, zero-configuration database engine, is included in the Python Standard Library for 6. working with the database. 
7. Tkinter : Tkinter is a Python package for the Tk graphical user interface toolkit. Version used '8.6'
8. OpenCV : version '4.5.1'

## Application

To use the application clone the repository and run face_app.py script after creating the virtual environment.
