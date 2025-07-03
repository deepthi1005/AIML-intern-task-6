# AIML-intern-task-6
# K-Nearest Neighbors (KNN) Classification on Iris Dataset

This project demonstrates the application of the **K-Nearest Neighbors (KNN)** algorithm for multi-class classification using the classic **Iris flower dataset**.

##  Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)
- **Attributes**: Sepal Length, Sepal Width, Petal Length, Petal Width
- **Target**: Species (`Setosa`, `Versicolor`, `Virginica`)

##  Workflow Steps

1. **Load and preprocess the dataset**
   - Drop unnecessary columns
   - Encode categorical target labels
   - Normalize features using `StandardScaler`

2. **Split into train and test sets**

3. **Train KNN models**
   - Try different values of **K** (1 to 10)
   - Select the value of K with the highest accuracy

4. **Evaluate the model**
   - Accuracy Score
   - Confusion Matrix

5. **Visualize**
   - Plot Accuracy vs K
   - Visualize Decision Boundaries (using first two features)

## Results

- Best K is selected based on test set accuracy
- Confusion matrix shows performance on multi-class classification
- Decision boundaries provide a visual interpretation of model behavior

## Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn (`KNeighborsClassifier`)
- Matplotlib, Seaborn

## Example Outputs

- Accuracy vs K Plot
- Confusion Matrix Heatmap
- Decision Boundary Visualization

## To Run This Project

# Clone the repository
git clone https://github.com/yourusername/knn-iris-classification.git
cd knn-iris-classification

# Install dependencies (optional if using Jupyter)
pip install -r requirements.txt

# Run the notebook or Python script
