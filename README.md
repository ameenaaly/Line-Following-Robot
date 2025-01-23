# Autonomous Line-Following Robot with Green and Red Marker Detection

This repository contains Python code for an autonomous robot implemented on a JetBot platform. The robot follows a black line on a white surface, detects directional green markers (left, right, U-turn, roundabout), and identifies red markers (stop signals). It also includes obstacle detection and a state-based control system.

## Features

- **Line Following**: Uses edge detection to follow a black line.
- **Green Marker Detection**: Interprets green markers for navigation decisions:
  - Left Turn
  - Right Turn
  - U-turn
  - Roundabout (left and right)
- **Red Marker Detection**: Stops the robot upon detecting a red marker.
- **Obstacle Avoidance**: Detects obstacles and stops the robot temporarily.
- **State-Based Control**: Manages robot behavior based on the current state (e.g., line following, blocked, directional turns).

## Dependencies

The code is built for JetBot and uses the following Python libraries:
- `cv2` (OpenCV): For image processing and edge detection.
- `torch`: For potential integration with machine learning models (if applicable).
- `numpy`: For numerical operations.
- `jetbot`: For interfacing with the JetBot's hardware components.
- `ipywidgets`: For displaying real-time camera feed in a Jupyter Notebook.
