Objective:
This Jupyter Notebook demonstrates the implementation of a K-Nearest Neighbors (KNN) classification algorithm using the Iris dataset. It includes exploratory data analysis, model training, prediction, and evaluation.
 Overview of Contents:
1. Importing Libraries
Essential Python libraries such as:

numpy, pandas: For data manipulation and handling

matplotlib.pyplot, seaborn: For visualization

sklearn modules: For model building, training, and evaluation

2. Dataset Loading
The built-in load_iris() function from sklearn.datasets is used to load the Iris dataset.

3. Data Exploration
The dataset is converted to a pandas DataFrame.

Basic data exploration including:

Head of dataset

Value counts of target classes

Visualizations using seaborn for pairplots and class distributions

4. Data Splitting
The dataset is split into training and testing sets using train_test_split() with an 80-20 split.

5. Model Building
A KNN classifier is instantiated (n_neighbors=3) and trained on the training set.

6. Model Evaluation
Predictions are made on the test set.

Evaluation metrics include:

Confusion Matrix

Classification Report (precision, recall, f1-score)

Accuracy score

7. Visualization
A confusion matrix heatmap is plotted using seaborn.

 Output:
Well-labeled graphs for class distribution and pairplot

Confusion matrix visualization

Performance metrics showing accuracy and classification effectiveness

