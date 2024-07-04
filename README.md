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

#### Model Building:

Define the CycleGAN model architecture.

#### Training:

Train the CycleGAN model with the dataset.

#### Evaluation:

Generate Monet-style images from real photos.

## Results:

After training the model, you can evaluate its performance by generating Monet-style images from real photos. The generated images can be visualized using matplotlib.

## Example:

Here’s an example of a generated Monet-style image:

![Screenshot (489)](https://github.com/Mutyala-Veera-Abhi-Nanda/Real-Image-to-Monet/assets/164295902/cdd8df54-522d-438c-a094-2fc12f3488ad)

