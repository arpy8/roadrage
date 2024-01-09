# RoadRage - Gesture Controlled Racing Game

## Overview
**roadrage** is a Python-based project that allows you to control roadrage using hand gestures. It utilizes computer vision and the PyAutoGUI library to detect hand poses and translate them into game commands. The primary purpose is to enhance the gaming experience by providing an alternative, hands-free control mechanism.

## Features
- Gesture-based control: Navigate through the racing game using hand gestures.
- Real-time pose detection: Utilizes OpenCV for real-time hand pose detection.
- OpenCV visualization: View the live camera feed with hand pose overlays.

## Getting Started (using pip)
1. Install the librar: `pip install roadrage`
2. Run the script: `roadrage`

## Dependencies
- OpenCV
- PyAutoGUI
- Mediapipe

## Usage
1. Use hand gestures to control the game: 
   - Raise your left hand to simulate pressing the right key; go right.
   - Raise your right hand to simulate pressing the left key; go left.
   - Bring both hands down to simulate pressing the 'x' key, accelarate.

## Configuration
Adjust the following threshold values in the `roadrage.py` script to fine-tune gesture sensitivity:
- `DOWN_THRESHOLD`: Threshold for downward gesture recognition.
- `LEFT_THRESHOLD`: Threshold for left gesture recognition.
- `RIGHT_THRESHOLD`: Threshold for right gesture recognition.

## Author
- GitHub: [arpy8](https://github.com/arpy8)

Feel free to contribute or report issues.
