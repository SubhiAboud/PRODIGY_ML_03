# PRODIGY_ML_03
Here's the description of the notebook for use in a README file, in English:

# Image Classification Notebook (Cats and Dogs)

This notebook implements an image classification task to distinguish between images of cats and dogs. It uses a dataset containing images of cats and dogs, and trains and evaluates several deep learning models.

## Main Contents:

1. **Library Imports and Data Setup:**
   - Importing necessary libraries such as TensorFlow, Keras, and OpenCV.
   - Loading and preparing the dataset.

2. **Data Exploration:**
   - Displaying the distribution of images between cat and dog categories.
   - Showing random samples of images.

3. **Data Generator Setup:**
   - Creating data generators for training and validation with data augmentation techniques applied.

4. **Model Building and Training:**
   - Utilizing transfer learning models such as ResNet50V2 and MobileNetV2.
   - Training a neural network model using MobileNetV2 as a feature extractor.
   - Training an SVM model on features extracted from MobileNetV2.

5. **Model Evaluation:**
   - Calculating model accuracies on the validation set.
   - Plotting learning curves for the models.

6. **Model Comparison:**
   - Comparing the performance of different models in terms of accuracy.
   - Comparing the sizes of saved models.

7. **Model Saving:**
   - Saving trained models for future use.

This notebook provides a comprehensive look at the process of image classification using deep learning and machine learning techniques, and can be used as a starting point for similar projects in computer vision.
data_URL : https://www.kaggle.com/competitions/dogs-vs-cats/data
