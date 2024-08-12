"""
# Hand Gesture-Based Screen Brightness Control

This project allows you to control the screen brightness of your computer using hand gestures. It uses a webcam to detect hand movements and adjusts the brightness based on the distance between your thumb and index finger.

## Features

- Real-time hand detection and tracking using MediaPipe.
- Adjusts screen brightness based on the distance between thumb and index finger.
- Simple and intuitive control without any physical contact.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- Screen Brightness Control
- NumPy

## Installation

1. **Install the required Python packages:**

   ```bash
   pip install opencv-python mediapipe screen-brightness-control numpy
Run the script:
    python3 brightness_control.py

2. **Control Brightness:
    - The script will open your webcam and start detecting your hand.
    - The distance between your thumb and index finger will control the screen brightness.
    - To exit the script, press the q key.

## How It Works
    The script uses OpenCV to capture video frames from your webcam.
    MediaPipe is used for hand detection and tracking.
    The script calculates the distance between the thumb (landmark 4) and the index finger (landmark 8).
    The screen brightness is adjusted based on this distance using the screen_brightness_control library.

## Notes
  - The script is configured to work with most built-in webcams.
  - Ensure your hand is within the frame for accurate detection.

## Contributing
  - Feel free to submit issues or pull requests if you have suggestions or improvements.

## Licence
  - This project is licensed under the MIT License. See the LICENSE file for more details.
