# Facial Recognition - AIML Final Project

Facial recognition–based attendance tracking system for educational environments. 

# Project Description:

Our smart attendance system is designed to offer real-time face recognition and attendance verification. By collecting facial data through a live webcam feed, our system is able to identify students and verify their presence without any manual input. Thanks to the main deep learning components found at the core of our solution, the FaceNet512 pretrained model and the backend detector, RetinaFace, our system is built for robust face detection and reliable attendance verification. We implemented two versions of our prototype:

  1. A standard model.
  2. An augmented model that uses image augmentation techniques to improve recognition in varied lighting and pose conditions.
     
The application includes a user-friendly Tkinter GUI for real-time monitoring, student registration, and attendance export. This project was developed in Python, with a focus on accessibility, affordability, and scalability for small to mid-sized educational institutions.

# Requirements:

To be able to run our program, make sure you have the following elements installed:

  - Python 3.8+
  - A functioning webcam
  - Basic hardware (standard laptop)

Libraries - In order to run our program we will use the following libraries, we explain how to install them in the **Installation** section:

  - deepface
  - opencv-python
  - pandas
  - numpy
  - scikit-learn
  - tkinter (usually included with Python)

# Installation:
   
Step 1. Download the ZIP file, and Extract the ZIP  (https://github.com/nour-farhat/Face-Recognition-Project-/blob/092207b5193cf4ed73f39d781250da6ec3e32e6c/FaceRecognition.zip)

Step 2. Open the terminal

Step 3. Set the directory according to file location: cd path/to/FaceRecognition

Step 4. Install required libraries with: pip install -r requirements.txt

Step 5. Start the GUI App with: python main.py

# Usage:

Once launched, the application interface provides the following functionalities:

1) Register user(s):

- Prompted to enter name
  
- Takes 3 webcam snapshots (front, left, right)
  
- In the augmented version, each image undergoes lighting and blur transformations
 

2) Start of attendance monitoring:

- Starts real-time webcam feed
  
- Detects and verifies students as they appear

- Automatically marks students present, late, or absent based on entry time


3) Exporting Attendance into CSV:

- Attendance data is displayed in a table on your Python IDE
  
- Option to export as CSV file


5) Additional Features:
   
- Continuous access verification (entrance simulation)
  
- Load public datasets 
  
- Clear user database

# Credits:

The authors for this project are:   

- Clementine Mathieu 
- Andrea Saxod
- Hugo Marsiglia
- Rakan Hourani 
- Nour Farhat

# SOME EXTRA INFORMATION ABOUT THE CODE

This project was created as part of our AI-machine learning and analytics course final project in April 2025.
It explores practical applications of deep learning, specifically face detection and recognition in education and proposes a scalable, real-world solution for a recurring institutional problem.


