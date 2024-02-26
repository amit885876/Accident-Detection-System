# Accident-Detection-System

#ACCIDENT DETECTION SYSTEM

#-> What is an Accident Detection System? An accident Detection System is designed to detect accidents via video or CCTV footage. Road accidents are a significant problem for the whole world. Many people lose their lives in road accidents. We can minimize this issue by using CCTV accident detection. This repository majorly explores how CCTV can detect these accidents with the help of Deep Learning.

#-> Prerequisites To use this project Python Version > 3.6 is recommended. To contribute to this project, knowledge of basic Python scripting, Machine Learning, and Deep Learning will help. -> Getting Started - How to use it?

#Clone this repository using "git clone https://github.com/amit885876/Accident-Detection-System.git"

#To install all the packages required to run this Python program "pip install -r requirements.txt"

#Note: This project requires a camera. So make sure you have a connected camera to your device. You can also use a downloaded video if not using a camera.

#Run Before running the program, you need to run the accident-classification.ipynb file which will create the model_weights.h5 file. Then, to run this Python program, you need to execute the main.py Python file.

#-> Libraries used: NumPy, Pandas, Tensorflow, Matplotlib, OpenCV

#-> Description This program includes 4 things.

#data: Kaggle dataset on Accident Detection from CCTV footage.
accident-classification.ipynb: This is a jupyter notebook that generates a model to classify the above data. This file generates two important files model.json and model_weights.h5.
detection.py: This file loads the Accident Detection system with the help of model.json and model_weights.h5 files.
camera.py: It packs the camera and executes the detection.py file on the video dividing it frame by frame and displaying the percentage of the prediction in the accident (if present) in the frame.

#-> Future Work We can use an alarm system that can call the nearest police station in case of an accident and also alert them of the severity of the accident.
