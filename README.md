# Spam Message Classification Project

This project explores spam detection using SMS message data. The notebook compares classification approaches such as Naive Bayes and K-Nearest Neighbors (KNN) to classify messages as either **ham** or **spam**.

## Project Files
- `Spam_message_NB_KNN.ipynb` - Jupyter notebook containing the data analysis, preprocessing, modeling, and evaluation steps.
- `spam.csv` - Dataset containing SMS messages labeled as `ham` or `spam`.

## Objective
The goal is to build a simple machine learning workflow for text classification and evaluate how well different models perform on spam detection.

## Requirements
Install the following Python libraries before running the notebook:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install them with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run
1. Open the notebook file `Spam_message_NB_KNN.ipynb` in Jupyter Notebook or JupyterLab.
2. Run the cells sequentially to load the dataset, preprocess the text, train the models, and view the results.

## Dataset Overview
The dataset contains SMS text messages with labels:
- `ham` - legitimate messages
- `spam` - unsolicited promotional or suspicious messages

## Notes
This is a beginner-friendly classification project focused on text preprocessing and model comparison for spam detection.
