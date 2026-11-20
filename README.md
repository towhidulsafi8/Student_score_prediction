# 📚 Student Study Hours and Scores Prediction using Machine Learning

## 📌 Project Overview

This project predicts a student's exam score based on the number of hours they study using Machine Learning. It demonstrates the complete Machine Learning Life Cycle, from data preprocessing to model evaluation and prediction.

Two regression algorithms are implemented and compared:

- Linear Regression
- Decision Tree Regression

The best-performing model is selected based on evaluation metrics.

---

## 🎯 Objectives

- Analyze the relationship between study hours and exam scores.
- Train multiple machine learning models.
- Compare model performance.
- Predict exam scores for new study hour values.
- Demonstrate a complete Machine Learning workflow.

---

## 📂 Dataset

**Dataset Name:** Hours and Scores

**Features**

| Feature | Description |
|----------|-------------|
| Hours | Number of study hours |
| Scores | Student exam score |

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔄 Machine Learning Life Cycle

### 1. Import Libraries

Imported all required Python libraries for data analysis, visualization, and machine learning.

### 2. Data Collection

Loaded the dataset using Pandas.

### 3. Data Preprocessing

- Checked missing values
- Removed duplicate records
- Verified data types
- Cleaned unnecessary columns (if present)

### 4. Exploratory Data Analysis (EDA)

Performed:

- Distribution plots
- Scatter plot
- Correlation heatmap

### 5. Feature Selection

- **Input (X):** Study Hours
- **Target (y):** Exam Scores

### 6. Train-Test Split

Dataset split into:

- 80% Training
- 20% Testing

### 7. Model Training

Trained two machine learning models:

- Linear Regression
- Decision Tree Regression

### 8. Model Evaluation

Models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### 9. Model Comparison

Compared both models based on evaluation metrics.

### 10. Prediction

Predicted a student's exam score using the best-performing model.

---

## 📊 Evaluation Metrics

The following metrics were used:

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score

The model with the highest R² Score and lowest prediction error was selected as the best model.

---

## 📈 Visualizations

The project includes:

- Histogram of Study Hours
- Histogram of Scores
- Scatter Plot
- Correlation Heatmap
- Linear Regression Plot
- Decision Tree Regression Plot

---

## 📁 Project Structure

```
Student_Study_Hours_and_Scores/
│
├── Student_Study_Hours_and_Scores.ipynb
├── README.md
```

---

## ▶️ How to Run

1. Clone the repository.

```bash
[git clone https://github.com/towhidulsafi8/Student_score_prediction]
```

2. Open the notebook in Google Colab or Jupyter Notebook.

3. Install dependencies.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Run all notebook cells.

---

## 📌 Results

The project compares the performance of Linear Regression and Decision Tree Regression.

Based on the evaluation metrics, the model with the higher R² Score is selected as the final prediction model.

---

## 🚀 Future Improvements

- Add more student-related features such as attendance, sleep hours, and previous grades.
- Train advanced regression models.
- Perform hyperparameter tuning.
- Deploy the model as a web application using Flask or Streamlit.

---

## 👨‍💻 Author

**Towhidul Safi**

Department of Computer Science and Engineering (CSE)

---

## 📄 License

This project is intended for educational and academic purposes.
