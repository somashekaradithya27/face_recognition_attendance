# Face Recognition-Based Attendance System

## Overview
This is a face recognition-based attendance system using OpenCV and the `face_recognition` library. It captures video from a webcam, detects faces, and marks attendance in a CSV file with a timestamp.

## Features
- Recognizes and identifies predefined faces.
- Automatically records attendance with timestamps.
- Saves attendance data in a CSV file named with the current date.
- Real-time face recognition using OpenCV.

## Requirements
Make sure you have the following installed:

- Python 3.x
- OpenCV (`cv2`)
- NumPy (`numpy`)
- `face_recognition` library

### Install Dependencies
Run the following command to install the required libraries:
```bash
pip install opencv-python numpy face_recognition
```

## Setup
1. Collect images of individuals to be recognized and store them in the same directory as the script.
2. Update the script with the correct image filenames and corresponding names.

## How to Run
Run the Python script using:
```bash
python attendance.py
```
Press `q` to exit the program.

## Output
- Attendance is stored in a CSV file named as the current date (e.g., `2025-02-18.csv`).
- The file contains two columns: `Name` and `Timestamp`.

## Notes
- Ensure the images used for recognition are clear and well-lit.
- The system may not work well with extreme lighting conditions or partially visible faces.

