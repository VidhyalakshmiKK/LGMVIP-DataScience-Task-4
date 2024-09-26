#  Iris Dataset Classification using Decision Tree Classifier 
## 📚 Project Overview
This project demonstrates how to build a Decision Tree Classifier using the famous Iris dataset. The Iris dataset contains 150 samples of iris flowers, with 4 features for each flower (sepal length, sepal width, petal length, petal width) and a corresponding class label representing the species of the flower (Setosa, Versicolor, Virginica). The goal is to predict the species of the flower based on these features.
## 📊 Dataset
The Iris dataset contains:

- 150 samples
- 4 features: sepal length, sepal width, petal length, petal width
- 3 classes: Setosa, Versicolor, Virginica
- The dataset is directly available from scikit-learn's datasets module, but you can also download it in CSV format for standalone use.

## 📈 Key Steps
- **Data Loading:** Load the Iris dataset from scikit-learn.
- **Data Splitting:** Split the dataset into training and testing sets.
- **Model Building:** Train the Decision Tree Classifier on the training set.
- **Prediction:** Use the trained model to predict the species of flowers in the test set.
- **Evaluation:** Evaluate the performance of the model using accuracy score and a confusion matrix.
- **Pruning:** As decision tree is prone to overfit prune the model.
- **Visualization:** Visualize the Decision Tree and plot feature importance.

## 📊 Results
- **Accuracy**: Achieves around 96.7% accuracy on the Iris dataset.
- **Confusion Matrix:** Provides a matrix to evaluate misclassifications.
