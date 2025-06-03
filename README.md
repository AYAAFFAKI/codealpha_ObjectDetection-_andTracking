
# YOLOv8 Webcam Object Detection

This project uses the Ultralytics YOLOv8 model to perform real-time object detection through a webcam.

## Description

- The code captures video frames from the default webcam.
- Each frame is processed by the pretrained YOLOv8 model to detect objects.
- Detected objects are highlighted with bounding boxes and labels.
- The Frames Per Second (FPS) is displayed on the video stream.
- The video stream window can be closed by pressing the **'q'** key.

## Requirements

- Python 3.7+
- OpenCV
- Ultralytics YOLO (`ultralytics` Python package)

## Installation

```bash
pip install ultralytics opencv-python
````

## Usage

Run the Python script (e.g., `yolo_webcam.py`) to start the webcam object detection.

```bash
python yolo_webcam.py
```

Press **'q'** to quit the application.

## Notes

* Make sure your webcam is properly connected.
* The YOLOv8 model weights (`yolov8n.pt`) will be downloaded automatically if not found.

---

Enjoy real-time object detection with YOLOv8!

```

Would you like me to generate the actual `read.md` file for you now?
```
