# Multiclass-Classification-product-category-prediction
Prediction of Product Category from Invoice using different ML models

This project is focused on building a high accuracy multiclass classification system to predict the Product Category of purchased goods & services, given the invoice information.

Prediction done using Logistic Regression Model.
Gives an accuracy score of 99.7% when tested using the training data.

Tools used: Jupyter Notebook, Anaconda, Python 3
Python libraries used: pandas, numpy, sklearn, nltk, matplotlib
Dataset/Input files Used: 'Train.csv' , 'Test.csv'
Output file: 'Predicted_Product_Category.csv'

- The source code is present in src/MulticlassClassification_ProductCategory.ipynb file which is a IPython Notebook file.
All the steps are documented in the markdown cells present in the Notebook file. The file can be opened using a Jupyter Notebook.

- The dataset is present in dataset/ folder

- Also a HTML version of the notebook file is provided named MulticlassClassification_ProductCategory.html which can be opened using any web browser.

## Additional Information:-

Anaconda is actually a distribution of software that comes with conda, Python, and over 150 scientific packages and their dependencies. It comes with jupyter notebook too. Hence installing anaconda will automatically install jupyter notebook.

### How to install Anaconda?

Download and install Anaconda:-
For windows: https://repo.anaconda.com/archive/Anaconda3-5.2.0-Windows-x86_64.exe

### Create a virtual environment:-
conda create -n predict-product-category python=3.6

### Activate virtual environment:-
conda activate predict-product-category # for windows

### Install all the dependencies:-
pip install <package_name>

### To launch Jupyter Notebook:-
Enter 'jupyter notebook' on the terminal
