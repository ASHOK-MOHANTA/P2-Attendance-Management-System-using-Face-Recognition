# P2-Attendance-Management-System-using-Face-Recognition

## Overview

The Attendance Management System using Face Recognition is an automated solution that uses face recognition technology to track student or employee attendance. The system utilizes the Viola-Jones Algorithm for face detection and Local Binary Patterns (LBP) for face recognition. It allows seamless, error-free attendance recording, eliminating the need for manual roll calls or attendance marking.

## Features

Real-time Face Detection: Utilizes Viola-Jones algorithm to detect faces in real time.
Face Recognition: Recognizes faces using Local Binary Patterns (LBP).
Automatic Attendance Marking: Automatically marks attendance based on the recognized face.
Database Integration: Maintains a database to store face features for recognition.
Efficient: Reduces human error and saves time in attendance tracking.

## Prerequisites

Before running the system, you will need to have the following installed:

Python (Version 3.x)
Required Libraries:
opencv-python
numpy
tensorflow or PyTorch (for any advanced features like deep learning, if required)
pillow
tinker (for GUI if used)
sqlite or any other database module (for storing face data and attendance logs)

## Installation
1.
Clone this repository to your local machine:
git clone https://github.com/your-username/attendance-management-face-recognition.git

2.Install required libraries using pip:
pip install -r requirements.txt

## Usage
Running the Program:

python main.py

