# Sentiment140 Dataset Download and Setup

## Project Introduction
This project aims to analyze the Sentiment140 dataset, which contains 1.6 million labeled tweets for sentiment analysis. We apply various pre-processing techniques, build a Logistic Regression classifier, and explore improvements through a topic-based approach. This README will guide you on how to download the dataset and prepare it for use in this project.

## Dataset Download and Preparation
Follow the steps below to download the dataset and prepare it for use:

### Steps:
1. **Download the Dataset:**
   - Visit the Kaggle dataset page: [Sentiment140 Dataset](https://www.kaggle.com/datasets/kazanova/sentiment140).
   - Click on "Download" to get the dataset.

2. **Extract the Dataset:**
   - Once the dataset is downloaded, unzip the file.
   - The dataset will typically be named `training.1600000.processed.noemoticon.csv`.

3. **Rename the Dataset:**
   - Rename the file to `sentiment140.csv` to ensure consistency with the project code.

4. **Move the File:**
   - Place the renamed file (`sentiment140.csv`) in the appropriate directory where the project expects the dataset to be loaded.

Now, you are ready to run the classification pipeline on the Sentiment140 dataset!

## Project Structure
- `/` : Directory where the `sentiment140.csv` file should be placed.
