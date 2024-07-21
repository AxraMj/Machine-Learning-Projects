# Face Recognition Project

This repository contains a face recognition project that uses Python and OpenCV to recognize faces from images and videos. The project includes scripts for training the model, resizing images, and testing the face recognition system.

## Project Structure

FaceRecognition/
├── videoTester.py
├── faceRecognition.py
├── resizeImages.py
├── videotomg.py
├── tester.py
├── trainingImages/
├── HaarCascade/
├── resizedTrainingImages/
└── TestImages/


## Files and Directories

- **videoTester.py:** Script to test face recognition on video files.
- **faceRecognition.py:** Main script for face recognition.
- **resizeImages.py:** Script to resize images for training.
- **videotomg.py:** Script to extract images from video files.
- **tester.py:** Script to test the face recognition model.
- **trainingImages/:** Directory containing images used for training the model.
- **HaarCascade/:** Directory containing Haar Cascade XML files for face detection.
- **resizedTrainingImages/:** Directory for resized training images.
- **TestImages/:** Directory containing images used for testing the model.

## Prerequisites

- Python 3.x
- OpenCV
- NumPy

## Installation

1. Navigate to the project directory:
   ```bash
   cd FaceRecognition

2. Install the required packages:
  pip install -r requirements.txt.

## Usage
1. Training the Model:
  Add your training images to the trainingImages/ directory.
  Run the resizeImages.py script to resize the training images
  python resizeImages.py

2. Testing the Model:
  Add your test images to the TestImages/ directory.
  Run the faceRecognition.py script to test face recognition
  python faceRecognition.py

3. Video Testing:
  Run the videoTester.py script to test face recognition on videos
  python videoTester.py


## Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an Issue if you have any suggestions or improvements.



