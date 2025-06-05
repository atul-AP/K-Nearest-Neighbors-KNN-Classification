
🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)
📘 Project Summary
This project applies the K-Nearest Neighbors (KNN) algorithm to classify iris flower species (Setosa, Versicolor, Virginica) based on floral features. The goal is to train a robust classifier, tune it using different k values, and visualize decision boundaries to interpret model behavior.

🎯 Problem Statement
The objective is to predict the species of iris flowers from four numeric features: sepal length, sepal width, petal length, and petal width. Using KNN, we aim to identify how different values of k affect model accuracy and how well the algorithm separates classes.

📂 Dataset Overview
The dataset contains 150 samples with the following features:

Feature	Description
Sepal Length	Length of the sepal (cm)
Sepal Width	Width of the sepal (cm)
Petal Length	Length of the petal (cm)
Petal Width	Width of the petal (cm)

Target Classes:

0 = Setosa

1 = Versicolor

2 = Virginica

🔧 Methods Used
🧩 Step 1: Data Loading & Exploration
Loaded the dataset using sklearn.datasets.load_iris()

Converted to a pandas DataFrame for easier analysis

🔄 Step 2: Feature Normalization
Applied StandardScaler to normalize features for better KNN performance

✂️ Step 3: Train/Test Split
Used train_test_split to split the data (80% train, 20% test)

🧠 Step 4: Model Training
Trained KNeighborsClassifier with k values: 1, 3, 5, 7, 9

Evaluated using:

Accuracy

Confusion Matrix

Classification Report (precision, recall, f1-score)

📈 Step 5: Accuracy vs. K Plot
Plotted accuracy against different values of k to choose the best one

🌐 Step 6: Decision Boundary Visualization
Used only 2 features (petal length & width) to plot decision boundaries in 2D

Visualized how KNN separates different classes

📊 Performance Summary
K Value	Accuracy (%)
1	~97%
3	~97%
5	~96%
7	~96%
9	~95%

Setosa is perfectly separable.

Optimal accuracy achieved at k = 3 and k = 1.

📈 Visualizations
✔ Accuracy vs K Plot
✔ Confusion Matrix for each K
✔ Decision Boundary using Petal Features

🛠 Tools & Technologies
Tool/Library	Use
Python	Programming
pandas, numpy	Data manipulation
scikit-learn	Model building & evaluation
matplotlib, seaborn	Visualization

✅ Summary of Tasks Achieved
✅ Loaded and explored the Iris dataset

✅ Normalized features using StandardScaler

✅ Trained KNN classifiers for multiple k values

✅ Evaluated models using multiple metrics

✅ Visualized decision boundaries using petal features

Let me know if you'd like this in a PDF or Markdown file, or if you'd like to include charts and figures directly. 








