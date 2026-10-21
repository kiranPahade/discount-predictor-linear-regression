# Discount Predictor — Simple Linear Regression

An educational Google Colab project for learning Python, data creation, visualization, and simple linear regression.

## Open in Google Colab
1. Download `Discount_Predictor_Simple_Linear_Regression.ipynb`.
2. Open https://colab.research.google.com/
3. Choose **File → Upload notebook** and select the `.ipynb` file.
4. Run cells from top to bottom.

## Dataset
The notebook generates its own synthetic dataset with `Original_Price` and `Discount_Percent`. It does not download third-party data. The synthetic relationship exists only for teaching; it is not a reliable model for actual retail pricing.

## Contents
- Dataset creation with NumPy and pandas
- Dataset inspection and visualization
- Feature/target selection
- Train/test split
- Simple Linear Regression training
- Regression line visualization
- R², MAE, and RMSE evaluation
- Prediction function and optional interactive widget
- CSV export
- Python concepts checklist and practice questions

## Requirements
Python 3.10+ recommended; `numpy`, `pandas`, `matplotlib`, `scikit-learn`, and optional `ipywidgets`. Google Colab usually includes the main packages.

## Publish to GitHub
1. Sign in to GitHub and create a **public** or **private** repository named `discount-predictor-linear-regression`.
2. Choose **Add file → Upload files**.
3. Upload this notebook and `README.md`.
4. Add a commit message such as `Add guided discount predictor notebook`.
5. Click **Commit changes**.

To use Git from a local terminal instead:
```bash
git init
git add .
git commit -m "Add guided discount predictor project"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/discount-predictor-linear-regression.git
git push -u origin main
```
Replace `YOUR-USERNAME` with your GitHub username. GitHub authentication may prompt you to sign in; never put a password or personal access token into source code.

## Python concepts included
Variables, imports, functions, arguments, arrays, dictionaries, DataFrames, indexing, attributes, methods, arithmetic, comparisons, conditionals, exceptions, f-strings, plotting, model fitting, prediction, metrics, and CSV file output.
