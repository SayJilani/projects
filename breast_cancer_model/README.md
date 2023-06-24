# Breast Cancer Classification

This project aims to build a machine learning model to classify breast cancer tumors as malignant or benign using the breast cancer dataset. The model is implemented using TensorFlow and Keras, and various preprocessing techniques are applied to prepare the data for training and testing.

## Dataset

The dataset used in this project is the Breast Cancer dataset obtained from Kaggle. It contains information about various features of breast tumors, such as mean radius, mean texture, mean perimeter, mean area, and mean smoothness. The target variable is the diagnosis, which indicates whether a tumor is malignant (1) or benign (0).
https://www.kaggle.com/datasets/merishnasuwal/breast-cancer-prediction-dataset

## Project Structure

The project follows the following steps:

1. Data loading: The breast cancer dataset is loaded from the provided CSV file.

2. Data preprocessing: The data is shuffled, and then split into training and test sets. The features and labels are separated for both sets. Feature normalization is performed to ensure all features are on the same scale.

3. Exploratory Data Analysis: A pairwise plot is created to visualize the relationships between different features in the training set.

4. Feature Selection: Features that are highly correlated with each other are removed from the test set.

5. Model Building: A logistic regression model is built using TensorFlow and Keras. The model is trained on the training set using the Adam optimizer and a chosen learning rate. The training progress is monitored using the loss and accuracy metrics.

6. Model Evaluation: The model's performance is evaluated using the validation set. Loss and accuracy metrics are displayed, and a loss plot is generated to visualize the training progress. The final model is then evaluated on the test set to obtain the test accuracy.

## Usage

To run the project locally, follow these steps:

1. Clone the repository:

2. Install the required dependencies:

numpy
matplotlib
pandas
seaborn
tensorflow
scikit-learn




