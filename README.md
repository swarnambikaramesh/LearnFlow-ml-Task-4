# Task-4
# Human Action Recognition (HAR) Dataset and VGG Model

This repository contains the Human Action Recognition (HAR) dataset and a VGG model trained on the dataset. The dataset is sourced from Kaggle, and it consists of labeled images representing various human actions.

## Dataset

### Overview
- **Training Set:** The training set includes labeled images with corresponding actions.
- **Testing Set:** The testing set is available for evaluating the model's performance.

### Dataset Structure
- The `train` folder contains training images.
- The `test` folder contains images for evaluation.

### Classes
The dataset consists of the following action classes:
- sitting
- using_laptop
- hugging
- sleeping
- drinking
- clapping
- dancing
- cycling
- calling
- laughing
- eating
- fighting
- listening_to_music
- running
- texting

### Dataset Visualization
To visualize the distribution of human activities, check the pie chart in the [Distribution of Human Activity](#dataset-visualization) section.

## Model

### Overview
The VGG model provided in this repository is pre-trained on the HAR dataset using TensorFlow and Keras.

### Model Architecture
- The VGG model is based on the VGG16 architecture.
- The model is fine-tuned to recognize 15 different human actions.

### Usage
- You can use the provided model weights (`model.h5`) for prediction on new images.
- Modify the image path in the [Sample Image Visualization](#sample-image-visualization) section and run the script to visualize predictions.
