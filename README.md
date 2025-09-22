OIBSIP_Data-Science_taskno.1-Neel-Kumavat 
Iris Flower Classification

Iris Species Classification – Machine Learning Project

Objective

The goal of this project is to train a machine learning model using the Iris dataset to classify iris flowers into three species:

Iris-setosa
Iris-versicolor
Iris-virginica

The model learns from flower measurements like sepal and petal dimensions and predicts the species accurately.

Dataset

The dataset used is `Iris.csv`, which contains the following columns:

Id (optional)
SepalLengthCm
SepalWidthCm
PetalLengthCm
PetalWidthCm
Species (target variable)

Tools and Technologies Used

Python
Pandas – for data manipulation
NumPy – for numerical operations
Matplotlib & Seaborn – for data visualization
scikit-learn (sklearn) – for model building and evaluation
Google Colab – execution environment

Steps Performed

1. Data Loading

 The dataset is loaded using `pandas.read_csv()`.

2. Exploratory Data Analysis (EDA)

Checked structure, data types, and missing values.
Explored data distribution and statistical summary.

3. Preprocessing

Removed the `Id` column (non-informative)
Encoded the `Species` column using `LabelEncoder` to convert categorical labels into numeric format.

4. Feature Selection

Chose 4 features: sepal and petal length and width.

5. Train-Test Split

Split the data (80% train, 20% test) using `train_test_split()`.

6. Model Training

Used Logistic Regression to train the model.

7. Model Evaluation

Evaluated using:

  Accuracy Score
  Confusion Matrix
  Classification Report
  Visualized confusion matrix using heatmap.

8. Prediction

 Predicted on test set.
 Compared **actual species vs predicted species** in a DataFrame.

Outcome

The Logistic Regression model achieved high accuracy in classifying iris species.
Model learned the relationship between flower measurements and species.
Visualizations showed strong class separation and helped validate model performance.

File Structure


Iris.csv                 # Dataset file
iris_classification.ipynb  # Main notebook (Colab compatible)
README.md                # Project overview





