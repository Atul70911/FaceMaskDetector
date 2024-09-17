# FaceMaskDetector
A Face Mask Detector built using deep learning techniques to identify whether a person is wearing a face mask or not. This project utilizes a convolutional neural network (CNN) to classify images into two categories: with mask and without mask.

Table of Contents
Overview
Dataset
Installation
Usage
Model
Results

Overview
With the rise of the COVID-19 pandemic, wearing a mask has become essential to minimize the spread of the virus. This Face Mask Detector project aims to automate the process of detecting if a person is wearing a face mask in real-time using a webcam or from an image.

Key Features:

Detects whether a person is wearing a face mask or not.
Works in real-time through webcam integration.
High accuracy and efficiency for practical use.
Dataset
The dataset used for training the model consists of images of people with masks and without masks. It is important to preprocess the images (resizing, normalization, etc.) to feed into the neural network.

Download Dataset 
Using kaggle API to import dataset rather than downloading.

Model
The Face Mask Detector uses a CNN architecture to classify images into two categories:

With Mask
Without Mask
Model Architecture:
Convolutional layers to extract features from the images.
MaxPooling layers to downsample the feature maps.
Fully connected layers for classification.
You can adjust the architecture and hyperparameters in the model.py file.

Results
The model achieved an accuracy of 92% on the validation set after training.


Contributing
If you would like to contribute to this project, feel free to submit a pull request or open an issue.

Fork the repository.
Create your feature branch (git checkout -b feature/YourFeature).
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature/YourFeature).
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

