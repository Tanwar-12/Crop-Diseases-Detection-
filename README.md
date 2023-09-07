# Crop Health Monitoring and Disease Detection

## Overview:
The purpose of this project is to create a deep learning model for crop detection using YOLOv5. Crop detection technology can be valuable for various applications in agriculture, such as monitoring crop health, yield prediction, and pest detection.

![image](https://github.com/Tanwar-12/Crop-Diseases-Detection-/assets/110081008/3110ba8f-d6c4-4fab-b8b7-452319b4b57d)

📁 Dataset:
For this project, you'll need a dataset of images containing various crops. You can collect or curate this dataset, ensuring it has annotated bounding boxes around the crops.

Workflow:
Here's a general workflow for your crop detection project using YOLOv5:

Data Preparation:
Dataset Collection and Annotation: Collect a dataset of images containing different crops. Annotate the images with bounding boxes around each crop using labeling tools like LabelImg or VGG Image Annotator.
Folder Structure: Organize your dataset into a folder structure that YOLOv5 can accept. It should have separate folders for images and labels, and each label file should correspond to an image file.

## Steps to Use YOLOv5:
Cloning YOLOv5 Repository: Clone the YOLOv5 repository from the official GitHub repository.

Setting Up Environment: Change the directory to the YOLOv5 folder and set up your Python environment with the necessary dependencies. You can use a virtual environment to manage your packages.

Downloading Pre-trained Weights: Download pre-trained YOLOv5 weights for your desired model size (e.g., YOLOv5s, YOLOv5m, YOLOv5l, YOLOv5x). These weights will be used as a starting point for training.

 ## Steps Before Training Custom Dataset:
* Go to yolov5/data/.
* Open data.yaml
* Edit the following inside it:

 1. Training and Validation file path
 2. Number of classes and Class names.
 3.  ## Training YOLOV5 Model
* Set images size 640 with batch of 8.
* Train model around 1000 epochs .
* Visualise the training metrics with the help of tensorboard.


  ## Testing Images Using Test Data:
![image](https://github.com/Tanwar-12/Crop-Diseases-Detection-/assets/110081008/c6b06782-48ab-402f-9682-978bce2bd35e)

  ![image](https://github.com/Tanwar-12/Crop-Diseases-Detection-/assets/110081008/b83af5f3-b78b-4ba0-a065-cadbf15b6caa)





