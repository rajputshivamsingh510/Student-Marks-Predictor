#  Student Marks Predictor

A simple machine learning project that predicts student exam scores based on the number of hours they studied. This project uses Linear Regression and KNN Regression to analyze and compare performance.

---

##  Problem Statement

Given the number of study hours, predict the score a student is likely to achieve in an exam. This is a supervised regression problem using a simple dataset.

---

##  Dataset

- **Name:** Student Scores Dataset  
- **Source:** [Kaggle – mexwell/student-scores](https://www.kaggle.com/datasets/mexwell/student-scores)
- **Features:**
  - `Hours`: Number of hours studied
  - `Scores`: Marks scored in exam

---

##  Algorithms Used

-  Linear Regression
-  K-Nearest Neighbors (KNN) Regression

---

## 🛠 Technologies

- Python 
- pandas
- matplotlib
- scikit-learn
---

##  Evaluation Metrics

| Metric        | Linear Regression | KNN Regression |
|---------------|-------------------|----------------|
| Mean Squared Error (MSE) | 30.87 | 32.21 |
| R² Score      | 0.28              | 0.25           |

 **Interpretation:**
- Both models show moderate performance.
- Linear Regression slightly outperforms KNN, which is expected due to the linear nature of the data.

---

##  Visualizations

- Scatter plot of study hours vs scores
- Regression line (for Linear Regression)
- Comparison of Actual vs Predicted scores

---

##  How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/student-marks-predictor.git
   cd student-marks-predictor
