# DSF38_MachineLearning

This project is an assignment from the **Digital Skill Fair 38.0** bootcamp, under the **AI/ML specialization**, organized by **Dibimbing.id**. The objective of the project is to predict students' exam scores based on the number of hours they studied using machine learning regression models.

## 📘 Project Overview

The goal is to identify the most accurate regression model to predict exam scores. The project follows a structured pipeline:

- ✅ Data Cleaning & Feature Validation  
- 📊 Exploratory Data Analysis (EDA)  
- 🤖 Model Training:  
  - Linear Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor  
- 📈 Model Evaluation using MSE & R² Score  
- 📉 Visual Comparison of Predictions  

## 📂 Dataset

- **Filename**: `student_scores.csv`
- **Features**:
  - `Hours`: Study hours
  - `Scores`: Exam scores

## 📊 Exploratory Data Analysis (EDA)

EDA involved:
- Descriptive statistics for feature summary
- Histograms with KDE for distribution analysis
- Scatter plot to show linear relationship
- Correlation heatmap
- Boxplots to detect outliers

## 🤖 Model Evaluation Results

| Model                   | MSE     | R² Score |
|------------------------|---------|----------|
| Linear Regression       | 18.94   | 0.968    |
| Decision Tree Regressor | 31.70   | 0.946    |
| **Random Forest Regressor** | **13.05** | **0.978** |

📌 **Conclusion**:  
The **Random Forest Regressor** performed the best with the **lowest MSE** and **highest R² Score**, making it the most accurate model for this prediction task.

## 📁 Files in this Repository

- `Student_Scores_Prediction_DSF38.ipynb`: Jupyter notebook containing the full project code.
- `student_scores.csv`: The dataset used.
- `Student Scores Prediction - Machine Learning.pdf`: PDF version of the presentation/report.
- `README.md`: Project overview and documentation.

## 🔗 Links

- 💻 [GitHub Repo](https://github.com/nadhif-royal/DSF38_MachineLearning)  
- 📄 [LinkedIn Profile](https://www.linkedin.com/in/royalnadhif50/)

---

