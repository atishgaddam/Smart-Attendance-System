# Smart Attendance System using OpenCV

A Python-based Smart Attendance System that uses Computer Vision and Face Recognition to automate attendance marking. The system detects and recognizes registered faces through a webcam and records attendance with timestamps, eliminating the need for manual attendance.

## Features

- Real-time face detection using OpenCV
- Face recognition for registered users
- Automatic attendance marking with date and time
- Stores attendance records in CSV format
- Prevents duplicate attendance entries
- Easy-to-use and lightweight application

## Technologies Used

- Python
- OpenCV
- face_recognition
- CSV
- Datetime

## Project Workflow

1. Register face images of students.
2. Encode facial features using the Face Recognition library.
3. Start the webcam for live face detection.
4. Match detected faces with stored encodings.
5. Mark attendance automatically with the current date and time.
6. Save attendance records in a CSV file.

## Folder Structure
│── Images/ # Registered face images
│── Attendance/ # Generated attendance CSV files
│── main.py # Main application
│── requirements.txt
│── README.md
