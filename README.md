# Mushroom-Poison-Prediction

## Project Overview
This project predicts whether a mushroom is poisonous or edible using machine learning, specifically a Random Forest Classifier. The model is trained on mushroom characteristics from a dataset to make accurate classifications.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Preprocessing](#data-preprocessing)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Making Predictions](#making-predictions)
- [File Structure](#file-structure)
- [Requirements](#requirements)
- [Usage](#usage)
  
## Data Preprocessing
- **Handling Missing Values** : Columns with excessive missing data were removed, and remaining missing values were filled with the mode or median.
- **Label Encoding** : Categorical columns were converted to numerical values using label encoding.
- **Feature Selection**: Only essential features were kept to enhance model performance.
- **Model Training and Evaluation** : A Random Forest Classifier was used due to its high accuracy and suitability for classification tasks.
- **Data Split**: The dataset was split into training (80%) and testing (20%) sets.
- **Training**: The model was trained using 20 estimators and a set random seed for reproducibility.
- **Evaluation**: The model achieved an accuracy of 0.9993 on the training data and 0.9885 on the test data, along with high precision and recall.
- **Making Predictions**: Final predictions on a new test dataset were saved in submission.csv, with classes mapped as:

**e for edible**
**p for poisonous**
## File Structure
- **train.csv** : Training data used for model training.
- **test.csv**: Test data for model evaluation.
- **submission.csv**: Final predictions for submission.
## Requirements
- **Python 3.x**
- **Libraries: pandas, numpy, scikit-learn**
