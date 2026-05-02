# 🩺 Baymax Project: Pneumonia Detection via Medical Imaging & Clinical Data

## Project Overview
This repository contains a machine learning pipeline designed to detect pneumonia by analyzing a combination of chest X-ray images and clinical blood data. The objective is to provide a multi-modal diagnostic tool that leverages both computer vision and tabular data for robust predictions.

## Architecture & Methodology
The project utilizes a hybrid machine learning approach:
* **Deep Learning (Feature Extraction):** A `ResNet50V2` architecture is employed to process and extract complex visual features from the medical imaging. 
* **Machine Learning (Classification):** A `Random Forest` classifier synthesizes the extracted image features with the clinical blood data to make the final diagnostic prediction.

## Performance
* **Overall Accuracy:** The model achieved an **83%** overall accuracy rate on the testing dataset.

## 👥 Contributors & Team Roles
This project was developed as a collaborative academic effort:

* **Fariha:** Research methodology, dataset curation, project documentation, and pipeline architecture design.
* **Mosaddeq:** Lead technical implementation, including the core coding for the ResNet50V2 and Random Forest models.

## How to Run the Notebook
1. Clone this repository or download the `.ipynb` file.
2. Upload the notebook to Google Colab.
3. Ensure your runtime is set to a GPU/TPU accelerator (`Runtime` -> `Change runtime type`).
4. Generate a Kaggle API token from your Kaggle account settings.
5. Replace `"YOUR_KAGGLE_KEY_HERE"` in the first cell with your actual token.
6. Run the cells sequentially to execute the pipeline.
