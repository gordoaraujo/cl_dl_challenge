# Deep Learning Data Challenge -- Hurricane Damage Detector

## Goal
Apply Deep Learning for image recognition techniques to a real world data set.

## Paper
The original paper can be found [here](https://arxiv.org/pdf/1807.01688.pdf)

## Project Intro/Objective
The key objective of the project is to work on an open dataset consisting of satellite imagery data to detect damaged buildings due to a hurricane. These satellite images are taken from the aftermath of Hurricane Harvey in 2017. The goal would be to build a classifier which can identify if a specific region (based on the input satellite image) is likely to have suffered from flooding and other typical structural damages due to Hurricane Harvey.

## Project Questions
1. Do split the train dataset into 80:20 (train-validation split – use seed=42). 
2. Resize images to 128x128
3. Build a basic CNN model from scratch (2-3) layers which should serve as a baseline model and give you around close to 80%+ accuracy easily
4. In order to improve model performance, try
   1. Different approaches of data augmentation, 
   2. more complex CNN architectures, 
   3. pre-trained models, 
   4. transfer learning along with NN training approaches like early stopping, dynamic learning rates etc.
5. Showcase model performance on test data using confusion matrix, classification reports

## Methods Used
* Deep Learning
* Data Visualization
* Predictive Modeling

## Technologies
* Python
* Pandas, Numpy, Scipy
* Sklearn, 
* Tensorflow

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is not included in this repo.
3. Data processing/transformation scripts are being kept in `notebooks\`

## Project Status: Active

## Contributing Members
* [Jose Araujo](https://github.com/gordoaraujo)
* [Mehran Chowdhury](https://github.com/MehranChowdhury)
* [Jonas Vossemer](https://github.com/jonasvossemer)
* [Vincent Zitzewitz](https://github.com/SirVincelot)