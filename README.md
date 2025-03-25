# Touchdesigner-AI-Emotion-Detector

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Setup](#setup)
- [Run the System](#run-the-system)
- [License](#license)

## Overview

The goal of this project is to create a system that can interpret and react to human physical input in a seamless and intuitive way. By leveraging TouchDesigner for visual creation and Python for scripting, the system detects a user's gestures, body language, and facial expressions, and modifies their environment accordingly. The system makes use of the [MediaPipe TouchDesigner Plugin](https://github.com/torinmb/mediapipe-touchdesigner) to extract and process the input from the user.

## Requirements

Before running this project, ensure that you meet the following requirements:

### Software Dependencies
1. **TouchDesigner**: A node-based visual programming language used for interactive and immersive media creation.
2. **MediaPipe TouchDesigner Plugin**: This plugin is used to interface with MediaPipe for gesture, body language, and facial expression recognition.
  
### Hardware Requirements
To run this system, you'll need the following hardware:

1. **Webcam**: A functional webcam or camera system is required to capture the user's body movements, hand gestures, and facial expressions in real-time.
  
2. **Audio Output**: Depending on the environmental control features you've set up in TouchDesigner, you may need audio output devices (such as speakers or headphones) for sound adjustments or audio-responsive visualizations.

3. **Computer with Adequate Processing Power**: The system requires a computer running Windows, Linux, or macOS with a modern processor for optimal performance. No graphics card is required.

## Setup

### Step 1: Clone the Repository
First, clone this repository to your local machine has the following file [Touchdesigner-AI-Emotion-Detector.zip]().

### Step 2: Download the MediaPipe TouchDesigner Plugin
The system requires the MediaPipe TouchDesigner Plugin for body, face, and hand gesture tracking. Follow these steps:

1. Visit the [MediaPipe TouchDesigner Plugin](https://github.com/torinmb/mediapipe-touchdesigner?tab=readme-ov-file) repository.

2. Download the latest `release.zip` from the repository (MAKE SURE IT'S `release.zip` AND NOT `mediapipe-touchdesigner-main.zip`).
   
4. Extract the contents of the `release.zip` into the the root directory (`Touchdesigner-AI-Emotion-Detector`) of this project. Otherwise the plugin wont work correcly with this project.

### Step 3: Make Sure the System Works

1. Open the `FinalDHProject.toe` project.

2. Within the the TouchDesigner project, ensure that the ensure that the plugin interface with MediaPipe is correctly set up. After the project has had some time to load, make sure that the `MediaPipe` function doesent display any errors.

3. Ensure that the `Window` function displays an animation of a vitrual cat.

### Step 5: Run the System
Once everything is set up, you can start the system by running the project in TouchDesigner. Follow these steps:

1. Open your TouchDesigner project `FinalDHProject.toe`.
2. Ensure that the webcam is connected and active.
3. Make sure that the audio output device is working properly and is playing music.
4. Within the project, open the `Window` function and enable `Open as Perform Window` or `Open as Seperate Window`.
6. The system should automatically play music while detect the user's body language, facial expressions, and hand gestures, and the displayed image should change accordingly

### License
ToDo: Do later


