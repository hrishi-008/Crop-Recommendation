# Crop Recommendation Using Artificial Neural Network

This project focuses on recommending crops based on various environmental and soil parameters using an Artificial Neural Network (ANN).

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The aim of this project is to predict the most suitable crop to be cultivated based on certain parameters using an ANN model. The project involves data preprocessing, building and training an ANN, and evaluating the model's performance.

## Dataset

The dataset used in this project is `Crop_recommendation.csv`, which contains various environmental and soil parameters along with the recommended crops.

## Project Structure

The project is organized into the following parts:

1. **Data Preprocessing**:
   - Importing libraries and the dataset.
   - Encoding categorical data using One Hot Encoding.
   - Splitting the dataset into training and testing sets.
   - Feature scaling.

2. **Building the ANN**:
   - Initializing the ANN.
   - Adding input, hidden, and output layers.

3. **Training the ANN**:
   - Compiling the ANN.
   - Training the ANN on the training set.

4. **Making Predictions and Evaluating the Model**:
   - Predicting the test set results.
   - Making the confusion matrix.
   - Calculating accuracy, precision, recall, and F1 score.

## Installation

To run this project, you need to have Python and the following libraries installed:

- numpy
- pandas
- tensorflow
- scikit-learn

You can install these libraries using the following command:

```bash
pip install numpy pandas tensorflow scikit-learn
