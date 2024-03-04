# Face Recognition Attendance System

## Introduction

This project is a simple face recognition attendance system built using Python, OpenCV, and face_recognition library. The system captures faces through a webcam, matches them against pre-trained images, and marks attendance in a CSV file.

## Features

- Real-time face recognition using webcam
- Automatic attendance marking
- Easy setup and customization
- CSV log for attendance records

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/Face-Recognition-Attendance.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Prepare your training images and put them in the `Training_images` directory.

4. Run the script:

    ```bash
    python face_recognition_attendance.py
    ```

## Usage

- Make sure to have your training images in the `Training_images` directory. Each image should contain only one face.
- Run the script and position yourself in front of the webcam.
- Your name will be displayed on the screen if recognized, and your attendance will be marked in the CSV file.

## Configuration

- You can customize the appearance of recognized faces and attendance log by modifying the script.
- For different camera sources or resolutions, adjust the parameters accordingly in the script.

## Credits

- [OpenCV](https://opencv.org/) - Open Source Computer Vision Library
- [face_recognition](https://github.com/ageitgey/face_recognition) - Recognize and manipulate faces from Python




