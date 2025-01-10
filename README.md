

# Automated Lighting Control Using Human Emotions

## Project Overview
The goal of this project is to create an automated lighting system that adjusts the lighting based on human emotions detected through facial expressions. The system uses real-time facial recognition to assess emotions and modifies the lighting to enhance the environment according to the detected emotion, improving the user experience.

## Objectives
- Detect facial expressions in real-time.
- Adjust lighting dynamically based on the detected emotion.
- Enhance the environment to reflect the user's emotional state.

## Tech Stack
- **Machine Learning**: For emotion detection using facial expressions.
- **Python**: For programming and handling the logic.
- **OpenCV**: For facial detection and real-time video processing.
- **FER 2013 Dataset**: For training the emotion detection model.

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/automated-lighting-control.git
   cd automated-lighting-control

2. Install the required libraries:

pip install -r requirements.txt


3. Run the script to start the lighting control:

python emotion_lighting_control.py



How It Works

The system uses OpenCV to capture video frames from the camera. It processes the frames to detect faces and uses a pre-trained emotion detection model (using the FER 2013 dataset) to classify the emotions. Based on the detected emotion, the lighting is adjusted accordingly.

