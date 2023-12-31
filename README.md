# Engagement Analysis with Head Pose Estimation

Engagement Analysis with Head Pose Estimation is a computer vision project that utilizes Mediapipe library for facial landmarks detection, OpenCV for computer vision tasks, and NumPy/Pandas for data manipulation. It estimates head pose and gaze direction to determine whether the user is engaged or not.

## Features

- Head pose estimation.
- Gaze direction analysis.
- Engagement analysis based on head pose and gaze direction.
- Real-time visualization of facial landmarks and analysis results.
- Track the duration of continuous eye contact with the camera to measure attention span.
- Analyze variations in gaze direction to understand shifts in focus.

## Parameters

Adjustable parameters are available in the script for customization:

- `draw_gaze`: Set to `True` to display gaze vectors.
- `draw_full_axis`: Set to `True` to display the full rotation axis.
- `draw_headpose`: Set to `True` to display head pose vectors.
- `x_score_multiplier` and `y_score_multiplier`: Multipliers to adjust the impact of gaze on head pose estimation.
- `threshold`: Threshold for averaging gaze scores between frames.

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/Ajayhegde1/MoodViewAnalytics.git
   ```

2. Install all the required Dependencies:
   Requirements:

   - OpenCV
   - Mediapipe
   - Numpy
   - Pandas

   ```
   pip install -r requirements.txt
   ```

3. Usage:
   ```
   python eye_nose_detector.py
   ```

## Results

The script provides real-time visual feedback on engagement and gaze direction. It also generates a summary of engagement statements and percentages after execution.

## License

This project is licensed under the <b>MIT License</b> - see the LICENSE file for details.
