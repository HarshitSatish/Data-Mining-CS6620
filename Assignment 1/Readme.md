CS 6220 — Homework 1: Data Mining Pipeline Setup

A scikit-learn pipeline that classifies Iris flowers (setosa / versicolor / virginica) from their sepal and petal measurements.

Environment
Language: Python 3
Notebook: Jupyter Notebook / JupyterLab
Core libraries: pandas, matplotlib, seaborn, scikit-learn
Dataset: Iris Flower Data Set (UCI Machine Learning Repository) — 150 samples, 4 features (sepal length/width, petal length/width), 3 classes.

The raw data file is at iris/iris.data relative to the notebook.

Project Structure
.
├── Assignment1.ipynb     # main notebook: data loading, EDA, pipeline, model, evaluation

├── iris/
│   └── iris.data          # Iris dataset

├── requirements.txt

└── README.md

Setup
bash
# clone the repo
git clone <your-repo-url>
cd <your-repo-folder>

# create and activate a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate

# install dependencies
pip install -r requirements.txt

# launch Jupyter
jupyter lab

Then open Assignment1.ipynb and run all cells.
