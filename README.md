# 📊 Iris Dataset Visualization

This Jupyter Notebook provides a simple and intuitive visualization of the **Iris dataset** using tools from the Python data science ecosystem.

## 📁 File: `Untitled4.ipynb`

## 🧰 Dependencies

Make sure you have the following Python packages installed:

```bash
pip install pandas seaborn matplotlib scikit-learn
```

## 📌 Features

1. **Loading the Iris Dataset**  
   Using `sklearn.datasets.load_iris`, the dataset is loaded into a Pandas DataFrame for easier manipulation.

2. **Pair Plot Visualization**  
   Uses `seaborn.pairplot` to visualize pairwise relationships between all features, colored by species (target).

3. **3D PCA Visualization**  
   Applies Principal Component Analysis (PCA) to reduce the dimensionality of the data to 3D and visualizes it using a 3D scatter plot from `matplotlib`.

   - Axes represent the first three principal components.
   - Points are colored based on the target class (species).
   - Includes a legend indicating the class labels.

## 📸 Sample Outputs

- **Pair Plot:**  
  Helps understand correlation and class separability.

- **3D PCA Plot:**  
  Aids in visualizing the dataset in reduced dimensional space while preserving variance.

## ▶️ How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/iris-visualization.git
   cd iris-visualization
   ```

2. Open the notebook:
   ```bash
   jupyter notebook Untitled4.ipynb
   ```

3. Run all cells to see the visualizations.

## 📚 Dataset Info

- 150 samples
- 4 features: sepal length, sepal width, petal length, petal width
- 3 classes: `setosa`, `versicolor`, `virginica`
