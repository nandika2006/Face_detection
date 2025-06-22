# Face Detection App 

This is a simple real-time face detection application built using **Python** and **OpenCV**.  
It uses the webcam to detect human faces and draws a green bounding box around them using the **Haar Cascade Classifier**.

## Features

- Detects faces in a live video stream from your webcam
- Draws bounding boxes around each face
- Counts the number of detected faces and displays it

## Tools & Technologies

- Python 3.x
- OpenCV (`cv2`)
- Haar Cascade XML file (pre-trained model)

## Project Structure

    FaceDetectionApp/
    │
    ├── face_detector.py # Main Python script
    ├── haarcascade_frontalface_default.xml # Haar cascade file (optional if using cv2.data)
    └── README.md # Project documentation

## How to Run the App

### 1. Clone the Repository or Download Files

    git clone https://github.com/your-username/FaceDetectionApp.git
    cd FaceDetectionApp
  
  2. Install Dependencies
  Make sure you have Python installed, then run:

    pip install opencv-python
  
  4. Run the App
  
    python face_detector.py
  
  4. Quit the App
  Press the q key in the webcam window to stop the app.
  or else press ctrl+c
  
## How It Works (Simple Terms)
  - The webcam captures live video.

  - Each frame is turned to black & white (grayscale).

  - OpenCV checks for specific patterns (like eye and nose areas).

  - It runs the image through stages of filters (called a “cascade”).

  - If it passes all checks, it detects a face and draws a box.

## Learning Goals
Real-time object detection

- Understanding Haar cascades and feature matching

- Working with webcam input in Python

- Basic OpenCV functions (frame reading, image processing, drawing)


# Credits
Haar Cascade Classifier by Viola & Jones (2001)
OpenCV community

License
