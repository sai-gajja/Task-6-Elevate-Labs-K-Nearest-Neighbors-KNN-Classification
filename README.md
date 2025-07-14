🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)
This project implements a K-Nearest Neighbors (KNN) classifier on the classic Iris dataset using Scikit-learn, along with visualizations to demonstrate model performance and decision boundaries.

📌 Project Objective
To explore instance-based learning by applying KNN classification on a multi-class dataset. We experiment with different values of K, evaluate the model, and visualize the classification decision boundaries.

📂 Dataset Used
Iris Dataset

150 samples

3 species of Iris flower: Setosa, Versicolor, Virginica

4 features:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

🔗 Download Dataset

🔧 Tools & Libraries
Python 🐍

NumPy

Pandas

Scikit-learn

Matplotlib

🧪 Implementation Steps
1. Data Preprocessing
Load the dataset using pandas

Encode categorical target labels using LabelEncoder

Split data into training and testing sets

Feature normalization using StandardScaler (optional)

2. Model Training
Use KNeighborsClassifier from sklearn.neighbors

Fit the model on training data

Predict on test data

3. Evaluation
Accuracy Score

Classification Report

Confusion Matrix

4. K Value Tuning
Iterate k from 1 to 20

Plot accuracy vs k to find the optimal number of neighbors

5. Visualization
2D decision boundary using only SepalLength and SepalWidth

📊 Results
Achieved 100% accuracy with k=3 on test data (for full-featured KNN)

Visualized how decision boundaries change with different K values

Built an intuitive plot for decision regions using only 2 features
