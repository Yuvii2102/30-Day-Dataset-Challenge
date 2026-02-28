                                                📄 Day 15 – Student Dropout Prediction Dataset


✨ Dataset Source :

https://www.kaggle.com/datasets/meharshanali/student-dropout-prediction-dataset

---

📌 Dataset Description

This dataset contains information about 10,000 students and is designed to predict whether a student will drop out or continue their studies.

It includes academic performance, demographic details, and behavioral features.

The data is synthetic but closely resembles real-world student data, including:
- Slight income and stress skewness
- Logical academic correlations
- 5% missing values (realistic dataset behavior)

---

📊 Type of Data

Structured data (tabular dataset)  
Contains both numerical and categorical features.

---

🤖 ML Concept

Machine Learning – Classification  

Predicting whether a student will drop out.

---

🎯 Target Variable

Dropout  
- 0 = Retained  
- 1 = Dropped Out  

Dropout Rate: 23.5%

---

📥 Input Features

- Age  
- Gender  
- Family_Income  
- Internet_Access  
- Study_Hours_per_Day  
- Attendance_Rate  
- Assignment_Delay_Days  
- Travel_Time_Minutes  
- Part_Time_Job  
- Scholarship  
- Stress_Index (1–10)  
- GPA  
- Semester_GPA  
- CGPA  
- Semester  
- Department  
- Parental_Education  

---

📤 Output

- Dropout (0 or 1)

---

🧠 What We Learned

- Low GPA and CGPA increase dropout risk  
- Poor attendance strongly affects retention  
- High stress levels increase dropout probability  
- Students with scholarships are less likely to drop out  
- Assignment delays and low study hours impact performance  

---

🔗 Correlation Insights

- GPA ↔ Dropout (Strong Negative Correlation)  
- Attendance_Rate ↔ Dropout (Negative Correlation)  
- Stress_Index ↔ Dropout (Positive Correlation)  
- Assignment_Delay ↔ Dropout (Positive Correlation)  

---

📈 Visualization Ideas

- Dropout distribution chart  
- GPA vs Dropout comparison  
- Attendance vs Dropout scatter plot  
- Stress level impact graph  
- Correlation heatmap  

---

🛠 Baseline Model

Logistic Regression  

ROC-AUC Score: 0.818  

Most Important Features:
✔ GPA  
✔ CGPA  
✔ Semester_GPA  
✔ Attendance_Rate  
✔ Stress_Index  

---

🌍 Real-Life Use

Used in:

- Early identification of at-risk students  
- Academic performance monitoring  
- University decision-making systems  
- Student retention strategies  

---

🎓 Learning Outcome

This project helped understand:

✔ Classification modeling  
✔ Handling imbalanced datasets  
✔ Missing value treatment  
✔ Feature importance analysis  
✔ Educational data analytics  

---

⭐ This project demonstrates how machine learning can predict student dropout risk using academic and behavioral data.
