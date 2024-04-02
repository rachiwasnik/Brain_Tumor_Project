# Brain Tumor Detection using VGG16 

This repository contains code for training and deploying a deep learning model (VGG16) to detect the presence of brain tumors in MRI images. The dataset consists of two folders: "yes" containing images with brain tumors and "no" containing images without brain tumors.

Dataset link : https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection

Objectives
Develop a deep learning model capable of accurately detecting brain tumors in MRI images.
Train the model using the VGG16 architecture on a dataset of labeled brain MRI images.
Evaluate the model's performance on a separate test set to assess its accuracy and reliability.
Provide a user-friendly interface for users to upload MRI images and obtain predictions regarding the presence of brain tumors.
Results
After training the VGG16 model on the provided dataset, the model achieved an accuracy of X% on the test set, demonstrating its effectiveness in accurately detecting brain tumors in MRI images.

Process
Data Preparation: Organize the dataset into two folders: "yes" containing images with brain tumors and "no" containing images without brain tumors.

Model Training: Utilize the VGG16 architecture to train the deep learning model on the labeled MRI images dataset. The model is trained on a GPU for faster convergence.

Model Evaluation: Evaluate the trained model's performance on a separate test set to assess its accuracy, precision, recall, and F1-score. This ensures the model's reliability and effectiveness in detecting brain tumors.

Results: After providing MRI images and we receive predictions regarding the presence of brain tumors.

Dependencies
Python 3.x
TensorFlow
Keras
google colab
