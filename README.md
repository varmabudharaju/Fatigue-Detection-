# Fatigue Detection and Alert System for Vehicles

## Introduction
The Fatigue Detection and Alert System for Vehicles is designed to address the critical issue of driver fatigue, which contributes to a significant number of road accidents annually. This system utilizes real-time image processing techniques to detect signs of drowsiness in drivers and issue alerts to prevent potential accidents.

## Motivation
Driver fatigue is a significant factor in many vehicle accidents. This project aims to develop a prototype drowsiness detection system that measures and records real-time features of the driver or driving pattern, evaluating them against predetermined levels to indicate fatigue.

## Technologies Used
- **Hardware Requirements:**
  - Processor: Intel i5 onwards
  - Solid State Disk: 1GB
  - System Memory: 4GB
  - Camera: 30fps
- **Software Requirements:**
  - Python 3.7
  - Open-CV
  - Python library dlib
  - shape_predictor_68_face_landmarks.dat
  - HAAR Cascading files

## Implementation
The system captures video from a camera, divides it into frames, and analyzes each frame for the presence of fatigue signs. It involves the detection of the driver's face and eyes and evaluates the state of drowsiness based on the eye aspect ratio and blink duration.

## Results
The implementation was successful in real-time capturing and analyzing video frames for fatigue detection. The system can distinguish between normal blinking and drowsiness based on eye closure duration, triggering alerts in the case of detected fatigue.

## Future Work
Future enhancements may include integration with vehicle control systems to automatically slow down the vehicle upon detecting drowsiness, development of a mobile application to inform users about their drowsiness levels during a journey, and improvement of the system's robustness in various driving conditions.

Guided by Mrs. T. Jyotsna Rani, Assistant Professor, Department of Computer Science & Engineering, GITAM.

## Acknowledgments
Special thanks to the Department of Computer Science and Engineering at GITAM Institute of Technology for supporting this project.

## References
- [Facial Features Monitoring for Real-Time Drowsiness Detection](https://ieeexplore.ieee.org/document/7880030)
- [Real-Time Drowsiness Detection using Eye Blink Monitoring](https://ieeexplore.ieee.org/document/7396336)


