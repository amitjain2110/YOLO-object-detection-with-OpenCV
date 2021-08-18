# YOLO-object-detection-with-OpenCV

Object detection using YOLO object detector

Detect objects in both images and video streams using Deep Learning, OpenCV, and Python.

I am using YOLOv3, in particular, YOLO trained on the COCO dataset.

The COCO dataset consists of 80 labels.

yolo-coco : The YOLOv3 object detector pre-trained (on the COCO dataset) model files. These were trained by the Darknet team.

coco.names

yolov3.cfg

yolov3.weights
[ Download these files]

# 1. YOLO object detection in images 

# Installation

pip install numpy

pip install opencv-python

# To Run the code

python yolo_image.py --image cricket-football.jpg

# 2. YOLO object detection in video streams

# Installation

pip install numpy

pip install opencv-python

# To Run the code

python yolo_video.py --input airport.mp4 --output airport_output.avi --yolo yolo-coco

# 3. Real-time object detection with deep learning and OpenCV

# Installation

pip install numpy

pip install opencv-python

pip install imutils

# To Run the code

python real_time_object_detection.py
