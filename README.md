# Iris Flower Species Prediction using Decision Tree

## Project Overview

This project focuses on using a Decision Tree classifier to predict the species of iris flowers based on their sepal and petal characteristics. Leveraging the famous Iris flower dataset, the goal is to build a model capable of accurately classifying iris flowers into their respective species: Setosa, Versicolor, or Virginica. The project demonstrates the application of machine learning algorithms in classifying and understanding different species of flowers based on their features.

## Table of Contents

- [Introduction](#introduction)

- [Dataset](#dataset)

- [Features](#features)

- [Methodology](#methodology)

- [Results](#results)

- [Usage](#usage)

- [Contributing](#contributing)

- [License](#license)

## Introduction

Handwritten digit classification is a common task in machine learning and computer vision. The objective is to create a model that can recognize and classify handwritten digits from 0 to 9. This project uses a Support Vector Machine (SVM) classifier to achieve this goal, providing a robust approach to image recognition.

## Dataset

The dataset used for this project is the famous Iris flower dataset, which contains measurements of sepal length, sepal width, petal length, and petal width for 150 iris flowers, with 50 samples from each of the three species: Setosa, Versicolor, and Virginica.

## Features

The key features of this project are:

- **Sepal Length**: Length of the sepal in centimeters.

- **Sepal Width**: Width of the sepal in centimeters.

- **Petal Length**: Length of the petal in centimeters.

- **Petal Width**: Width of the petal in centimeters.

## Methodology

1\. **Data Preprocessing**:

    - Loaded the Iris flower dataset.

    - Checked for missing values and outliers.

    - Split the dataset into training and test sets.

2\. **Exploratory Data Analysis (EDA)**:

    - Visualized the distribution of each feature.

    - Analyzed the relationships between different features.

3\. **Model Implementation**:

    - Implemented a Decision Tree classifier using the `scikit-learn` library.

    - Trained the model on the training set.

4\. **Model Evaluation**:

    - Evaluated the model's performance using metrics such as accuracy, precision, recall, and F1-score.

    - Analyzed the confusion matrix to understand the classification performance.

## Results

The Decision Tree model achieved the following performance metrics on the test set:

- **Accuracy**: 92.38%

- **Precision**: 92.00%

- **Recall**: 92.00%

- **F1-score**: 92.00%

These results demonstrate the effectiveness of the Decision Tree classifier in accurately predicting the species of iris flowers based on their sepal and petal characteristics.

## Output of Decision Tree

The trained Decision Tree model can be visualized to understand how it makes predictions based on the provided features (sepal length, sepal width, petal length, and petal width). Below is an example visualization of the Decision Tree:
![image](https://github.com/Sahilwarudkar27/Iris-Flower-Species-Prediction/assets/99885674/120524a2-eecd-4afe-a9ef-bdfa8990baaf)

## Usage

To use this project, follow these steps:
1. **Access the Kaggle notebook**:
   - Open the Kaggle notebook by clicking on the following link: [[Link to Kaggle notebook](https://www.kaggle.com/code/sahilwarudkar/iris-flower-species-prediction/edit)]
2. **Run the notebook**:
   - Once the notebook is open, you can run each cell sequentially to see the analysis and model implementation.


## Contributing

Contributions are welcome! Please follow these steps:

1\. Fork the repository.

2\. Create a new branch (`git checkout -b feature-branch`).

3\. Commit your changes (`git commit -m 'Add new feature'`).

4\. Push to the branch (`git push origin feature-branch`).

5\. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
