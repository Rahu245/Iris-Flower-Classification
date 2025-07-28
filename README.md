# Iris Flower Classification
This project is a Machine Learning classification task using the famous **Iris Flower Dataset**. It involves data preprocessing, exploratory data analysis (EDA), model building, evaluation, and user input prediction.

# Project Structure

- `Iris_Flower_Classification.ipynb` — Jupyter Notebook with complete code: loading data, visualization, training ML models, and evaluation.
- `iris.csv` or `iris_dataset.csv` — Dataset files used for model training and testing.

# Dataset Description
The Iris dataset is one of the most well-known datasets in the machine learning community. It includes 150 samples of iris flowers from three species: *setosa*, *versicolor*, and *virginica*. Each sample has the following features:

- **Sepal Length (cm)**
- **Sepal Width (cm)**
- **Petal Length (cm)**
- **Petal Width (cm)**
- **Target (Species)** — Class label (`setosa`, `versicolor`, or `virginica`)

# Technologies & Libraries Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn (SVM, train_test_split, accuracy_score, confusion_matrix)

# ML Models Applied

- **Support Vector Machine (SVM)**
  - Used for classification
  - Evaluated using accuracy, confusion matrix, and classification report

# Features
- Dataset loading and cleaning
- Visualizations (pairplots, heatmaps)
- Model training and prediction
- Real-time prediction using user input
- Evaluation using:
  - Accuracy
  - Confusion matrix
  - Classification report

# How to Run

1. Clone or download this repository.
2. Open the notebook file: `Iris_Flower_Classification.ipynb` in **Jupyter Notebook** or **Google Colab**.
3. Upload the required dataset file (`iris.csv` or `iris_dataset.csv`) when prompted, or mount Google Drive if stored there.
4. Run all cells to:
   - Load and explore the data
   - Train the model
   - Make predictions on test data and new inputs

## 🔮 Prediction Example

At the end of the notebook, you can input:
Enter sepal length: 5.1
Enter sepal width: 3.5
Enter petal length: 1.4
Enter petal width: 0.2
and the model will output:
The species of the flower is: setosa

Developed by: Y R Rahul
Feel free to contribute, improve, or raise issues!
