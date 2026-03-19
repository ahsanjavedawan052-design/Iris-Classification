# Iris-Classification
Iris Flower Classification: A Machine Learning pipeline using K-Nearest Neighbors (KNN) to predict species based on morphological features.
🌸 Iris Flower Classification with KNN
📌 Project Overview
This project implements a K-Nearest Neighbors (KNN) machine learning model to classify iris flowers into three species: Setosa, Versicolor, and Virginica. Using morphological measurements, the model identifies patterns that distinguish these species with high precision.

The Dataset
The Iris Dataset contains 150 instances with 4 features:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

🚀 Key Features
Exploratory Data Analysis (EDA): Visualized feature distributions using Seaborn pair plots.

Data Preprocessing: Handled feature scaling and split data into training/test sets (80/20).

Machine Learning: Implemented a KNeighborsClassifier from Scikit-Learn.

Evaluation: Achieved 100% accuracy on the test set, supported by a detailed Classification Report.

📊 Visualizing the Data
The pair plot below illustrates how the Setosa species is linearly separable from Versicolor and Virginica, making it an ideal candidate for distance-based algorithms like KNN.
