# Deepfake Detection Project

## Overview

This project focuses on deepfake detection using a combination of the Celeb_DF and Deepfake Detection Challenge (DFDC) datasets. The main workflow involves two distinct steps: preprocessing the data and training/evaluating the deepfake detection model.

## Dataset

Our dataset is a combination of two datasets: Celeb_DF and DFDC. You can access the dataset [here](https://drive.google.com/drive/folders/141QZxkvyrtaSV24GCqy7CokPTnJNYKa4?usp=sharing). The dataset is organized into four folders, two for real faces and two for deepfakes, with one folder from each dataset.

## Steps to Reproduce

### Step 1: Dataset Preparation

- Download the dataset from the provided link.
- Upload the four folders to your Google Drive. (Note: This project is developed in Google Colab, and Google Drive is used for storage.)

### Step 2: Preprocessing

Navigate to the `pre_processing` folder, which contains five code files:

1. `pre_processing_celeb_fake_face.ipynb`
2. `preprocessing_celeb_real_face.ipynb`
3. `pre_processing_dfdc_fake_face.ipynb`
4. `pre_processing_dfdc_real_face.ipynb`
5. `labels.ipynb`

Execute each of the four preprocessing files corresponding to the datasets. The processed files will be saved in the Google Drive itself. The `labels.ipynb` file is used to create labels for the videos.

### Step 3: Model Training and Evaluation

Navigate to the `Model_and_train.ipynb` file. Update the file locations for the preprocessed files according to your Google Drive setup. Run the file to train and evaluate the deepfake detection model.

## Code Files

1. `pre_processing_celeb_fake_face.ipynb`: Preprocess Celeb_DF dataset fake face videos.
2. `preprocessing_celeb_real_face.ipynb`: Preprocess Celeb_DF dataset real face videos.
3. `pre_processing_dfdc_fake_face.ipynb`: Preprocess DFDC dataset fake face videos.
4. `pre_processing_dfdc_real_face.ipynb`: Preprocess DFDC dataset real face videos.
5. `labels.ipynb`: Create labels for the preprocessed videos.
6. `Model_and_train.ipynb`: Train and evaluate the deepfake detection model.

## Instructions

1. Run the preprocessing code files to prepare the data.
2. Adjust file locations in the `Model_and_train.ipynb` file.
3. Run the `Model_and_train.ipynb` file to train and evaluate the deepfake detection model.

Feel free to explore and modify the code to suit your needs. If you encounter any issues, refer to the provided dataset link and follow the outlined steps for successful execution.