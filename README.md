# ASL Data Science Project: Convolutional Neural Network (CNN) using Keras

<p align="center">
  <img src="ASL Data Science/american_sign_language.PNG" alt="Project Logo" width="300" height="200">
</p>

## Overview
Welcome to the ASL Data Science project, a venture into the world of American Sign Language (ASL) recognition using Convolutional Neural Networks (CNNs) implemented with Keras. Our mission is to build a robust model capable of accurately recognizing hand gestures corresponding to ASL signs.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
American Sign Language is a crucial means of communication for individuals with hearing impairments. In this project, we harness the power of deep learning, specifically CNNs implemented in Keras, to create a model that excels at recognizing ASL signs.

## Dataset
The dataset used for training and testing the CNN model is sourced from [Kaggle](https://www.kaggle.com/datasets/datamunge/sign-language-mnist). It comprises a diverse set of images featuring different ASL signs captured in various conditions.

## Project Structure
```
ASL Data Science/
│
├── kaggle.json              # Kaggle API key for dataset download (not included in the repository)
├── sign_mnist_test/         # Test set images
├── sign_mnist_train/        # Training set images
├── ASL.ipynb                # Jupyter notebook for the project
├── requirements.txt         # File containing the names of the modules needed to be installed
├── amer_sign2.png           # Sample image 1
├── amer_sign3.png           # Sample image 2
├── american_sign_language.PNG # Project logo or relevant image
├── sign-language-mnist.zip  # Zip file containing the original dataset
├── sign_mnist_test.csv      # Test set labels in CSV format
├── sign_mnist_train.csv     # Training set labels in CSV format
├── LICENSE                  # Project license
└── README.md                # Project documentation
```

## Installation
To install the necessary dependencies, run the following commands in the shell/command prompt:
```bash
cd ASL\ Data\ Science
pip install -r requirements.txt
```

## Results
Explore the model's performance and gain insights from the evaluation. This section includes visualizations and metrics that showcase the effectiveness of the trained model.

## Contributing
If you would like to contribute to the project, please follow the guidelines outlined in README.md.

## License
This project is licensed under the GNU General Public License v2.0. Feel free to use, modify, and distribute the code for your own projects.
