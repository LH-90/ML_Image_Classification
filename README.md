# Machine Learning Challenge 2023: Object Recognition


## Overview

The goal of this challenge is to develop a machine learning model capable of identifying various objects and letters within a series of images. The chosen targets for recognition are: Bee, Football, Laptop, Letter M, Letter T, and Train.

## Dataset Structure

The dataset is organised in a main directory named "Dataset" with 6 sub-directories, each dedicated to a specific object or letter. These sub-directories contain images relevant to the respective target.

Link to the dataset: https://drive.google.com/drive/folders/1xySHpWBCxZoBf7pEC3GIx3lWyfTcjEBo

## Setup

- Clone this repo
- Prepare the dataset: Create a new directory named "Dataset", inside the "Dataset" directory, create 6 sub-directories according to your dataset structure and import the images into their respective subdirectories
- Create a virtual environment: `python3 -m venv myenv`
- Activate the virtual environment: `source myenv/bin/activate`
- Install the dependencies in the activated environment (myenv): `pip install numpy tensorflow matplotlib scikit-learn`
- Run the code inside **image_classification.ipynb**

## Model Development in VS Code

1. Install and import necessary libraries

2. Data preprocessing: load, split the data into training and testing sets and perform necessary preprocessing steps, such as rescaling and resizing

3. Develop neural network architecture: build the neural network architecture using the Keras library, adjust the model architecture based on the requirements of the challenge

4. Compile, train and evaluate: compile the model, train it on the training set, and evaluate its performance on the validation set

5. Check the model: after training, check the model by predicting a random picture from the test set






