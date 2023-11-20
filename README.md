# Face Recognition System

This project implements a real-time face recognition system using Python and OpenCV. The system captures live video from the webcam, detects faces, and matches them against a set of pre-recorded face signatures. The face signatures are generated by encoding facial features using the face_recognition library. The system utilizes MongoDB to store recognized faces and provides feedback in the form of notifications. It's a practical demonstration of facial recognition technology, suitable for various applications such as security systems, attendance tracking, and more.

# Key Features:

Real-time face recognition from webcam feed.
Encoding and comparison of facial features using face_recognition library.
Integration with MongoDB for persistent face data storage.
Live feedback on recognition status.

# Usage:

Clone the repository.
Install the required dependencies (cv2, numpy, face_recognition, pymongo).
Create a folder named images and put photos of people's faces in it (face signatures).
Run the app.py script to launch the webcam-based face recognition system.

# Note: Ensure that you have MongoDB installed and running locally for database functionality.
