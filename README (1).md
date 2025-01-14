
# Intel Image Classification with TensorFlow

This repository demonstrates a practical approach to image classification using the Intel Image Classification dataset. It focuses on exploring, preparing, and training machine learning models to categorize images into various classes, such as buildings, forests, glaciers, mountains, seas, and streets. The workflow leverages TensorFlow's `image_dataset_from_directory` for efficient dataset management and includes techniques to normalize image data for better model performance.

## Project Overview

### Key Tasks:
1. **Data Exploration**  
   - Analyze the distribution of images in the training and test sets.
   - Check for balance in class proportions across datasets.

2. **Data Preparation**  
   - Load the dataset using TensorFlow's `image_dataset_from_directory`.
   - Normalize image data between values 0 and 1 for consistent model input.

3. **Model Training and Testing**  
   - Train a neural network on the training dataset.
   - Evaluate model performance on the test dataset.

## Dataset

- **Source:** [Intel Image Classification Dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)  
- **Structure:** The dataset is pre-partitioned into training and test sets. Each class is organized into separate folders for easy loading.

## Getting Started

### Requirements
- Python 3.7 or higher
- TensorFlow 2.x
- Additional dependencies specified in the notebook

### Running the Notebook
1. Download and unzip the dataset.
2. Install required Python packages.
3. Open the notebook and follow the instructions in each section to execute the cells.

## Notebook Highlights
- **Code Cells:** 36
- **Markdown Cells:** 22
- Kernel: `priyam_env` (Python 3.12.4)

## Results
- A well-balanced dataset ensures fair model evaluation.
- Normalized image inputs improve training stability and model performance.
