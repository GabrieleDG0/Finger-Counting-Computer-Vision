# Finger counting with OpenCV and MediaPipe

## Introduction
This project is a real-time finger counting application that uses OpenCV for video capture and MediaPipe for hand feature recognition. The application captures video from the webcam, recognizes the position of the fingers and displays the number of fingers raised on the screen.

**Note: You can find a .exe file, inside the release section of Github, if you want to try the project, without needing to install Python, if you have a Windows system.**

### Controls
- Q Key: Exit and close all the windows 

## Features
The application recognizes the number of fingers raised in real time using your webcam. It uses MediaPipe's hand tracking solution to detect and track the position of the fingers. Also, the application displays frames per second (FPS) on the screen to monitor performance.

For optimal performance, make sure you are using the application in an environment with the following conditions:

- Good lighting: avoid strong light or reflections that can cause glare. Soft, even lighting is best for hand feature recognition.
- Neutral background: A simple, unobtrusive background is ideal to reduce noise and ensure accurate hand recognition.
- Minimal movement: Keep the camera and hand still during recognition to maintain accuracy.
To run this script, you must have Python and the following packages installed OpenCV and Mediapipe

### Landmarks model
![Landmarks](https://github.com/user-attachments/assets/64b5c2ab-15a7-49f0-9241-e0e4dda6498b)

This finger counting application provides a foundation for a variety of technical and research-oriented applications. It can be extended to implement gesture-based control systems, enabling interaction with multimedia software, smart devices, or games. With further development, the application could be adapted to recognize more complex hand gestures, potentially supporting sign language interpretation.

Future enhancements include support for tracking multiple hands simultaneously, which would enable collaborative or multi-user interaction scenarios. Gesture recognition can be expanded beyond simple finger counting to detect predefined gestures, such as thumbs up or victory signs, triggering specific actions. Integration of machine learning models could further improve accuracy and robustness, particularly under varying lighting conditions and complex backgrounds

This project serves as a solid foundation for the research and further development of fingerprint and gesture recognition technologies in various fields. If you find any bugs, errors or problems, feel free to open an issue. **Happy Coding!**
