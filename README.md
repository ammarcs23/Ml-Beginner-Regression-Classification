# ML Beginner: Regression and Classification

Two very simple, beginner-friendly Machine Learning notebooks. Every step has a short explanation in plain English, so a complete beginner can follow along.

## Notebooks

| Notebook | Problem type | Algorithm | Dataset |
|---|---|---|---|
| `Diabetes_Regression_Beginner.ipynb` | Regression (predict a number) | Linear Regression | Diabetes (442 patients, 10 features) |
| `Wine_Classification_Beginner.ipynb` | Classification (predict a category) | Decision Tree | Wine (178 wines, 13 features) |

Both datasets come built-in with scikit-learn, so **no download and no internet are needed**.

## Steps followed in each notebook

1. Import tools (libraries)
2. Load the data
3. Look at the data (EDA)
4. Split the data into training and test parts
5. Train the model
6. Check the predictions
7. Measure the quality (metrics)

## Metrics used

| Notebook | Metrics |
|---|---|
| Diabetes (Regression) | MAE, MSE, RMSE, R2 |
| Wine (Classification) | Accuracy, Precision, Recall, F1-score, Confusion Matrix |

Each notebook also compares the model with a "lazy guess" baseline, to show that the model is really useful.

## Results

| Notebook | Result |
|---|---|
| Diabetes | R2 about 0.45, MAE about 42.8 (normal for this small and noisy dataset) |
| Wine | Accuracy about 94.4% (34 of 36 test wines correct) |

## How to run

1. Install Python 3.9 or newer.
2. Install the libraries:
   ```
   pip install pandas numpy matplotlib scikit-learn jupyter
   ```
3. Open the project folder and start Jupyter:
   ```
   jupyter notebook
   ```
   (You can also open the notebooks in VS Code.)
4. Open a notebook and click **Run All**.

## Libraries used

| Library | Purpose |
|---|---|
| pandas | Tables of data |
| numpy | Fast maths on numbers |
| matplotlib | Charts |
| scikit-learn | Datasets, models and metrics |

## Project structure

```
ml-beginner-regression-classification/
├── Diabetes_Regression_Beginner.ipynb
├── Wine_Classification_Beginner.ipynb
└── README.md
```

## Ideas for the future

- Try other algorithms (Random Forest, SVM)
- Use cross-validation
- Tune the model settings (for example `max_depth` of the tree)
