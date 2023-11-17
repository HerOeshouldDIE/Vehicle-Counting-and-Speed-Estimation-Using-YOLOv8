# Vehicle Counting and Speed Estimation using YOLOv8

## Overview

This repository presents a robust solution for vehicle counting and speed estimation using the YOLOv8 object detection model. The system excels in detecting vehicles in videos, tracking their movement, and estimating their speed, making it a valuable tool for traffic analysis and monitoring.

## Features

- **Object Detection:** Leverages YOLOv8 for accurate and efficient vehicle detection.
- **Tracking:** Implements a robust tracking mechanism to follow vehicles across frames.
- **Speed Estimation:** Estimates the speed of detected vehicles based on their movement.
- **Interactive Jupyter Notebook:** Provides an interactive Jupyter Notebook for testing and exploration.

## Prerequisites

Before running the code, ensure you have the following installed:

- Python (3.7 or higher)
- OpenCV
- Pandas
- Ultralytics
- Jupyter Notebook (for running the Jupyter file)

Install the required Python libraries using:

```bash
pip install opencv-python pandas ultralytics jupyter
```

## Files

### 1. `main.py`

The main script for vehicle counting and speed estimation. Run this script to process a video and generate output.

#### Usage:

```bash
python main.py
```

### 2. `tracker.py`

Contains the `Tracker` class responsible for robust object tracking in consecutive frames.

### 3. `jupyter1.ipynb`

An interactive Jupyter Notebook providing a hands-on environment for testing and understanding the code.

## How to Run

1. **Run `main.py`:**

   ```bash
   python main.py
   ```

   This processes the video, performs vehicle counting and speed estimation, and saves the output in `output.avi`.

2. **Run `jupyter1.ipynb`:**

   - Install Jupyter Notebook (if not already installed):

     ```bash
     pip install jupyter
     ```

   - Open Jupyter Notebook:

     ```bash
     jupyter notebook
     ```

   - Open the `jupyter1.ipynb` notebook, run the cells, and replace the video file name if needed.

## How to Clone

To clone this repository, use the following command:

```bash
git clone https://github.com/HerOeshouldDIE/Vehicle-Counting-and-Speed-Estimation-Using-YOLOv8.git
```

## GitHub Repository

Explore the complete code and resources on GitHub: [Vehicle-Counting-and-Speed-Estimation-Using-YOLOv8](https://github.com/HerOeshouldDIE/Vehicle-Counting-and-Speed-Estimation-Using-YOLOv8)

Feel free to star, fork, or contribute to this project! Your feedback is valuable.
