his project is a Face Recognition–based Attendance System built using Python, OpenCV, and the face_recognition library. It uses a webcam to detect and recognize faces in real time and automatically marks attendance for known individuals.

The system compares live camera input with pre-stored face images. When a match is found, the person’s name and entry time are saved in a CSV file, which is automatically created for the current date.

✨ Features

Real-time face detection using webcam

Face recognition using pre-trained face encodings

Automatic attendance marking

Date-wise attendance stored in CSV files

Prevents duplicate attendance entries

Displays name and attendance status on screen

🛠️ Technologies Used

Python

OpenCV

face_recognition (dlib-based)

NumPy


📂 Project Structure
Face-Recognition-Attendance/
│
├── faces/
│   ├── person1.jpg
│   ├── person2.jpg
│   └── person3.jpg
│
├── main.py
├── requirements.txt
└── README.md
