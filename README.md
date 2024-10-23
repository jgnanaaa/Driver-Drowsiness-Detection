
# Driver Drowsiness Detection

## Overview
Driver Drowsiness Detection is a system designed to detect signs of driver fatigue or drowsiness using computer vision techniques. The project utilizes a live video feed to monitor the driver's eyes and trigger an alert if drowsiness is detected, helping to prevent accidents.

## Features
- Real-time detection of drowsiness using a webcam.
- Calculates Eye Aspect Ratio (EAR) to detect eye closure.
- Alerts the user if drowsiness is detected for a sustained period.

## Technologies Used
- **Python**
- **OpenCV** - For video capture and image processing.
- **Dlib** - For facial landmark detection.
- **Numpy** - For array manipulation.

## How It Works
1. The system captures a real-time video feed from a connected webcam.
2. Facial landmarks are detected, specifically focusing on the eyes.
3. The Eye Aspect Ratio (EAR) is computed continuously to monitor if the eyes are closed for too long.
4. If the eyes remain closed beyond a certain threshold, the system triggers an audible alert to wake the driver.

## Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-username/driver-drowsiness-detection.git
cd driver-drowsiness-detection
