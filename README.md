# Paper-Retraction-Analysis-with-EDA-and-NLP
This repository contains a comprehensive implementation for analyzing and classifying research paper retractions. The project includes data preprocessing, feature extraction, and machine learning models to predict and identify retracted papers based on metadata and textual features.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
  - [K-means Clustering](#k-means-clustering)
  - [Reason Percentage](#reason-percentage)
  - [Publisher Analysis](#publisher-analysis)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Data Preprocessing**: Handles missing values, duplicates, and feature scaling.
- **Text Analysis**: Extracts linguistic and contextual features from abstracts.
- **Machine Learning Models**: Implements multiple classifiers (e.g., SVM, Random Forest).
- **Evaluation Metrics**: Calculates accuracy, precision, recall, and F1-score.
- **Visualization**: Generates plots to interpret model results and feature importance.

## Dataset

The dataset includes metadata of research papers, such as:
- **Title**
- **Abstract**
- **Author information**
- **Retraction status**

## Features

- **Data Preprocessing**: Handles missing values, duplicates, and feature scaling.
- **Text Analysis**: Extracts linguistic and contextual features from abstracts.
- **Machine Learning Models**: Implements multiple classifiers (e.g., SVM, Random Forest).
- **Evaluation Metrics**: Calculates accuracy, precision, recall, and F1-score.
- **Visualization**: Generates plots to interpret model results and feature importance.




Ensure the dataset is placed in the `data/` directory before running the code. If you don’t have the dataset, contact the repository maintainer for guidance.

## Installation

1. Clone the repository:
   
    git clone https://github.com/username/retraction-project.git
  

2. Navigate to the project directory:
    cd retraction-project

3. Install the dependencies:
    pip install -r requirements.txt

## Usage

Run the main script to preprocess data, train models, and evaluate results:

python main.py



---

### Cell 7: Results Section

## Results

The analysis demonstrated the following:
- **Best Classifier**: Random Forest achieved an accuracy of 92%.
- **Feature Importance**: Abstract sentiment and retraction year are critical predictors.

### K-means Clustering

Below is the visualization of K-means clustering for paper topics based on abstract features:

![K-means Clustering](images/kmeans-cluster.png)

### Reason Percentage

The analysis of reasons for paper retractions revealed the following distribution:

![Reason Percentage](images/reason-percentage.png)

### Publisher Analysis

Analysis of publishers revealed trends in retracted publications:

![Publisher Analysis](images/publisher-analysis.png)
