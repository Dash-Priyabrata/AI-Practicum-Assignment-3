University of Texas San Antonio, AI Practicum, Fall 2023
                                                                                                                                                 
Assignment 3:ML Model in Tensorflow 
                                                                    
Date Due: Sep 26, 2023, 11:59 PM 
Objectives 
This assignment will introduce you to developing and prototyping an AI model in python using the tensorflow library. The source code should be uploaded to Assignment 3 repository on Github classroom and a report should be submitted on Canvas with the required deliverables. Following are the objectives of Assignment 3. 
Get familiar with tensorflow API for AI/ML models. 
Implement and train a simple neural network and evaluate its performance  using the tensorflow API. 
Train and validate a deep neural network on an object detection task.

Q.1 - Train and validate a deep neural network on MNIST dataset using tensorflow(25 points) 
 The goal is to implement a deep neural network that can perform image classification.  
Implement a deep neural network (DNN) model (for classification task) of your choice using tensorflow1.  
Train the DNN model and evaluate the performance of the model on Fashion MNIST dataset. For the chosen model, complete the second column of Table 1. Add the table to the report with appropriate caption. 

———————————————————— 1Refer to the resources section for additional information on basics of implementing deep neural networks in tensorflow.   

Table 1: Fill in the second column for the chosen DNN model. Additional information about the model can be included. 
Plot the loss and classification performance curves. Add the plots to the report with appropriate labels. 
Add a discussion section, where you provide the reasoning for selecting the model and, describe strategies that could lead to a higher classification accuracy.  
Dataset: Fashion MNIST is a dataset of Zalando's article images consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes.
 Q.2 - Use the TF-Hub module to perform object detection (25 points) 
 For part 2, you will be required to load and validate a pre-trained AI model to solve an object detection task. Follow the directions provided in the object detection tutorial here. There are two object detection modules provided by the TF-Hub, namely FasterRCNN +InceptionResNetV 2 and ssd+mobilenetV 2. Following are the deliverables:  
Pick at least 2 images from the internet or custom images and perform inference with the downloaded images on both the modules. 

Compare the inference time for the modules. 
Display the inference images with the bounding boxes for both the modules. Add these images to the report with appropriate labels. 

Briefly discuss the use-cases or potential applications for the two modules.  
Q.3 - Train custom object detection model in tensorflow (50 points) 
Use the tensorflow object detection API or any other resource available online to train a custom object detection model. Several model config files are provided here. Pick a config and train the model using the tensorflow API. You can either retrain the model on the COCO dataset or train it on any custom dataset which you would like to experiment on. Following are the deliverables: 

Brief description of the selected model with screenshot of the network architecture 

Screenshot of the model being trained 

Plots of inference images with bounding boxes with appropriate labels 

List of challenges faced while training the model  
Dataset: COCO is a large-scale object detection, segmentation, and caption- ing dataset. Objects are labeled using per-instance segmentations to aid in precise object localization. COCO dataset contains photos of 91 objects types and a total of 2.5 million labeled instances in 328k images.  
Resources 
 • Resources for using the tensorflow library are provided here.
 • Further tutorials and examples for beginners can be found here. 

• Deep Learning basics - here  


