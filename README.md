# Crowd count and Density Estimation:

This project implements a real-time crowd counting system using the YOLOv8 object detection model from the [Ultralytics](https://github.com/ultralytics/ultralytics) library. It detects and counts the number of people in a webcam feed, displaying the count live on the video stream.

## Features

- Real-time people detection using webcam input.
- Counts and displays the number of people detected per frame.
- Uses Ultralytics YOLOv8 for high-accuracy object detection.

## Requirements

- Python 3.8+
- OpenCV
- Ultralytics (YOLO)
- A pretrained YOLOv8 model (`YOLO_model.pt`)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/yolo-crowd-counter.git
cd yolo-crowd-counter
```

2. Install the required Python packages:

```bash
pip install opencv-python ultralytics
```

3. Add your YOLOv8 model file (e.g., YOLO_model.pt) to the project directory!

# Usage
## Run the script:

```bash
python main.py
```
- A window will open showing the live webcam feed with bounding boxes around detected people.

- The total count of people will be displayed in the top-left corner.

- Press q to exit.
