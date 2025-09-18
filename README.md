# ML-Multi-class-Classifier
This project studies the dataset of 1800 data matrices (small pictures representing a digit) with 64 features.

**Objective:** To solve the multi-class classification problem, which consist of determining what category the digit belongs to. There are 10 categories, corresponding to every digit (from 0 to 9).

## Overview
The dataset is imported from the sklearn library, hence, the exploratory data analysis (EDA) is ommited. Then, the performance of 6 different ML algorithms are compared:

• Algorithm 1: **KNeighborsClassifier**.

• Algorithm 2: **SVC**.

• Algorithm 3: **GaussianNB**.

• Algorithm 4: **XGBClassifier (XGBoost library)**.

• Algorithm 5: **LGBMClassifier (LightGBM library)**.

• Algorithm 6: **CatBoostClassifier (CatBoost library)**.

Finally, the best algorithim is selected for this particular dataset.

🛠️**Libraries used**: Pandas, Matplotlib, Seaborn, NumPy, SciPy, Scikit-learn, XGBoost, LightGBM, CatBoost.

The Jupyter Notebook is in notebooks/multi_classifier.ipynb.

## 🚀 Installation
1. Clone this repository:
```
git clone https://github.com/arteaga7/ML-Multi-class-Classifier.git
```
2. Set virtual environment and install dependencies:
```
python3 -m venv env && source env/bin/activate && pip3 install -r requirements.txt
```
3. Run Jupyter Notebook in notebooks/multi_classifier.ipynb.