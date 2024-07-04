# Real Image to Monet using CycleGAN:

This project uses CycleGAN to transform real images into Monet-style paintings. The project involves loading a dataset, preprocessing the data, building and training a CycleGAN model, and generating Monet-style images from real photos.

## Dataset:

The dataset used in this project is sourced from a Kaggle dataset, specifically designed for GAN projects.

## Requirements:

- Python 3.x
- numpy
- pandas
- tensorflow
- tensorflow-addons
- matplotlib
- PIL (Pillow)

## Key Sections in the Notebook:

#### 1. Notebook Initialization

The notebook contains basic initialization steps, These include imports of necessary libraries and setting up 

configurations for the environment.

#### 2. Libraries and Configurations

The initial cells are importing libraries like TensorFlow, Keras, NumPy, Matplotlib, and others essential for data handling, neural network modeling, and visualization. 

#### 3. Load and Preprocess the Data

This section is responsible for loading the dataset which includes real photos and Monet-style paintings. It typically involves:

- Defining the paths to the datasets.

- Writing functions to load and preprocess the images, such as resizing, normalizing, and augmenting them for training.

#### 4. Define the Model Architecture

The notebook defines the architecture of the Generative Adversarial Network (GAN) used for style transfer. This includes:

- A Generator model: Converts real photos to Monet-style images.

- A Discriminator model: Evaluates the authenticity of the generated Monet-style images.

#### 5. Compile and Train the Model

The training process involves:

- Defining loss functions and optimizers for both the generator and discriminator.

- Compiling the model and setting up training loops.

- Monitoring the training process using metrics such as loss and accuracy.

#### 6. Save and Load Model Weights

This part involves saving the trained model weights and loading them for inference. It ensures that the model can be reused without retraining.

#### 7. Visualize Monet-esque Photos

In the final section, the notebook demonstrates how to use the trained generator model to convert real photos into Monet-style paintings. This involves:

- Selecting random photos from the dataset.

- Converting these photos using the trained generator.

- Visualizing the original and converted images side by side.

## Summary

It covers:

- Loading and preprocessing the data.

- Defining and training the GAN model.

- Saving the model weights.

- Using the trained model for inference and visualization.

## Example:

Here’s an example of a generated Monet-style image:

![Screenshot (489)](https://github.com/Mutyala-Veera-Abhi-Nanda/Real-Image-to-Monet/assets/164295902/cdd8df54-522d-438c-a094-2fc12f3488ad)

