# Pre-trained Image Classifier to Identify Dog Breeds
Project completed as a part of the AI programming with Python Nanodegree by Udacity

# General Information
This repository is part of a project aimed at assisting a citywide dog show organizing committee in efficiently handling contestant registration. The challenge is to ensure that only images of dogs are registered, and their breeds are correctly identified. To achieve this, a Python classifier utilizing various CNN model architectures (ResNet, AlexNet, and VGG) has been developed.

# Principal Objectives
Identify whether submitted pet images are of dogs.
Classify the breed of dog for images that are identified as dogs.
Evaluate and compare the performance of ResNet, AlexNet, and VGG architectures for the given objectives.
Consider time resources and determine if alternative solutions could provide "good enough" results within acceptable time frames.

# Technologies Used
ImageNet: A deep learning model, specifically a Convolutional Neural Network (CNN), for image feature detection.
Python 3.0
ResNet, AlexNet, and VGG model architectures.

# Setup
Ensure Python 3 is installed on your system (Installing Python Guide).
Download the workspace files and organize them in a single folder.
Two folders of interest: pet_images for classification and uploaded_images for user-submitted images.
Use terminal/command prompt to run projects.

# Usage
Open a terminal from the workspace folder and run 'check_images.py'. The program will classify the 40 images from the 'pet_images' folder.
Open a terminal from the uploaded_images folder and run 'sh run_models_batch_uploaded.sh'. This will use all three model architectures to classify the images in the uploaded_images folder, generating result files in the workspace in .txt format.
