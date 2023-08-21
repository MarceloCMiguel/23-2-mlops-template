# Machine Learning Operations and Interviews

This repository contains the template code and data files for the Machine Learning Operations and Interviews project. The project is part of the Machine Learning Operations and Interviews course offered by [Insper](https://insper.github.io/mlops).

## Repository Structure

The repository is organized into several key folders:

1- data: This folder contains the dataset files used in the project. It is further divided into the following subfolders:

- original: Raw dataset files in their original form.

- processed: Processed dataset files that have been cleaned and preprocessed for model training.
- predict: Data files used for making predictions using the trained model.

2- model: In this folder, you can find the trained machine learning model saved using the pickle format. This model is ready to be loaded and used for predictions.

3- notebooks: Explore the Jupyter Notebooks in this folder to gain insights into the data and visualize patterns. These notebooks provide interactive visualizations and analyses that help understand the dataset and model performance.

4- src: The source code for the project is located in this folder. It includes the following Python scripts:

- predict.py: A script to load the trained model and make predictions on new data.
- process.py: This script handles the data - preprocessing steps, transforming the raw data into a format suitable for training.
- train.py: Use this script to train the machine learning model using the processed data.
