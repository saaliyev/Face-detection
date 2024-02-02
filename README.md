# Video Face Detection using OpenCV and MediaPipe

This repository contains a Python script that utilizes OpenCV and MediaPipe for real-time face detection in video streams. It can identify faces within the video, draw bounding boxes around them, and display the detection confidence and frame rate.

## Setup

To run this script, you need Python installed on your machine along with the following libraries:

- OpenCV
- MediaPipe

Install the required libraries with:
pip install opencv-python mediapipe

## Running the Script
Place your video file in the Videos folder and rename it to <VIDEO_FILE>.mp4, or adjust the script to point to your video file's path.

Execute the script in your terminal:

python face_detect.py

## Output
The script will display the video stream in a window with faces highlighted. Detection confidence and FPS are shown on the stream.
