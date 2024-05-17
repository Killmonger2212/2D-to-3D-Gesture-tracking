# 3D Hand Gesture Tracking with Computer Vision and Unity

This project integrates computer vision techniques and the Unity game engine to achieve precise 3D hand gesture recognition. It leverages MediaPipe for real-time hand detection and landmark localization from a webcam feed, and then maps these landmarks to 3D space within the Unity environment for realistic rendering and interactive experiences.

## Features

- Real-time hand detection and 2D landmark extraction using MediaPipe
- Transmission of 2D hand landmarks from Python to Unity via UDP
- Mapping of 2D landmarks to 3D space within Unity
- Dynamic adjustment of 3D hand model depth based on hand position changes
- Visual representation of hand gestures using GameObjects and LineRenderer
- Intuitive and immersive 3D hand gesture visualization and interaction

## Getting Started

Follow these steps to set up and run the project on your local machine.

### Prerequisites

- Python 3.8.5
- OpenCV 4.5.1
- MediaPipe 0.8.9
- Unity 2020.3.25f1

### Installation

1. Clone the repository:

```
git clone https://github.com/your-username/3d-hand-gesture-recognition.git
```

2. Open the Unity project by following these steps:
   - Launch Unity Hub
   - Click on the "Open" button
   - Navigate to the cloned repository folder
   - Select the "Unity_Project" folder and click "Open"

### Usage

1. **Step 1:** Run the `main.py` file to initialize the camera and start streaming hand landmarks to Unity.

```
python main.py
```

2. **Step 2:** Open Unity Hub and select the project file.

3. **Step 3:** Run the Unity environment by clicking on the "Play" button in the Editor.

4. **Step 4:** Interact with the Unity scene using hand gestures. The 3D hand model in the scene will mimic your hand movements in real-time.


Refer to the project documentation for more details on configuring these files according to your specific requirements.

## Contributing

Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.


## Acknowledgments

- [MediaPipe](https://github.com/google/mediapipe) - Cross-platform, customizable machine learning solution for live and streaming media
- [OpenCV](https://opencv.org/) - Open-source computer vision and machine learning software library
- [Unity](https://unity.com/) - Cross-platform game engine and development environment
