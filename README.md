# RoadSignDetectionSystem
Developed a road sign detection system using the YOLOv8 deep learning model to automatically detect and classify traffic signs from images. The model extracts visual features and predicts the location and category of road signs, enabling accurate detection useful for autonomous driving and driver assistance systems.
## Dataset

The dataset used in this project is obtained from Roboflow Universe.

Dataset Link:
https://universe.roboflow.com/selfdriving-car-qtywx/self-driving-cars-lfjou

It contains labeled images of different traffic signs such as stop signs, speed limit signs, and traffic lights. The dataset is formatted for YOLO object detection training.
## Technology Used
Python  
YOLOv8  
OpenCV  
Google Colab

## Training Command
yolo task=detect mode=train model=yolov8n.pt data=data.yml epochs=10 imgsz=640 batch=16
