# MNIST Digit Analysis

This project provides an exploratory data analysis (EDA) and machine learning classification models on the MNIST dataset, a collection of handwritten digits. We perform data visualization, dimensionality reduction, and then apply Logistic Regression, K-Nearest Neighbors (KNN), and Random Forest algorithms for digit classification.

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [How to Run](#how-to-run)
- [Model Results](#model-results)
- [License](#license)

## Overview

This repository provides an analysis of the MNIST dataset using Python and popular data science libraries like `scikit-learn`, `matplotlib`, and `seaborn`. The main focus is on:

- **Exploratory Data Analysis (EDA)**: Analyzing and visualizing the dataset to understand key characteristics.
- **Dimensionality Reduction**: Using techniques like PCA and t-SNE to reduce the data's dimensions for visualization.
- **Classification Models**: Training three models (Logistic Regression, KNN, Random Forest) to classify handwritten digits.

## Technologies Used

- **Python 3.x**
- **Libraries**:
  - `scikit-learn`
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scipy`
- **Google Colab** (optional if you're using Colab for running the notebooks)

## Dataset

The project uses the **MNIST dataset**, which is a collection of 70,000 28x28 grayscale images of handwritten digits from 0 to 9. The dataset is publicly available from [Yann LeCun's website](http://yann.lecun.com/exdb/mnist/). The dataset has been split into training and testing subsets (60,000 and 10,000 samples, respectively).

Data preprocessing steps:
- Reshaping the data for model training
- Normalizing the pixel values to improve model performance

## How to Run

### Option 1: Run on Google Colab
Click on the link below to open the notebook in Google Colab:
- [Open 1_MNIST_EDA.ipynb in Colab](https://colab.research.google.com/github/amiri-lina/mnist-digit-analysis/blob/main/MNIST_EDA.ipynb)

### Option 2: Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/amiri-lina/mnist-digit-analysis.git
   cd mnist-digit-analysis
