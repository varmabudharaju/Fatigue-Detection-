# Fatigue Detection and Alert System for Vehicles

## Introduction
The Fatigue Detection and Alert System for Vehicles is designed to address the critical issue of driver fatigue, which contributes to a significant number of road accidents annually. This system utilizes real-time image processing techniques to detect signs of drowsiness in drivers and issue alerts to prevent potential accidents.

## Motivation
Driver fatigue is a significant factor in many vehicle accidents. This project aims to develop a prototype drowsiness detection system that measures and records real-time features of the driver or driving pattern, evaluating them against predetermined levels to indicate fatigue.

## System Requirements

### Hardware Requirements
- **Webcam**: 30fps minimum for real-time video capture.
- **Computer**: Intel i5 processor (or equivalent) with at least 4GB of RAM.

### Software Requirements
- **Python**: Version 3.7 or higher.
- Libraries:
  - **OpenCV**
  - **Dlib**
  - **NumPy**
  - **Imutils**
  - **Playsound**
  - **Argparse**

## Installation

1. Ensure Python 3.7 or higher is installed on your system.

2. Install the necessary Python libraries by running the following command in your terminal or command prompt:
    ```bash
    pip install numpy imutils opencv-python dlib playsound argparse
    ```

3. Download the `shape_predictor_68_face_landmarks.dat` file from the [dlib website](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2), extract it, and note the file location.

4. Prepare an alarm sound file in MP3 or WAV format and place it in an accessible directory.

## Execution Instructions

1. Open your terminal or command prompt and navigate to the directory containing the `FaceDetection.py` script.

2. Run the script with the necessary arguments for the shape predictor and alarm file. Replace `<path_to_shape_predictor>` with the path to your `shape_predictor_68_face_landmarks.dat` file, and `<path_to_alarm_file>` with the path to your alarm sound file:
    ```bash
    python FaceDetection.py --shape-predictor <path_to_shape_predictor> --alarm <path_to_alarm_file>


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


