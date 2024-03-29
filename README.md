## Deep Learning Nanodegree 
## Landmark Classifier & Tagging for Social Media
Project Overview
This project focuses on building a landmark classifier using Convolutional Neural Networks (CNNs). The goal is to predict the location of images, especially when no location metadata is available, by detecting and classifying landmarks depicted in the images. This addresses the need for advanced features in photo sharing and storage services, such as automatic tagging and organization.

This project develops convolutional neural networks (CNNs) for identifying landmarks on social media images. The project explores 2 methodologies: building a neural network "from scratch" and building a neural network using transfer learning (based on the VGG16 pre-trained model).

## Project Steps
1. Create a CNN to Classify Landmarks (from Scratch)
Visualize and preprocess the dataset.
Develop a CNN from scratch for landmark classification.
Explain data preprocessing choices and network architecture.
Export the best network using Torch Script.
2. Create a CNN to Classify Landmarks (using Transfer Learning)
Explore and select pre-trained models for classification.
Train and evaluate the chosen transfer-learned network.
Describe the rationale behind the pre-trained model selection.
Export the best transfer learning solution using Torch Script.
3. Deploy Model/Algorithm in an App
Use the best model to create a user-friendly app for landmark recognition.
Test the model's performance and usability.
Reflect on the model's strengths and weaknesses.

## Tools Used
PyTorch for machine learning model development.
Jupyter Notebooks for project implementation.
Torch Script for model export.

## Challenges
Underfitting for the model from scratch. solved with redisign the model architecture and train the model from start.
Overfitting for the model transffered. solved with experiment diffenrent transfered model and implementation regularizations.
