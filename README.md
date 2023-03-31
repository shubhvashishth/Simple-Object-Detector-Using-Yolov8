
# Simple-Object-Detector-Using-Yolov8


## Overview

This repository contains a simple object detector that uses YOLOv8 to detect objects in images. 
## Installation and Working

```bash
  pip install ultralytics
```
```bash
  from ultralytics import YOLO

    # Load a pre-trained model
    model = YOLO("yolov8n.yaml")  
    model = YOLO("yolov8n.pt") 
```
This will automatically download the model and weights into your directory.
## Demo

![Alt text](https://github.com/shubhvashishth/Simple-Object-Detector-Using-Yolov8/blob/fc34d8473bb9bfd1d69c3f430e561f5f6d88d9fd/dog.jpeg?raw=true "Title")

![Alt text](https://github.com/shubhvashishth/Simple-Object-Detector-Using-Yolov8/blob/main/runs/detect/predict/dog.jpeg?raw=true "Title")


![Alt text](https://github.com/shubhvashishth/Simple-Object-Detector-Using-Yolov8/blob/main/bus.jpg?raw=true "Title")

![Alt text](https://github.com/shubhvashishth/Simple-Object-Detector-Using-Yolov8/blob/main/runs/detect/predict/bus.jpg?raw=true "Title")
## Acknowledgements

 - [YOLOV8 Github](https://github.com/ultralytics/ultralytics/issues/1125)
 - [Medium](https://towardsdatascience.com/enhanced-object-detection-how-to-effectively-implement-yolov8-afd1bf6132ae)


