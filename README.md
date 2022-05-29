# Attendance-system
An attendance system which utilizes facial recognition to mark the presence, time-in, and time-out of employees. 



Facial recognition is becoming more prominent in our society. It has made major progress in the field of security. It is a very effective tool that can help low enforcers to recognize criminals and software companies are leveraging the technology to help users access the technology. This technology can be further developed to be used in other avenues such as ATMs, accessing confidential files, or other sensitive materials. This project servers as a foundation for future projects based on facial detection and recognition. This project also convers web development and database management with a user-friendly UI. Using this system any corporate offices, school and organization can replace their traditional way of maintaining attendance of the employees and can also generate their availability(presence) report throughout the month.

# The system mainly works around 2 types of users

1.Employee

2. Admin

# Following functionalities can be performed by the admin:


• Login

• Register new employees to the system

• Add employee photos to the training data set

• Train the model

• View attendance report of all employees. Attendance can be filtered by date or employee.

Following functionalities can be performed by the employee:
• Login

• Mark his/her time-in and time-out by scanning their face

• View attendance report of self



# Face Detection
Dlib's HOG facial detector.

# Facial Landmark Detection
Dlib's 68 point shape predictor

# Extraction of Facial Embeddings
face_recognition by Adam Geitgey

# Classification of Unknown Embedding
using a Linear SVM (scikit-learn)


# How To Run ?

clone it on your computer

make a separate python virtual environment or use the default one already installed on your machine

Download this file

put it inside \face_recognition_data directory

run pip install -r requirements.txt directory

Run python manage.py runserver directory to run the project

view the project!!!!


# ADMIN LOGIN details

name:- admin

Password:- admin



python 3.6.1
