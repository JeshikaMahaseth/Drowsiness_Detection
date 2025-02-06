# Drowsiness_Detection
This project implements a real-time drowsiness detection system using OpenCV, dlib, and Python. The system analyzes a webcam video feed to monitor a person’s eye movements and triggers an alert if signs of drowsiness are detected.

Features
Eye Aspect Ratio (EAR) Calculation: Detects prolonged eye closure using facial landmarks.
Real-Time Detection: Processes video frames in real time using a webcam feed.
Alarm System: Triggers an audible alarm when drowsiness is detected.
Facial and Eye Detection: Includes additional scripts for face and eye detection using Haar cascades.
Technologies Used
Python: Core language for scripting.
OpenCV: For face and eye detection, as well as video processing.
dlib: For precise facial landmark detection.
Pygame: To play alert sounds for drowsiness warnings.
Applications
This project is ideal for applications in driver assistance systems (ADAS) and safety monitoring systems, where detecting drowsiness can help prevent accidents.

How It Works
Detects facial landmarks using dlib's pre-trained model.
Calculates the Eye Aspect Ratio (EAR) to determine whether the eyes are closed.
Continuously monitors EAR and triggers an alarm when it remains below the threshold for a set number of frames.
