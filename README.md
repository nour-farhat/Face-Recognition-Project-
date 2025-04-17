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

Libraries - In order to run our program, we make use of the following libraries: 

  - deepface
  - opencv-python
  - pandas
  - numpy
  - scikit-learn
  - tkinter (usually included with Python)
        To download the library type the following command:   
    ```pip install deepface opencv-python pandas numpy scikit-learn ``` 

# Installation:
  
Now that the required library is set up, Follow these final steps to download the zip file from the repository:
 
Step 1. Open the PennyPlanner_Final.py.zip file

Step 2. Download the ZIP

Step 3. Import the ZIP file in your IDE environment and simply run the code

The code can also be imported into an online IDE environment, such as Google Colab. As our code doesn't rely on any datasets, you shouldn't encounter any issues during the import and execution process.

# Usage:

After a user enters our platform:

1) They will be welcomed and asked for their monthly budget (users will not be able to enter a number lower or equal to 0).
 

2) Customized categories and allocation amounts: Users will be prompted to input their chosen personalized category and the desired monetary allocation for that category. Upon completion of category creation, users can signify completion by entering "done."


3) Visualization of user's budget: After completing the previous steps, users will encounter a pie chart illustrating the distribution of their allocated funds among various categories. Additionally, an automated savings category will be generated, displaying the amount saved if the total budget was not fully allocated.


4) Expense tracking and history: Finally, users will be prompted to input their expenses within the designated category they created, and they will receive an overview of their expense history. Users will need to input the name of a category they have created and the corresponding expense amount.

This video will give you a quick tutorial on how to use the application:
https://drive.google.com/file/d/1noesa8NmtBWf-e-t1dqDPuW9gzX6gd8e/view?usp=drive_link

# Credits:

The authors for this project are:   

- Clementine Mathieu 
- Daniel Teixidor
- Jimena Navarro
- Rakan Hourani 
- Nour Farhat

# SOME EXTRA INFORMATION ABOUT THE CODE

In order to carry out our objective, we have used the following data structures and algorithms:

  1. Hash Tables - Used to store all details regarding the opportunities
  2.  Dictionaries -Used to store budget information, where keys represent expense categories, and values represent the budget allocated to each category
  3. Lists
  4. Quicksort Algorithm 


