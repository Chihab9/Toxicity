Toxicity Prediction using Machine Learning
This project explores the use of machine learning techniques to predict toxic chemicals and drugs based on molecular descriptors extracted from chemical structures. Specifically, we employ RDKit, a widely used cheminformatics library to compute a comprehensive set of molecular descriptors for a given dataset. To address the challenges associated with high-dimensional data, we apply Principal Component Analysis (PCA) for dimensionality reduction on 208 RDKit descriptors. To further enhance prediction accuracy, we employ ensemble learning techniques, such as Gradient Boosting and AdaBoost, which combine the predictions of multiple weak learners.

Table of Contents
Getting Started
Prerequisites
Installing Dependencies
Usage
Authors
License
Getting Started
To get started with this project, you can clone this repository by running the following command in your terminal:

bash
Copy code
git clone https://github.com/<username>/toxicity-prediction.git
Once you have cloned the repository, you can follow the instructions below to install the required dependencies and run the code.

Prerequisites
To run this project, you will need the following dependencies:

Python (version 3.6 or higher)
pandas (version 1.3.0 or higher)
numpy (version 1.20.3 or higher)
scikit-learn (version 0.24.2 or higher)
rdkit (version 2021.03.2 or higher)
Installing Dependencies
To install the required dependencies, you can use pip, the Python package installer. Run the following command in your terminal to install all the required dependencies:

bash
Copy code
pip install pandas numpy scikit-learn rdkit
Note: Make sure you have Python and pip installed on your system before running the above command.

Usage
To use this project, follow these steps:

Open the toxicity-prediction directory in your terminal.

Run the following command to preprocess the data and train the models:

bash
Copy code
python train.py
This will generate a CSV file named submission.csv containing the predictions on the test set.

(Optional) If you want to run the PCA analysis separately, run the following command:
bash
Copy code
python pca.py
This will generate a CSV file named pca_components.csv containing the principal components of the dataset.

Authors
Your Name
License
This project is licensed under the MIT License.
