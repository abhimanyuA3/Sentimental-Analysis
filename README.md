# Sentimental-Analysis

This repository contains code for real-time emotion detection using a webcam. The program uses a pre-trained deep learning model to detect emotions in faces captured by the webcam.

## Requirements
* Python 3.x
* TensorFlow
* Keras
* OpenCV

## Installation

1. Install the required dependencies:
  ```pip install tensorflow keras opencv-python```

2. Download the pre-trained model file (Emotion_Detection.h5) and place it in the project directory.

3. Run the program:
  ```python run.py```

## Usage
1.Connect a webcam to your computer.
2.Run the program as mentioned in the Installation section.
3.The webcam feed will open, and it will detect faces in real-time.
4.The predicted emotion label will be displayed on each detected face.
5.Press 'q' to quit the program.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## References
https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data?select=example_submission.csv
