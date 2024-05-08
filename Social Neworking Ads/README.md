# Social Network Ads Prediction

This Python script utilizes Support Vector Machine (SVM) algorithms to predict whether a user would purchase a product based on their age and estimated salary. It demonstrates the use of different SVM kernels such as linear, radial basis function (RBF), and polynomial kernels.

## Prerequisites

Before running the script, ensure you have the following Python libraries installed:

- numpy
- pandas
- matplotlib
- seaborn
- plotly
- scikit-learn

  
Usage
Clone the repository or download the script.
Make sure you have the dataset Social_Network_Ads.csv in the /dataset directory.
Run the script social_network_ads_prediction.py.


Description

The script performs the following steps:

1. Loads the dataset containing information about users, including age, estimated salary, and whether they purchased a product.
2. Splits the dataset into training and testing sets.
3. Performs feature scaling to standardize the range of independent variables.
4. Trains SVM classifiers with different kernels: linear, RBF, and polynomial.
5. Predicts the labels for the test set and calculates the accuracy score for each classifier.
6. Visualizes the training and testing data points using scatter plots.
7. Visualizes the decision boundaries in 2D and 3D space.

File Structure
Copy code
.
├── dataset
│   └── Social_Network_Ads.csv
├── social_network_ads_prediction.py
└── README.md
