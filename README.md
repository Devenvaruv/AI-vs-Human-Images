# AI-vs-Human-Images

## Project Overview
The project aims to address the growing importance of detecting AI generated images, which have significant implications for journalism, copyright, and security. This project includes exploration, model building, and analysis steps to distinguish AI generated images from real ones.

## Project Components

1. **Data Acquisition & Validation**:
   - We utilize a dataset from Kaggle that includes real images and state-of-the-art (SOTA) generative samples.

2. **Exploratory Data Analysis (EDA)**:
   - Visual analysis to understand class balance and potential artifacts in the dataset.

3. **Model Development**:
   - **Model A**: Custom CNN built from scratch.
   - **Model B**: ResNet-18 with transfer learning.
   - **Model C**: EfficientNet-B0 with fine-tuning of the last few layers.

4. **Training & Evaluation**:
   - Utilizes stratified dataset splits and consistent data loaders.
   - Comparison of models based on accuracy, precision, recall, F1 score, and AUC.

5. **Inference on Test Set**:
   - Generates a Kaggle-ready submission from an inference on the test dataset.

## Repository Contents

- `notebooks/Final_Project_.ipynb`: The main notebook containing code for data processing, model training, and evaluation.
- `FinalProjectPresentation.pptx`: A presentation summarizing the project's process, results, and findings.
- `output`: A folder that contains all the model results.
- `models`: Contains all three model weights.


## Getting Started

You would need to make a copy of the notebook and just run it!