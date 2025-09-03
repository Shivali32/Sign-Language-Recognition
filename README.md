# Sign Language Recognition Project

## Overview
This repository provides an end-to-end system for recognizing and interpreting sign language gestures using computer vision and deep learning. The project demonstrates the complete pipeline—from collecting raw gesture data to training machine learning models and running real-time inference.

## Features
- **Data Collection**: Capture and store sign language gesture data.
- **Data Preprocessing**: Clean and prepare data for model training.
- **Model Training**: Train machine learning models to recognize sign language gestures.
- **Inference**: Use trained models to interpret sign language in real-time.

## Technologies
- **Programming Language**: Python (>=3.6)
- **Libraries**: OpenCV, TensorFlow, NumPy
- **Machine Learning**: Deep learning models for gesture recognition


## Installation
1. Clone the repository: 
``` git clone https://github.com/your-username/sign-language-recognition.git ```
``` cd sign-language-recognition ```
2. Install dependencies: 
``` pip install -r requirements.txt ```

3.  Set up environment variables:
Create a `.env` file in the root directory and add necessary configurations.

## Usage
1. The workflow is designed to move seamlessly from data collection to deployment:
2. Collect Data → Record sign language gestures and store them in the data/ directory.
3. Preprocess Data → Use scripts in preprocessing/ to clean, normalize, and prepare datasets.
4. Train Models → Run training scripts in model/ to build deep learning models on processed data.
5. Run Inference → Deploy trained models with scripts in static/ to recognize gestures in real time.

## Demo
Watch the demo video [here](https://github.com/Shivali32/Sign-Language-Recognition/blob/main/ProjectFiles/Video.mp4).
