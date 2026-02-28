                                                  📱 Day 19 – Mobile Price Classification

✨ Dataset Source 

https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification

---

📌 Dataset Description

This dataset contains specifications of mobile phones and their corresponding price range categories.

Bob wants to understand the relationship between mobile features (like RAM, battery power, internal memory, etc.) and the price range of the phone.

Instead of predicting exact price, the goal is to classify mobiles into different price ranges.

---

📊 Type of Data

Structured tabular dataset  
Numerical + Binary features

Total Records: 1000  
Total Features: 20+  

---

🤖 ML Concept

Machine Learning – Multi-Class Classification

The goal is to classify mobile phones into different price categories.

---

🎯 Target Variable

price_range

Classes:
0 → Low Cost  
1 → Medium Cost  
2 → High Cost  
3 → Very High Cost  

---

📥 Input Features

- battery_power (mAh)  
- blue (Bluetooth availability)  
- clock_speed  
- dual_sim  
- fc (Front camera MP)  
- four_g  
- int_memory (GB)  
- m_dep (Mobile depth)  
- mobile_wt (Weight)  
- n_cores  
- pc (Primary camera MP)  
- ram  
- screen_height  
- screen_width  
- talk_time  
- three_g  
- touch_screen  
- wifi  

---

📤 Output

Predicted price range category (0–3)

---

🧠 What We Learned

- RAM is one of the strongest predictors of price  
- Battery power impacts higher price categories  
- Internal memory affects pricing  
- Screen resolution influences premium range  
- 4G / Touchscreen features impact pricing  

---

🔗 Correlation Insights

- RAM ↔ Price Range (Strong positive correlation)  
- Battery Power ↔ Price  
- Internal Memory ↔ Price  
- Screen Size ↔ Price Category  
- 4G Support ↔ Higher Price Range  

---

📈 Visualization Ideas

- RAM vs Price Range box plot  
- Battery power distribution  
- Feature importance chart  
- Correlation heatmap  
- Class distribution bar chart  

---

🌍 Real-Life Use

Used in:

- Product pricing strategy  
- Market segmentation  
- Competitive mobile analysis  
- Feature-based pricing optimization  
- Business decision support  

---

🎓 Learning Outcome

This project helped understand:

✔ Multi-class classification  
✔ Feature importance analysis  
✔ Business-driven ML problems  
✔ Market-based predictive modeling  
✔ Data preprocessing techniques  

---

⭐ This project demonstrates how machine learning can classify products into price segments based on technical specifications.
