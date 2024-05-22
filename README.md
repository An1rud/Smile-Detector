# Smile Detector

This is a simple smile detection application using OpenCV. The program captures video from the webcam, detects faces, and saves an image whenever a smile is detected.

## Features
- Detects faces in real-time from the webcam feed.
- Detects smiles within the detected faces.
- Saves an image (`smile.png`) when a smile is detected.

## Prerequisites
- Python 3.x
- OpenCV

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/An1rud/Smile-Detector.git
   cd Smile-Detector
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the smile detector script:
   ```bash
   python smile_detector.py
   ```

2. The application will open a window showing the webcam feed. When a smile is detected, it will save an image as `smile.png` and print a message in the console.

3. Press `q` to exit the application.

## License

This project is licensed under the MIT License.
