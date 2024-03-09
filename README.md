# Parkinson's Disease Detection

This repository contains a Python implementation for Parkinson's Disease detection using Support Vector Machine (SVM) and Random Forest (RF) classifiers. The project aims to build and evaluate machine learning models that can accurately classify individuals as either having Parkinson's Disease or not, based on various features extracted from voice recordings.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

Parkinson's Disease is a progressive neurological disorder that affects movement and can lead to various motor and non-motor symptoms. Early detection of the disease is crucial for proper treatment and management. This project explores the use of machine learning techniques, specifically SVM and Random Forest classifiers, to detect Parkinson's Disease based on voice recordings.

## Dataset

The dataset used in this project is obtained from Kaggle. It consists of voice recordings from individuals, both with and without Parkinson's Disease. The dataset includes various features extracted from these voice recordings, such as pitch, amplitude, and frequency-related features.

## Installation

To run this project locally, you'll need to have Python 3.x and the following libraries installed:

- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

You can install these libraries using pip:

```
pip install pandas numpy scikit-learn seaborn matplotlib
```

Additionally, you'll need access to Google Colab or a Jupyter Notebook environment to execute the code.

## Usage

1. Clone the repository:
  ```
git clone https://www.github.com/sushantkothari/Parkinson-s-Disease-Prediction-Using-Random-Forest/
  ```
2. Navigate to the project directory:
   ```
   cd parkinsons-disease-detection
   ```
3. Upload the `<Parkinsson disease dataset file>.csv` dataset to your Google Colab or Jupyter Notebook environment.

4. Run the code cells in the provided notebook file.

The code will load the dataset, preprocess the data, train the SVM and Random Forest models, evaluate their performance using various metrics (accuracy, precision, F1-score, ROC AUC), and generate confusion matrices and visualizations for both models.

## Code Structure

The repository contains the following files:

- `Parkinson's_Random_Forest_Classifier.ipynb`: The Jupyter Notebook file containing the Python code for data loading, model training, evaluation, and visualization.
- `README.md`: This file, providing an overview of the project and instructions for usage.

## Results

The performance of the SVM and Random Forest models is evaluated using various metrics, including accuracy, precision, F1-score, and ROC AUC (Area Under the Receiver Operating Characteristic Curve). The results are displayed in the notebook and visualized using confusion matrices and plots.

The code also generates visualizations to compare the performance of the two models side by side, making it easier to analyze and interpret the results.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
