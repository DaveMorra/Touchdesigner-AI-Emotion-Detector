# Touchdesigner-AI-Emotion-Detector

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Setup](#setup)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Overview

The goal of this project is to create a system that can interpret and react to human physical input in a seamless and intuitive way. By leveraging TouchDesigner for visual creation and Python for scripting, the system detects a user's gestures, body language, and facial expressions, and modifies their environment accordingly. The system makes use of the [MediaPipe TouchDesigner Plugin](https://github.com/torinmb/mediapipe-touchdesigner) to extract and process the input from the user.

## Requirements

Before running this project, ensure that you meet the following requirements:

### Software Dependencies
1. **TouchDesigner**: A node-based visual programming language used for interactive and immersive media creation.
   - Download here: https://derivative.ca/
2. **MediaPipe TouchDesigner Plugin**: This plugin is used to interface with MediaPipe for gesture, body language, and facial expression recognition.
   - Download the latest release from the [MediaPipe TouchDesigner GitHub](https://github.com/torinmb/mediapipe-touchdesigner?tab=readme-ov-file).
  
### Hardware Requirements
To run this system, you'll need the following hardware:

1. **Webcam**: A functional webcam or camera system is required to capture the user's body movements, hand gestures, and facial expressions in real-time. Ensure that your camera has sufficient resolution and frame rate for smooth tracking (1080p or higher is recommended).
  
2. **Audio Output**: Depending on the environmental control features you've set up in TouchDesigner, you may need audio output devices (such as speakers or headphones) for sound adjustments or audio-responsive visualizations.

3. **Computer with Adequate Processing Power**: The system requires a computer running Windows, Linux, or macOS with a modern processor (e.g., Intel i5/Ryzen 5 or better). For optimal performance, make sure your machine has at least 8 GB of RAM and a dedicated graphics card (e.g., NVIDIA GTX 1050 or better). Real-time processing of body language, facial expressions, and hand gestures can be demanding on your system, so a machine with decent processing power will ensure smooth operation.



