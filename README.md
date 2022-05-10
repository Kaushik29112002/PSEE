# PSEE
Myself KAUSHIK KIDECHA From BTech CE 4th Semester

I am here to present " STUDENT ATTENDENCE SYSTEM USING QR CODE "

from MyQR import myqr

There is a very interesting and fun library MyQR in Python, which can not only make all kinds of beautiful QR codes, but also generate dynamic color QR codes.

MyQR is a third-party library that can generate custom QR codes. You can generate ordinary QR codes, artistic QR codes with pictures, or dynamic QR codes as needed.

import os

The OS module in Python provides functions for interacting with the operating system. OS comes under Python’s standard utility modules. This module provides a portable way of using operating system-dependent functionality. The *os* and *os.path* modules include many functions to interact with the file system.

import base64

The Base64 encoding is used to convert bytes that have binary or text data into ASCII characters. Encoding prevents the data from getting corrupted when it is transferred or processed through a text-only system. In this article, we will discuss about Base64 encoding and decoding and its uses to encode and decode binary and text data.

generate.py

It creates and read data from students.txt file and generate QR Code of data stored in students.txt file.
Encodes the data from students.txt and generates QR Codes.

import cv2

cv2 is the module import name for opencv-python, "Unofficial pre-built CPU-only OpenCV packages for Python". The traditional OpenCV has many complicated steps involving building the module from scratch, which is unnecessary. I would recommend remaining with the opencv-python library.

CV2 is an important security feature for credit card transactions on the Internet and over the phone. “CVV” stands for “Card Verification Value”. It is the three-digit number printed in the signature space on the back of most credit cards, such as Visa, Mastercard, and Discover cards.

import numpy as np

The import numpy portion of the code tells Python to bring the NumPy library into your current environment. The as np portion of the code then tells Python to give NumPy the alias of np. This allows you to use NumPy functions by simply typing np. function_name rather than numpy.

import pyzbar.pyzbar as pyzbar

Based on the official documentation, pyzbar is. “… a pure Python library that reads one-dimensional barcodes and QR codes using the zbar library, an open source software suite for reading bar codes from various sources, such as video streams, image files and raw intensity sensors.

import sys

Python sys module
The python sys module provides functions and variables which are used to manipulate different parts of the Python Runtime Environment. It lets us access system-specific parameters and functions.

import sys

First, we have to import the sys module in our program before running any functions.
sys.modules
This function provides the name of the existing python modules which have been imported.

sys.argv
This function returns a list of command line arguments passed to a Python script. The name of the script is always the item at index 0, and the rest of the arguments are stored at subsequent indices.

sys.base_exec_prefix
This function provides an efficient way to the same value as exec_prefix. If not running a virtual environment, the value will remain the same.

sys.base_prefix
It is set up during Python startup, before site.py is run, to the same value as prefix.

sys.byteorder
It is an indication of the native byteorder that provides an efficient way to do something.

sys.maxsize
This function returns the largest integer of a variable.

sys.path
This function shows the PYTHONPATH set in the current system. It is an environment variable that is a search path for all the python modules.

sys.stdin
It is an object that contains the original values of stdin at the start of the program and used during finalization. It can restore the files.

sys.getrefcount
This function returns the reference count of an object.

sys.exit
This function is used to exit from either the Python console or command prompt, and also used to exit from the program in case of an exception.

sys executable
The value of this function is the absolute path to a Python interpreter. It is useful for knowing where python is installed on someone else machine.

sys.platform
This value of this function is used to identify the platform on which we are working.

import time

time() The time() function returns the number of seconds passed since epoch. For Unix system, January 1, 1970, 00:00:00 at UTC is epoch (the point where time begins). import time seconds = time.time() print("Seconds since epoch =", seconds)

import pybase64

The Base64 encoding is used to convert bytes that have binary or text data into ASCII characters. Encoding prevents the data from getting corrupted when it is transferred or processed through a text-only system.

from tkinter import*

In order to work with a tkinter application, we have to install and import the tkinter library in our environment. Generally, we import the tkinter library in the environment by using from tkinter import * command. The significance of "import *" represents all the functions and built-in modules in the tkinter library.

root = Tk()

Tkinter is a Python package which comes with many functions and methods that can be used to create an application. In order to create a tkinter application, we generally create an instance of tkinter frame, i.e., Tk(). It helps to display the root window and manages all the other components of the tkinter application.

root.geometry("")

Tkinter is a Python module that is used to develop GUI (Graphical User Interface) applications. It comes along with Python, so you do not have to install it using the pip command.

Tkinter provides many methods; one of them is the geometry() method. This method is used to set the dimensions of the Tkinter window and is used to set the position of the main window on the user’s desktop.

root.title("Attendence Using QR Code")

root = tkinter.Tk() root.title("Attendence Using QR Code") root is the window you create and root. title() sets the title of that window.

What is root configure?
root.configure(background="")
root-config is a tool that is used to configure and determine the compiler and linker flags that should be used to compile and link programs that use ROOT.

cap = cv2.VideoCapture(0)

This will return video from the first webcam on your computer.

cv2.imshow()

What is cv2 Imshow () in Python?
OpenCV-Python is a library of Python bindings designed to solve computer vision problems. cv2. imshow() method is used to display an image in a window. The window automatically fits to the image size.

root.mainloop()

What is root Mainloop () in Python?
root. mainloop() is a method on the main window which we execute when we want to run our application. This method will loop forever, waiting for events from the user, until the user exits the program – either by closing the window, or by terminating the program with a keyboard interrupt in the console.
