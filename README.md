# Iris-K-Nearest-Neighbors

## Description
This project demonstrates the **K-Nearest Neighbors (KNN)** algorithm using the **Iris dataset**.  
The goal is to classify Iris flowers into three species: **setosa, versicolor, and virginica** based on four features:

- Sepal length  
- Sepal width  
- Petal length  
- Petal width  

The project includes:

- Loading and exploring the Iris dataset  
- Visualizing data with scatter plots  
- Splitting data into training and testing sets  
- Training a **KNN classifier**  
- Evaluating model performance using:  
  - **Accuracy**  
  - **Confusion Matrix** (with heatmap visualization)  
  - **Classification Report** (Precision, Recall, F1-Score)

---

## Project Workflow

1. **Data Loading & Exploration**  
   - Load the Iris dataset using `scikit-learn.datasets`.  
   - Explore features and target labels to understand data distribution.  

2. **Data Visualization**  
   - Use scatter plots to visualize relationships between features for different classes.  
   - Understand how separable the classes are in feature space.  

3. **Data Preparation**  
   - Split the dataset into **training** and **testing sets** for model evaluation.  

4. **Model Building**  
   - Create a **KNN classifier** with `k=7` neighbors.  
   - Train the model on the training data (`X_train`, `y_train`).  

5. **Prediction & Evaluation**  
   - Predict class labels for the test data.  
   - Evaluate using:  
     - **Accuracy** – overall correctness of predictions  
     - **Confusion Matrix** – detailed view of correct and incorrect predictions  
     - **Heatmap** – visual interpretation of the confusion matrix  
     - **Classification Report** – precision, recall, and F1-score for each class  

---

## Libraries Used
- `pandas` – for data manipulation  
- `matplotlib` – for scatter plot visualizations  
- `seaborn` – for heatmap visualizations  
- `scikit-learn` – for dataset, KNN classifier, and evaluation metrics  

---

## Dataset
- The **Iris dataset** is a classical machine learning dataset with:  
  - **150 samples**  
  - **4 features**: sepal length, sepal width, petal length, petal width  
  - **3 classes**: setosa, versicolor, virginica  
- Each class has **50 samples**, making it a balanced dataset suitable for classification tasks.  

---

## Insights
- KNN is a **lazy learning algorithm**, storing training data and predicting based on nearest neighbors.  
- The confusion matrix and classification report provide insights into **which classes are predicted well** and **where the model makes mistakes**.  
- Visualizations help in understanding **feature separability** and **class distribution**.
