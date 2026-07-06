#  Brain Tumor Detection using Deep Learning

A web application that detects the presence of brain tumors from MRI images using a Convolutional Neural Network (CNN) built with TensorFlow/Keras. Users can upload an MRI scan through a simple Flask web interface and receive the predicted tumor type along with the model's confidence score.

## Features

- Upload brain MRI images through a web interface
- Detects whether a tumor is present
- Classifies tumors into:
  - Glioma
  - Meningioma
  - Pituitary Tumor
  - No Tumor
- Displays prediction confidence
- Fast inference using a pre-trained TensorFlow model
- REST API endpoint for predictions
