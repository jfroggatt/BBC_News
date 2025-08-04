#%% md
# BBC News Classification with NMF Project

University of Colorado, Boulder - CSCA 5632: Unsupervised Algorithms in Machine Learning

## Project Overview

This project is about categorizing BBC News articles using matrix factorization to predict the category. The project is using the [BBC News Classification](https://www.kaggle.com/competitions/learn-ai-bbc) competition on [Kaggle](https://www.kaggle.com/)  for the source data and the final accuracy score results obtained by submission of a prediction against the competition's Test data set. The project's [competition notebook](https://www.kaggle.com/code/jamesfroggatt/bbc-news-classification-with-nmf) is also available on Kaggle, for review of the submission results.

The project will work to follow a typical machine learning project, with an exception that the specific unsupervised model, Non-negative Matrix Factorization (NMF), is already determined. After evaluations have been perfomed for the NMF model, the project will then select and compare the performance for against a supervised model. The guidelines for this project are as follows:

### Step 1. Exploratory Data Analysis

In this section we will inspect, visualize, and clean the data. As part of the process, we will also select a word embedding method and review associated visualizations and statistics. Following a review of the EDA, we will then generate a plan for the analysis, including data cleaning, preprocessing, and feature engineering steps.

### Step 2. Building and training the unsupervised model

In this section we will build a model using the Non-negative Matrix Factorization method and predict train and test data labels. The model's performance across various hyperparameter configurations will be evaluated to determine the optimal configuration. The performance will be inpected through results of the accuracy score and confusion matrix. Finally, we may look at additional methods to improve the final model performance.

### Step 3. Compare with supervised learning

In this section we will evaluate and select a supervised model to generate the predicted category and compare the test results with the NMF model. This comparison will also include an evaluation of how each model performs based on the size of the training data.

### Step 4. Project Report and Conclusion

Finally, we will evaluate the project results.

## Installation

Follow these steps to setup the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/jfroggatt/BBC_News.git
cd BBC_News
```
### 2. Create a Virtual Environment (Optional but Recommended)

#### 2a. using venv:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate.ps1 (or activate.bat)
```
#### 2b. using uv:
```bash
uv venv
source .venv/bin/activate  # On Windows:  .venv\Scripts\activate.ps1 (or activate.bat)
```
### 3. Install Dependencies
Install all required packages from `requirements.txt`:
#### 3a. using venv:
```bash
pip install -r requirements.txt
```
#### 3b. using uv
```bash
uv sync
```
### 4. Launch Jupyter Notebook
```bash
Jupyter Notebook
```
Then open the `bbc_news.ipynb` file from the Jupyter interface.

## Requirements
-  Python 3.12
-  Jupyter Notebook
-  See `requirements.txt` or `pyproject.toml` for the full list

## Usage
-  Run each cell in sequence
-  Modify parameters or data to explore custom scenarios
-  Refer to comments for explanation of each step
