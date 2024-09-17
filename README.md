# Potato Leaf Disease Identification App

## Overview

This repository contains code and resources for classifying potato leaf diseases into three categories: Healthy, Early Blight, and Late Blight. The models used are Convolutional Neural Networks (CNN) trained to identify these diseases from images of potato leaves.

## Repository Structure

- **`dataset/`**: Contains the dataset for training and evaluating the models.
- **`models/`**: Contains pre-trained models and code for training new models.
- **`notebooks/`**:
  - **`CNN_Model_Training.ipynb`**: Colab notebook for training a standard CNN model.
  - **`CNN_Noise_Model_Training.ipynb`**: Colab notebook for training a CNN model with noise augmentation.
- **`README.md`**: This file.

## Data

The dataset used for training and evaluation can be downloaded from the following link:

- [Potato Leaf Disease Dataset](https://drive.google.com/drive/folders/1IB30n-VIPByRIccrG9BhkWd7pp0naged?usp=sharing)

### Dataset Structure

The dataset is organized into folders by category:
- `Healthy/`
- `Early_Blght/`
- `Late_Blght/`

Each folder contains images of potato leaves.

## Colab Notebooks

### 1. CNN Model Training

- **Notebook Link**: [CNN_Model_Training.ipynb](https://colab.research.google.com/drive/1B5Ggz4Q_JWFiFKY6PnE0IN_TBuevkH78?usp=sharing)
- **Purpose**: Train a standard CNN model to classify potato leaf diseases.
- **Instructions**:
  1. Open the notebook in Google Colab.
  2. Follow the step-by-step instructions to upload the dataset, train the model, and evaluate its performance.
  3. The notebook will guide you through preprocessing the data, defining the model architecture, training the model, and evaluating its accuracy.

### 2. CNN with Noise Model Training

- **Notebook Link**: [CNN_Noise_Model_Training.ipynb](https://colab.research.google.com/drive/1vRnW7ZFJBBH2Kie5vC5IlEmVfkVnXrYE?usp=sharing)
- **Purpose**: Train a CNN model with noise augmentation to potentially improve robustness.
- **Instructions**:
  1. Open the notebook in Google Colab.
  2. Follow the instructions to upload the dataset, train the model with added noise, and evaluate its performance.
  3. The notebook includes steps for data augmentation with noise, defining the model architecture, training, and evaluating.

## Usage

1. **Download and Prepare Dataset**:
   - Download the dataset from the provided Google Drive link.
   - Extract the dataset and ensure it is organized as specified.

2. **Run the Notebooks**:
   - Open the provided Colab notebooks in Google Colab.
   - Follow the instructions in each notebook to run the code, train the models, and evaluate their performance.

3. **Model Inference**:
   - After training, you can use the models to classify new potato leaf images. 
   - Upload your leaf images to the app or script that utilizes the trained models for inference.

## Dependencies

- TensorFlow or PyTorch (as specified in the Colab notebooks)
- OpenCV (for image processing)
- Google Colab (for executing notebooks)

## Contributing

Contributions are welcome! You can:
- Improve model performance.
- Add new features or functionalities.
- Report any issues or bugs.

To contribute, please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

 