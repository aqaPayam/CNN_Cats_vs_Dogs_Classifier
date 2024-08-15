# CNN Cats vs Dogs Classifier

This repository contains the implementation of a Convolutional Neural Network (CNN) to classify images of cats and dogs. This project is a part of the Deep Learning course (HW2) instructed by Dr. Soleymani.

## Project Overview

The goal of this project is to apply CNNs to solve an image classification problem of distinguishing between cats and dogs. We make use of the `cats_and_dogs_filtered` dataset, which includes images of cats and dogs that will be used for training and validation.

## Dataset

The dataset is sourced from the [ML EDU Datasets](https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip). The data contains two folders: `train` and `validation`, with subdirectories for `cats` and `dogs`. 

## Task: Cats vs Dogs Classification

The model is trained on a subset of the dataset and tested on a validation set. The primary aim is to explore and implement the usage of CNNs to achieve accurate classification.

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/AqaPayam/CNN_Cats_vs_Dogs_Classifier.git
    ```

2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the dataset:
    The dataset will be automatically downloaded and unpacked as part of the notebook execution.

4. Run the Jupyter notebook:
    ```bash
    jupyter notebook HW2_CNN_TODO.ipynb
    ```

## Requirements

- Python 3.x
- TensorFlow
- Keras
- Jupyter Notebook
- Google Colab (optional, for GPU support)

## Running the Model

1. Ensure that the dataset is downloaded and unpacked.
2. Follow the notebook instructions to train and validate the CNN model on the Cats vs Dogs dataset.

## Acknowledgments

This project is part of the Deep Learning course at [Institution Name] by Dr. Soleymani.
