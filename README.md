# Car Price Prediction Using Random Forest Regression

## Project Overview

This project aims to predict the selling price of cars using the Random Forest Regression Machine Learning algorithm. The model analyzes various car-related features such as fuel type, kilometers driven, transmission type, and ownership details to estimate the car price accurately.

Random Forest Regression was chosen because it provides high accuracy, reduces overfitting, and performs well on structured datasets.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

---

## Dataset Features

The dataset contains the following features:

* Car Name
* Year
* Present Price
* Kms Driven
* Fuel Type
* Seller Type
* Transmission
* Owner

### Target Variable

* Selling Price

---

## Machine Learning Algorithm

### Random Forest Regression

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

Advantages:

* High prediction accuracy
* Handles nonlinear data effectively
* Reduces overfitting
* Works well with large datasets

---

## Project Workflow

### 1. Data Collection

Imported the car dataset and explored its structure.

### 2. Data Preprocessing

* Checked null values
* Removed unnecessary columns
* Encoded categorical variables
* Split dataset into training and testing data

### 3. Exploratory Data Analysis (EDA)

Performed data visualization to understand:

* Correlation between features
* Price distribution
* Impact of car features on selling price

### 4. Model Building

Implemented the Random Forest Regressor using Scikit-learn.

```python id="9j74wv"
from sklearn.ensemble import RandomForestRegressor

model = RandomForestRegressor()
model.fit(x_train, y_train)
```

---

## Model Evaluation

The model performance was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

Example:

* MAE: Low value indicates better prediction accuracy
* R² Score: Higher value indicates better model performance

---

## Results

The Random Forest Regression model achieved good prediction accuracy and performed better compared to traditional linear models.

The model successfully predicts car selling prices based on historical data and car specifications.

---

## Future Improvements

* Hyperparameter tuning using RandomizedSearchCV
* Deploy model using Flask or Streamlit
* Add real-time prediction interface
* Use larger datasets for improved accuracy

---

## How to Run the Project

### Clone the Repository

```bash id="4t2xan"
git clone <repository-link>
```

### Install Dependencies

```bash id="qg4i8j"
pip install -r requirements.txt
```

### Run the Notebook

```bash id="91i8rq"
jupyter notebook
```

---

## Author

Venky Karanam
Aspiring Data Scientist | Machine Learning Enthusiast
