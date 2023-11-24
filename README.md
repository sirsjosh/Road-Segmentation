# Road Segmentation 

## Overview

This repository contains the code for a road segmentation project using deep learning techniques. The goal of the project is to segment roads from aerial images. The segmentation model is built using TensorFlow and Keras.

## Project Structure

- `data/`: Contains the dataset used for training and testing.
- `models/`: Stores the trained models.
- `notebooks/`: Jupyter notebooks for exploration and analysis.
- `src/`: Source code for the project.
  - `data_preparation.py`: Functions for preparing and loading the dataset.
  - `model.py`: Definition of the segmentation model.
  - `train.py`: Script for training the model.
  - `predict.py`: Script for making predictions using the trained model.
- `video.py`: Script for processing video frames.
- `requirements.txt`: List of Python dependencies.
- `README.md`: Project documentation.

## Getting Started

### Prerequisites

Make sure you have Python and the required dependencies installed. You can install the dependencies using:

```bash
pip install -r requirements.txt
