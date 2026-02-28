                                          🕵️ Day 21 – Deepfake & Synthetic Media Detection Dataset

✨ Dataset Source 

https://www.kaggle.com/datasets/payaldhokane/deepfake-and-synthetic-media-detection-dataset

---

📌 Dataset Description

This dataset contains synthetic forensic metadata representing real and AI-generated (deepfake) media samples across images, videos, and audio.

It is designed for deepfake detection research and binary classification tasks.

⚠️ Note:
This dataset contains synthetic metadata only and does NOT include actual deepfake media files.

---

📊 Type of Data

Structured tabular dataset  
Numerical + Categorical + Binary features  

Total Records: 1000  

---

🤖 ML Concept

Machine Learning – Binary Classification  

Goal:  
Classify media as:

0 → Real  
1 → Fake (Deepfake / AI-generated)

---

🎯 Target Variable

is_fake (Real vs AI-generated content)

---

📥 Input Features

Media Information:
- media_type (Image / Video / Audio)
- content_category
- face_count
- audio_present
- source_platform

Forensic Indicators:
- lip_sync_score (0–1)
- visual_artifacts_score (0–1)
- compression_level (0–1)
- lighting_inconsistency_score (0–1)

---

📤 Output

Predicted Label:
- Real
- Fake (Deepfake)

---

🧠 What We Learned

- High visual artifact score often indicates fake content  
- Poor lip-sync consistency suggests synthetic video  
- Lighting inconsistencies are common in deepfakes  
- Compression anomalies can reveal AI generation  
- Multi-feature analysis improves detection accuracy  

---

🔗 Correlation Insights

- Lip Sync Score ↔ Authenticity  
- Visual Artifacts ↔ Fake Probability  
- Lighting Inconsistency ↔ AI Generation  
- Compression Level ↔ Synthetic Media Detection  

---

📈 Visualization Ideas

- Feature importance chart  
- Correlation heatmap  
- Lip-sync score distribution (Real vs Fake)  
- Platform-wise fake content analysis  
- Media-type vs detection accuracy  

---

🌍 Real-Life Use

Used in:

- Social media moderation systems  
- News verification platforms  
- Digital forensics research  
- AI-generated content detection  
- Cybersecurity applications  

---

🎓 Learning Outcome

This project helped understand:

✔ Binary classification modeling  
✔ AI forensics concepts  
✔ Feature importance analysis  
✔ Ethical AI research applications  
✔ Real-world deepfake detection modeling  

---

⭐ This project demonstrates how machine learning can analyze forensic metadata to detect AI-generated or manipulated media.
