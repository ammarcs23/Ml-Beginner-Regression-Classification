# ML for Beginners: Guess the Number and Guess the Type

Two very, very simple Machine Learning notebooks. Everything is explained in plain English, and **every code cell has only one line of code**, so a complete beginner can follow along step by step.

## Notebooks

| Notebook | Problem type | Algorithm | Dataset |
|---|---|---|---|
| `Diabetes_Regression_Nursery.ipynb` | Regression (guess a number) | Linear Regression | Diabetes (442 patients, 10 facts each) |
| `Wine_Classification_Nursery.ipynb` | Classification (guess a type) | Decision Tree | Wine (178 wines, 13 facts each) |

Both datasets come built-in with scikit-learn, so **no download and no internet are needed**.

## What makes these notebooks simple

- One cell = one line of code
- A short markdown note above every code cell
- Easy real-life examples (a taxi for Linear Regression, the "20 Questions" game for Decision Tree)
- A "lazy guess" comparison to show that the model really learned something

## Steps in each notebook

1. Bring the tools (import libraries)
2. Get the data
3. Look at the data
4. Split the data (study part and exam part)
5. Teach the computer (train the model)
6. Let the computer guess (make predictions)
7. Check the guesses (metrics)

## Scores (metrics) used

| Notebook | Scores |
|---|---|
| Diabetes (Regression) | MAE, MSE, RMSE, R2 |
| Wine (Classification) | Confusion Matrix, Accuracy, Precision, Recall, F1-score |

## Results

| Notebook | Result |
|---|---|
| Diabetes | R2 about 0.45, MAE about 42.8 (normal for this small and noisy dataset) |
| Wine | Accuracy about 94.4% (34 of 36 test wines correct) |

## How to run

1. Install Python 3.9 or newer.
2. Install the libraries:
   ```
   pip install pandas matplotlib scikit-learn jupyter
   ```
3. Start Jupyter in the project folder:
   ```
   jupyter notebook
   ```
   (You can also open the notebooks in VS Code.)
4. Open a notebook and press **Shift + Enter** on each cell, one by one. You can also click **Run All**.

## Libraries used

| Library | Purpose |
|---|---|
| pandas | Tables of data |
| matplotlib | Pictures and charts (used in the Wine notebook to resize the tree picture) |
| scikit-learn | Datasets, models and scores |

## Project structure

```
ml-beginner-regression-classification/
├── Diabetes_Regression_Nursery.ipynb
├── Wine_Classification_Nursery.ipynb
└── README.md
```

## Ideas for the future

- Try other algorithms (Random Forest, SVM)
- Change `max_depth` of the tree and see what happens
- Try cross-validation