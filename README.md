# Random Forest Classification Model on Social Network Ads Dataset

This project demonstrates the implementation of a **Random Forest classification model** to predict whether a user purchases a product based on their Age and Estimated Salary. The dataset used is the **Social_Network_Ads.csv**, a commonly used example for binary classification tasks. **This project can be easily adapted to work with other datasets** containing different or additional independent variables.

---

## 📂 Dataset
The dataset contains the following features:
- `Age`
- `EstimatedSalary`
- `Purchased` (Target: 1 if purchased, 0 otherwise)

---

## ✅ Steps to Run in Google Colab

1. **Upload the Dataset**
   - Upload the `Social_Network_Ads.csv` file to your Colab session.

2. **Import Libraries**
   - Load necessary libraries: NumPy, Pandas, Matplotlib.

3. **Load the Dataset**
   - Use Pandas to load the CSV file.

4. **Preprocess the Data**
   - Split the dataset into features `X` and target variable `y`.
   - Use `train_test_split` to create training and test datasets.
   - Apply `StandardScaler` to normalize the features.

5. **Train the Model**
   - Train a Random Forest model using `RandomForestClassifier` from `sklearn.ensemble`.

6. **Make Predictions**
   - Predict results for a single input and the test set.

7. **Evaluate the Model**
   - Print the confusion matrix.
   - Print the accuracy score.

8. **Visualize the Results**
   ### ✅ Decision Boundary Visualizations

**Training Set:**

![Training Set Result](https://github.com/user-attachments/assets/63dc235f-8cdd-4b48-aba5-68f2c758d1e7)

**Test Set:**

![Test Set Result](https://github.com/user-attachments/assets/f3a451b2-855e-4f5d-a5ef-598edfbdc98d)
---

## 🛠 Requirements
Make sure you have the following Python libraries installed (in Google Colab, they are typically pre-installed):
- `numpy`
- `pandas`
- `matplotlib`
- `sklearn`

---

## 📊 Model Used
A **Random Forest Classifier** with the following parameters:
- `n_estimators = 10`
- `criterion = 'entropy'`
- `random_state = 0`

This ensemble method builds multiple decision trees and merges them to get more accurate and stable predictions.
