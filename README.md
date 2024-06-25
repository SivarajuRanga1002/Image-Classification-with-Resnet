# Image-Classification-with-Resnet

# Image Classification Comparison with ResNet 50 and Other Models

This repository contains the implementation and results of an image classification project where ResNet 50 and another pre-trained model from torchvision are used to classify images from selected ImageNet classes. The project evaluates and compares the performance of these models based on accuracy and architectural differences.

## Project Overview

The project involves:
- Selecting 10 classes from the ImageNet dataset.
- Running inference on images from these classes using ResNet 50 and another selected model from torchvision.
- Comparing the performance of these models in terms of accuracy and discussing the results based on their architectural differences.

## Key Features

- **Dual Model Evaluation**: Uses ResNet 50 and one other torchvision model to perform image classification.
- **Accuracy Assessment**: Evaluates and compares the accuracy of the models on a set dataset.
- **Architectural Insights**: Provides insights into how model architecture influences performance.

## Setup and Usage

### Cloning the Repository

    ```bash
    git clone https://github.com/yourusername/image-classification-comparison.git
    
**Running the Notebook**

    ```bash
    Copy code
    Navigate to the notebook provided in this repository: Ranga_Resnet_PartAandPartB.ipynb.
    This can be done in Google Colab or any environment that supports Jupyter Notebooks.

**Upload Images:**

    ```bash
    Upload images to the sample_data/images/ directory as per the instructions in the notebook.
    Each class from ImageNet should have two images for a total of 20 images.
    Install Dependencies (if not using Google Colab):

**Copy code**

    ```bash
    pip install torch torchvision
    
**Run the Notebook:**
    ```bash
    Execute all cells in the notebook to see the classification results and confidence scores for each image.
