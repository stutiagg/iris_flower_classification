# iris_flower_classification
This project builds and evaluates machine learning models to classify Iris flower species (Setosa, Versicolor, Virginica) based on their measured features.
The dataset used is the classic Iris dataset from sklearn.

## Models Implemented
Four supervised ML models were trained on 75% of the data and tested on 25%.
1. Logistic Regression
2. kNN
3. Decision Tree
4. SVC

## Dataset
The sklearn Iris dataset contains 150 samples with 4 features:
* Sepal length (cm)
* Sepal width (cm)
* Petal length (cm)
* Petal width (cm)

Target classes:  
0 – Setosa  
1 – Versicolor  
2 – Virginica

## Workflow  
1. Load dataset using sklearn.datasets.load_iris  
2. Split into train/test using train_test_split  
3. Train Linear Regression, Decision Tree, and KNN  
4. Predict on test data  
5. Measure accuracy scores  
6. Compare model performance

## Results
| Model              | Accuracy | Precision | Recall | F1-Score |
|-------------------|----------|-----------|--------|----------|
| Linear Regression  | 0.97     | 0.96      | 0.98   | 0.97     |
| kNN                | 1.00     | 1.00      | 1.00   | 1.00     |
| Decision Tree      | 0.97     | 0.96      | 0.98   | 0.97     |
| SVC                | 0.97     | 0.96      | 0.98   | 0.97     |

## Libraries Used  
Python 3.x  
NumPy  
pandas  
scikit-learn  
matplotlib

## How to Run
### Option 1 — Google Colab (Recommended)  
Open the notebook:
```
iris_flower_classification.ipynb
```
Install dependencies inside a cell:
```
!pip install -r requirements.txt
```
Run the notebook cell by cell.

### Option 2 — Local Jupyter Notebook
Install dependencies:
```
pip install -r requirements.txt
```
Launch Jupyter:
```
jupyter notebook
```
Open the notebook and run all cells.
               



## File Structure
iris_flower_classification/  
├── iris_flower_classification.ipynb  
├── README.md  
└── requirements.txt

## Future Improvements  
Add SVM, RandomForest, Logistic Regression  
Hyperparameter tuning  
Add visualization dashboard (Streamlit)


