# Image Classification Repository

This repository contains four Jupyter notebooks and code related to image classification using deep learning with TensorFlow and Keras. In these notebooks, we'll explore different techniques and models for classifying images of clothing and distinguishing between pictures of cats and dogs.

## Notebooks

1. **Clothing Classification**: In this notebook, we build and train a neural network to classify images of clothing, such as sneakers and shirts, using TensorFlow and Keras.

2. **Clothing Classification-CNN**: In this notebook, we build and train a neural network with convolutional layers to classify clothing images using TensorFlow and Keras. CNNs are powerful for image classification tasks.

3. **Cats_and_Dog**: This notebook focuses on classifying images into pictures of cats or dogs. We build an image classifier using the `tf.keras.Sequential` model and load data using `tf.keras.preprocessing.image.ImageDataGenerator`. This notebook does not use data augmentation.

4. **using_Image_augmentation**: Similar to the third notebook, this one also classifies images into pictures of cats or dogs. However, it incorporates data augmentation techniques to enhance the model's performance.

## Data

The first and second notebooks in this repository use the [Fashion MNIST dataset](https://github.com/zalandoresearch/fashion-mnist). Fashion MNIST contains 70,000 grayscale images in 10 categories. Each image represents an individual article of clothing at a low resolution of 28 x 28 pixels. Here's what you can expect to find in the dataset:

- 60,000 training images.
- 10,000 test images.
- 10 different clothing categories, including items like sneakers, shirts, and more.

You can access the Fashion MNIST dataset through TensorFlow, or you can download it from the official repository linked above.

The third and fourth notebooks focus on classifying images of cats and dogs. We use a filtered version of the "Dogs vs. Cats" dataset, originally provided by Microsoft Research and available on Kaggle. To access this dataset and prepare it for the notebooks, we will perform the following steps:

1. Download the dataset from a specified URL.
2. Unzip the dataset to the Colab filesystem.
3. Utilize `tf.keras.preprocessing.image.ImageDataGenerator` to read the data from disk.

For instructions on downloading and preparing the "Dogs vs. Cats" dataset, please refer to the respective notebooks (3rd and 4th) for detailed information and code.
