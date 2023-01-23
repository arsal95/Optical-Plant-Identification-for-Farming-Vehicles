# Optical-Plant-Identification-for-Farming-Vehicles
The main objective of the project is to build a prototype of an optical plant detector which is to be attached to farming vehicles for detection of Rumex Acetosa using Machine learning and deep learning techniques. The project is to be implemented an image detection model on Raspberry pi 4. The whole system is mounted on a farming vehicle which is then used by farmers for detecting Rumex Acetosa and eliminating them.

The pi camera is used for capturing the visuals of the field and feed them to raspberry pi. The methods used for the plant detection are machine learning and deep learning techniques. The object detection is achieved by training a deep learning model with the custom dataset of the plant ‘Rumex Acetosa’.

## Requirements
1. Plant (Rumex Accetosa) detection in real-time or on video and images data.
2. Bounding Box appears on the Region of Interest (Rumex Accetosa) during the detection in real-time or in video/images.
3. Train the model using Machine Learning & Deep Learning approaches.
4. Implement the object detection model on state-of-the-art single board computer (Raspberry Pi 4).
5. Use suitable camera for real-time detection.
6. Develop the Graphical User Interface to interact to the product.
7. Detection in every weather conditions as well as damaged plant.

## Training YOLOv3 to detect a Rumex Acetosa (Plant)
* Prepare the Image dataset
* Annotate the images using software (LabelImg), before anotation select the YOLO format from the software settings.
* In the images create RectBox on the plant (Rumex Acetosa) and label the name of the class (Rumex Acetosa). 
* Create a zip folder containing annotated pictures .txt files and classes.txt on the google drive.
* Open the Google Colab, enable/select the GPU and connect it to google drive.
* Clone the darknet and compile it using Nvidia GPU.
* Configure Darknet network for training YOLO V3.
* Create folder on google drive so that we can save there the weights.
* Extract the annotated images (.txt) from the zip folder that is uploaded on google drive.
* Start the training and stop it when the average loss is less than 0.5 (more than 1000 iterations in this case).

## Test the Trained Model
* I created a python project to test the model with Opencv.
* Call the last weights file and YOLO V3 config file in the python script and test it on random images, videos, and camera (in real-time).

## Implemented System
| <img src="./Images/Implemented System.PNG"> |
|:--:| 
| *Space* |

| ![](Images/Implemented%20System.PNG) | 
|:--:| 
| *Space* |
