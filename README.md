# Face Mask Detection

## Overview
The **Face Mask Detection** project is a machine learning-based solution designed to identify if a person is wearing a face mask in an image. This project is relevant for public health and safety applications, especially in environments where mask-wearing is required. It leverages a large dataset of face images to train a model capable of detecting masks with high accuracy.

## Objective
The main objective of this project is to automatically detect the presence or absence of a face mask on individuals in images, aiming to support safety measures in crowded or controlled areas. This project serves as a foundation for potential real-time applications in security systems, public spaces, or health monitoring systems.

## How It Works
1. **Data Collection and Processing**: 
   - This project uses a large dataset containing thousands of images labeled as "mask" or "no mask."
   - Given the extensive size of the dataset, it was stored on Google Drive, allowing seamless integration and access directly from the cloud to save local storage and enable faster loading times.

2. **Data Preparation and Augmentation**:
   - Images are preprocessed to ensure they are suitable for training, including resizing, scaling, and normalizing.
   - Augmentation techniques, such as rotations and flips, are applied to improve the model's ability to generalize across different facial orientations and lighting conditions.

3. **Model Training**:
   - A Convolutional Neural Network (CNN) is used to classify images as either "with mask" or "without mask." This deep learning model learns to recognize patterns in the dataset, distinguishing between masked and unmasked faces.

4. **Prediction and Evaluation**:
   - After training, the model is tested on unseen data to evaluate its accuracy and reliability. This process ensures that it performs well in real-world scenarios and different image settings.
   - Predictions can be made on new images to identify whether a person is wearing a mask or not.

## Key Benefits
- **Public Health Support**: Provides a reliable way to monitor mask compliance in public spaces.
- **Automated Monitoring**: Can be integrated into security or surveillance systems for automated mask detection.
- **Versatile Applications**: Useful for various industries, including healthcare, transportation, and event management, where mask compliance is important.

## Technologies Used
- **Python**: Primary programming language for data processing, model training, and evaluation.
- **TensorFlow/Keras**: Used to build and train the Convolutional Neural Network (CNN) model for image classification.
- **OpenCV**: For image preprocessing and manipulation, such as resizing and scaling.
- **NumPy**: For handling numerical data and array operations.
- **Pandas**: Used for data manipulation and handling structured datasets.
- **Matplotlib/Seaborn**: Visualization libraries used to explore data distributions and relationships.
- **Google Drive Integration**: Cloud storage solution to handle the large dataset efficiently.

## Potential Applications
This project can be adapted for practical use in:
- **Security and Surveillance Systems**: To automatically detect and alert staff when individuals are not wearing masks.
- **Public Transportation**: Monitoring mask compliance in crowded settings.
- **Event Management**: Enforcing health guidelines in large gatherings and ensuring compliance.

## Dataset Consideration
Due to the size of the dataset, which contains thousands of high-resolution images, it is stored on Google Drive. This setup allows efficient access and processing, leveraging cloud storage to manage large data files without overwhelming local resources. You can view or download the dataset from [this Google Drive link](https://drive.google.com/drive/folders/1Bt566RAQ1pLNUkozJtEMOumLZZhz-PxZ?usp=sharing).

## How to Use
This model can be used independently to analyze images for mask compliance. For real-time applications, it could be integrated with camera feeds to monitor multiple individuals continuously. The model can also be part of a larger system focused on health compliance and safety monitoring.
