# Fake News Data Analysis

This repository contains a Python script for analyzing fake news using the Passive Aggressive Classifier. The script takes a dataset of news articles and classifies them into "FAKE" or "REAL" categories. In this README, you'll find information about the project, how to run the code, and the project's structure.

## Table of Contents
- [Project Overview](#project-overview)
- [Requirements](#requirements)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## Project Overview

Fake news has become a significant concern in the era of information overload. This project aims to classify news articles as either "FAKE" or "REAL" using the Passive Aggressive Classifier and TF-IDF vectorization. The code provided here allows you to load a dataset, preprocess the text data, train the classifier, and evaluate its accuracy.

## Requirements

Before you run the code, you'll need to make sure you have the following dependencies installed:

- Python 3.x
- NumPy
- pandas
- scikit-learn

You can install the required packages using the following command:

```bash
pip install numpy pandas scikit-learn
```

## Usage

1. **Clone the Repository**

   Clone this repository to your local machine using Git:

   ```bash
   git clone https://github.com/kayteekay1412/Fake-news-detector.git
   cd Fake-news-detector
   ```

2. **Download and Extract the Dataset**

   The dataset is included in a zip file (`news.zip`) within the repository. You'll need to extract it. Run the following command in the project directory:

   ```bash
   unzip news.zip
   ```

3. **Run the Code**

   Open a terminal or command prompt and navigate to the project directory. Run the Python script `FakeNewsDetector.py` using the following command:

   ```bash
   python FakeNewsDetector.py
   ```

   The script will load the dataset, preprocess the text data, train the Passive Aggressive Classifier, and display the accuracy score and a confusion matrix.

4. **Interpret the Results**

   The script will output the accuracy of the model in classifying fake and real news articles. You can also observe the confusion matrix for further analysis.

## Project Structure

The project is organized as follows:

```
Fake-news-detector/
│
├── FakeNewsDetector.py    # Python script for fake news analysis
│
├── news.zip               # Dataset (zipped for distribution)
│
├── README.md              # This README file
```
