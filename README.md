# Fashion Trend Analysis

This project utilizes computer vision and machine learning techniques to analyze fashion trends in real-time video streams.

## Features

- Real-time fashion trend prediction
- Dominant color extraction
- Live video processing

## Technologies Used

- OpenCV
- TensorFlow
- scikit-learn
- NumPy

## How It Works

1. Captures video frames from the camera
2. Extracts features using MobileNetV2
3. Clusters features using MiniBatchKMeans for trend prediction
4. Analyzes dominant colors in each frame
5. Displays results in real-time

## Results

## Results

<img src="Screenshot 2024-07-19 000923.png" alt="Fashion Trend Analysis Screenshot 1" width="400"/>

<img src="Screenshot 2024-07-19 001353.png" alt="Fashion Trend Analysis Screenshot 2" width="400"/>

## Setup and Running

1. Install required libraries: pip install opencv-python tensorflow scikit-learn numpy
2. Run the script: python fashion_trend_analysis.py
3. Press 'q' to quit the application


## Future Improvements

- Integrate more sophisticated trend detection algorithms
- Expand the dataset for more accurate predictions
- Implement user interface for easier interaction
