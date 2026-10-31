# **CNN Emotion Recognition with Residual Units**

  This project implements **Facial Emotion Recognition** using a Convolutional Neural Network (CNN) enhanced with
  **Residual Units**. It uses real-time webcam feed for emotion detection and leverages TensorFlow and OpenCV for deep
  learning and computer vision tasks.

  ---

  ## **Features**
  - Real-time emotion detection using webcam input.
  - Custom implementation of **Residual Units**, inspired by ResNet architecture.
  - Modular code for testing and extending deep learning components.
  - Cross-platform support with minimal dependencies.

  ---

  ## **Table of Contents**
  - [Technologies Used](#technologies-used)
  - [How It Works](#how-it-works)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Future Enhancements](#future-enhancements)

  ---

  ## **Technologies Used**
  - **TensorFlow**: For building and testing the deep learning components.
  - **OpenCV**: For capturing and processing real-time webcam input.
  - **Python**: Programming language for implementation.
  - **facial_emotion_recognition**: Pre-trained library for emotion classification.
  - **PyTorch**: Required by the facial_emotion_recognition library.

  ---

  ## **How It Works**
  1. **Emotion Recognition**:
     - Captures real-time frames from the webcam.
     - Processes each frame to detect and classify facial emotions.
     - Displays the emotion on the video feed.

  2. **Residual Units**:
     - Implements skip connections to improve training for deeper networks.
     - Used as a test module for future integration into the emotion recognition pipeline.

  ---

  ## **Installation**

  ### Prerequisites
  - Python 3.10 or higher.
  - A webcam connected to your system.

  ### Steps
  1. Clone this repository:
     ```bash
     git clone https://github.com/anson10/CNN-Emotion-Recognition.git
     cd CNN-Emotion-Recognition
     ```

  2. Install the dependencies:
     ```bash
     pip install -r requirements.txt
     ```

  ---

  ## **Usage**
  Run the script:
  ```bash
  python emotion-recogntion.py
  ```

  It runs the Residual Unit test first, then opens the webcam for emotion recognition. Press **ESC** in the video window
  to exit.

  ---

  ## **Future Enhancements**
  - Integrate Residual Units directly into the emotion recognition pipeline.
  - Extend emotion categories and improve model accuracy.
  - Add GPU support for faster processing.
  - Develop a GUI for better user experience.
