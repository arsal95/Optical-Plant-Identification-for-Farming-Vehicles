# Optical-Plant-Identification-for-Farming-Vehicles
The main Objective of the project is to build a prototype of an optical plant detector which is to be attached to farming vehicles for detection of Rumex Acetosa using Machine learning and deep learning techniques. The project is to be implemented an image detection model on Raspberry pi 4. The whole system is mounted on to a farming vehicle which is then used by farmers for detecting Rumex Acetosa and eliminating them.

The pi camera is used for capturing the visuals of the field and feed them to raspberry pi. The methods used for the plant detection are machine learning and deep learning techniques. The object detection is achieved by training a deep learning model with the custom dataset of the plant ‘Rumex Acetosa’.

## Requirements
1. Plant (Rumex Accetosa) detection in real-time or on video and images data.
2. Bounding Box appears on the Region of Interest (Rumex Accetosa) during the detection in real-time or in video/images.
3. Train the model using Machine Learning & Deep Learning approaches.
4. Implement the object detection model on state-of-the-art single board computer (i.e. Jetson Nano or Raspberry Pi 4).
5. Use suitable camera for real-time detection.
6. Develop the Graphical User Interface to interact to the product.
7. Detection in every weather conditions as well as damaged plant.

## Training YOLOv3 to detect a Rumex Acetosa (Plant)
* Prepare the Image dataset
* Annotate the images using software (LabelImg), before anotation select the YOLO format from the software settings.
* In the images create RectBox on the plant (Rumex Acetosa) and label the name of the class (Rumex Acetosa). 
* Train the image dataset using "Google Colab"
