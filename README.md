# AutoSelfie
  It is a python program which takes selfie automatically on smiling 

## Real-Time Selfie Capture with Facial Recognition

This Python script utilizes OpenCV and Pyttsx3 to create a real-time selfie capture application with facial recognition features. It captures a selfie when a smile is detected on a recognized face, and the user is notified through spoken feedback.

## Features

- Real-time camera feed using OpenCV.
- Face detection using Haar Cascade classifiers.
- Smile detection on recognized faces.
- Selfie capture with timestamp.
- Spoken feedback using Pyttsx3.

## Prerequisites

- Python 3
- OpenCV (`cv2`) library
- Pyttsx3 library

## How to Run

1. **Install the required libraries:**
   ```bash
   pip install opencv-python pyttsx3
   ```
2. **Download Haar Cascade XML Files:**
  Download the Haar Cascade XML files for face, smile, and eye detection from OpenCV's official repository or other sources.

3. **Save XML Files:**
  Save the downloaded XML files in the same directory as the script.

4. **Run the Script:**

  ```bash
  python autoselfie.py
  ```
5. **Capture Selfies:**

  The webcam will start, and the script will detect smiles on recognized faces, capturing selfies automatically.

6. **Quit the Application:**

  Press the 'q' key to quit the application.
