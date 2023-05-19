# Object-Detection-Web-App-Using-YOLOv7-and-Flask

Object Detection Web App Using YOLOv7 and Flask

## Description

This project utilizes the YOLOv7 deep learning model for object detection. The YOLOv7 model is trained on a custom dataset using the Grocessory dataset, labeled using Roboflow. The trained model is then used to perform object detection on test images and videos. Additionally, a Flask application has been developed to facilitate uploading images and videos for real-time detection.

## Features
- Object detection using the YOLOv7 model
- Training on a custom dataset
- Integration with Roboflow for labeling
- Real-time detection in a Flask application
- Support for image and video uploads

## Installation
- Clone the Repository: git clone https://github.com/username/YOLOv7.git
`cd YOLOv7`
- Set Image Paths: Edit the YAML file (data.yaml) to specify the paths of your train and test images.
- Training: Train the YOLOv7 model with the custom dataset using the following command:
`python train.py --img 640 --batch 16 --epochs 50 --data data.yaml --weights yolov7x.pt --cache`
Monitor the training progress and adjust the parameters as needed.

## Object Detection
- Once training is complete, locate the best weights file (best.pt) in the runs/exp/ directory.
- Use the best weights to perform object detection on a test image using the following command:
`python detect.py --weights runs/train/exp/weights/best.pt --img 640 --conf 0.25 --source test.jpg`

## Flask Application
- Set up a virtual environment and install the necessary dependencies:
`virtualenv env \
source env/bin/activate \
pip install -r requirements.txt` \
- Run the Flask application:
`python webapp.py`
- Access the application in a web browser at http://localhost:5000 and upload images or videos for object detection.

Steps to use:

1- Setup the environment to run yolov7 and flask.

2- Clone this github repo.

3- Paste your custom model in the cloned repo.

4- Run :  python webapp.py

5- Open 127.0.0.1:5000

6- Upload Image or video to test.

