# Day-3
# 🚀 Linear Regression on Titanic Dataset

## 📌 Objective

This project demonstrates the implementation and understanding of **Simple and Multiple Linear Regression** using the Titanic dataset. The goal is to build a regression model that predicts the likelihood of survival based on various passenger features.

---

## 🛠️ Tools & Libraries Used

- **Python 3**
- **Pandas** – for data handling
- **Scikit-learn** – for building and evaluating the linear regression model
- **Matplotlib** – for plotting the regression line

---

## 📂 Dataset

- Dataset used: `titanic_cleaned.csv`
- This is a preprocessed and cleaned version of the Titanic dataset.
- The target column is: `Survived` (0 = did not survive, 1 = survived)

---

## 📈 Project Workflow

### 1. **Data Import & Preprocessing**
- The dataset is loaded using `pandas.read_csv`.
- Unnecessary columns such as `Passenger`, `Name`, and `Ticket` were removed as they are non-numeric or identifiers.
- Target column (`Survived`) is separated from features.

### 2. **Train-Test Split**
- The dataset is split into training and testing sets using an 80/20 split via `train_test_split()`.

### 3. **Model Training**
- A **Linear Regression** model is trained using `sklearn.linear_model.LinearRegression`.

### 4. **Model Evaluation**
- Evaluation metrics used:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score (Coefficient of Determination)

### 5. **Plotting Regression Line**
- A scatter plot is used to visualize the relationship between one selected feature (e.g., `Age`) and the predicted outcome.

### 6. **Coefficient Interpretation**
- Model coefficients are displayed to understand how each feature impacts survival.

---

## 📊 Output & Results

- Evaluated model performance using MAE, MSE, and R².
- Displayed regression coefficients for each feature.
- Plotted a regression line over actual data points for visual interpretation.

---

## 📌 Conclusion

This project showcases the fundamental implementation of linear regression using the Titanic dataset. Although linear regression is not typically used for classification tasks (like survival prediction), it helps in understanding relationships and contributions of different features to the output.

---

M.Sathvika
29-05-2025
