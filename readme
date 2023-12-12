# Hand Tracking and Motion Capture Integration

## Overview
This repository contains a Python script that utilizes the `cvzone` library for hand tracking. The script captures hand landmarks in real-time through a webcam and sends the landmark data to Unity via a UDP socket connection. The integration with Unity facilitates motion capture, allowing for interactive applications and simulations.

## Requirements
- Python 3.x
- OpenCV (cv2)
- cvzone library
- Unity (for motion capture integration)

## Setup
1. Install the required Python libraries using the following command:
    ```bash
    pip install -r requirements.txt
    ```

2. Ensure that Unity is installed on your system.

## Usage
1. Run the Python script using the following command:
    ```bash
    python hand_tracking_motion_capture.py
    ```

2. Open your Unity project and set up a UDP receiver to receive the hand landmark data.

3. As the script captures hand landmarks, it sends the data to the specified IP address and port (default: 127.0.0.1:5052). Ensure that the Unity application is listening on the same IP address and port for seamless integration.

## Configuration
- You can modify the script to customize detection parameters, such as detection confidence (`detectionCon`) and the maximum number of hands (`maxHands`).
- Adjust the IP address and port in the `serverAddressPort` variable to match your Unity application's configuration.
