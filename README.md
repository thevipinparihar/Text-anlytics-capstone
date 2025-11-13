# Breast Cancer Analytics Using Big Data, Text, Social Media & Web Analytics  
### **Capstone Project – MBA Business Analytics**  
**Author:** Vipin Kumar  
**Roll Number:** 24MBMB13  
**University:** University of Hyderabad   
**Year:** 2025  

---

# 📌 Project Overview  
This capstone project explores how **Big Data Analytics**, **Text Mining**, **Social Media Analysis**, and **Web Analytics** can be used to understand breast cancer awareness, patient emotions, recurrence risk, and public engagement.

The project contains **5 use cases**, each focusing on a real-world analytical scenario using a single integrated dataset of **350 synthetic records**, including:  
- Tweets  
- Articles/Blogs  
- Patient support group posts  
- Google Search Trends  
- YouTube comments + engagement data  

All analysis was performed using:  
✔ **PySpark**  
✔ **Pandas**  
✔ **NLTK (VADER + NRC)**  
✔ **TF-IDF + LDA Topic Modeling**  
✔ **Machine Learning Models**  
✔ **Matplotlib & Seaborn (2D/3D Visuals)**  

---

# 📁 Dataset Description  
Filename: **breast_cancer_text_social_web_data.csv**  
Rows: **350**  
Columns include:  

### **Social Media (Tweets)**
- `tweet_text`  
- `tweet_sentiment`  
- `likes`, `retweets`  

### **Articles (Text Analytics)**
- `article_text`  
- `topic_predicted`  

### **Patient Support Group (Emotion Detection)**
- `patient_post`  
- `primary_emotion`  

### **Web Analytics (Google Trends)**  
- `google_search_index`  
- `month`  

### **YouTube Analytics**  
- `youtube_comment`  
- `comment_sentiment`  
- `video_likes`, `video_views`  

---

# 🧠 **Use Case 1 — Early Detection via Social Media Sentiment**  
### **Goal:**  
Analyze public sentiment about breast cancer awareness using **VADER sentiment analysis**.

### **Techniques Used:**  
- VADER compound score  
- Label comparison  
- 2D & 3D visualizations  
- Engagement analysis (likes vs retweets)

### **Key Output Metrics:**  
**Logistic Regression:**  
- Accuracy: **0.5650**  
- ROC-AUC: **0.4840**  

**Random Forest:**  
- Accuracy: **0.5800**  
- ROC-AUC: **0.5304**  

### **Visualizations:**  
✔ Bar chart of sentiments  
✔ Pie chart  
✔ Word cloud  
✔ 3D rotating engagement scatter  

---

# 🧵 **Use Case 2 — Topic Modeling on Awareness Articles**  
### **Goal:**  
Extract dominant topics from article/blog text.

### **Techniques Used:**  
- Text Cleaning  
- TF-IDF Vectorization  
- LDA Topic Modeling (5 topics)  
- Topic assignment  
- 3D topic visualizations

### **Key Output Metric:**  
- **Random Forest ROC-AUC: 0.5186**  
- **Silhouette Score (Clustering): 0.0906**  

### **Visualizations:**  
✔ Topic distribution  
✔ Keyword bar charts  
✔ Topic heatmap  
✔ 3D rotating topic scatter  
✔ Topic word clouds  

---

# 💬 **Use Case 3 — Emotion Detection on Patient Support Posts**  
### **Goal:**  
Detect emotional patterns (fear, sadness, trust, joy, anger).

### **Techniques Used:**  
- NRC Emotion Lexicon  
- Tokenization  
- Emotion scoring dictionary  
- Dominant emotion prediction  
- 3D emotion mapping  

### **Visualizations:**  
✔ Emotion distribution  
✔ Emotion pie chart  
✔ Emotion heatmap  
✔ 3D rotating emotion scatter  
✔ Emotion word clouds  

---

# 🌐 **Use Case 4 — Web Search Trend Analytics**  
### **Goal:**  
Analyze Google search interest trends and detect spikes (e.g., Breast Cancer Awareness Month in October).

### **Techniques Used:**  
- Time-series creation from month  
- Rolling averages (3M, 6M)  
- Peak detection  
- Year–Month heatmap  

### **Visualizations:**  
✔ Trend line + Rolling averages  
✔ Peak detection markers  
✔ Seasonal month-wise boxplot  
✔ Year–month heatmap  
✔ 3D rotating surface plot  

### **Key Result:**  
- Web search interest shows seasonal peaks in **October**.

---

# ▶ **Use Case 5 — YouTube Comment Analytics + Engagement Prediction**  
### **Goal:**  
Analyze YouTube comments and predict engagement using sentiment + TF-IDF.

### **Techniques Used:**  
- Clean YouTube comments  
- VADER sentiment  
- TF-IDF features (300)  
- Ridge Regression  
- Engagement score creation  

### **Model Output:**  
- **YouTube Comment Classifier (Text-only)**  
- Accuracy: **0.58**  
- ROC-AUC: **0.5830**  

**Confusion Matrix:**  
# Text-anlytics-capstone
[[62 52]
[32 54]]
### **Visualizations:**  
✔ Sentiment distribution  
✔ Engagement histogram  
✔ 3D engagement scatter  
✔ Rotating 3D comment engagement plot  

---

# 🎯 Project Architecture  
-- data/
| └── breast_cancer_text_social_web_data.csv
|
|-- notebooks/
| ├── use_case_1_sentiment.ipynb
| ├── use_case_2_topic_modeling.ipynb
| ├── use_case_3_emotion_detection.ipynb
| ├── use_case_4_web_trends.ipynb
| └── use_case_5_youtube_analytics.ipynb
|
|-- outputs/
| ├── sentiment_results.csv
| ├── topics_table.csv
| ├── emotion_results.csv
| ├── web_trend_results.csv
| ├── youtube_engagement_results.csv
|
└── README.md
---

# 🏆 Key Insights Across All Cases
- Public sentiment on awareness posts leans **neutral–positive**, but predictive accuracy is limited.  
- Topic modeling identifies **5 strong awareness themes**.  
- Patient posts show high **fear** and **sadness**, echoing emotional support needs.  
- Web search spikes **every October** (awareness month).  
- YouTube engagement depends heavily on **sentiment + content richness**.

---

# 💡 Why This Project Matters  
This project demonstrates how multidisciplinary analytics — **Big Data**, **NLP**, **ML**, **Social Media**, **Web Trends** — can support:  
- Early cancer detection  
- Public health awareness  
- Patient emotional understanding  
- Research funding trends  
- Healthcare communication  

---

# 🎤 Viva Preparation Summary  
You should be able to answer:  
- Why Big Data is used in healthcare  
- How sentiment analysis works (VADER, polarity)  
- What TF-IDF & LDA are  
- How NRC lexicon detects emotions  
- Why search interest spikes in October  
- How engagement modeling works  
- Differences between classification & regression  

---

# 📬 Contact  
**Vipin Kumar**  
Roll No: **24MBMB13**  
MBA Business Analytics — University of Hyderabad  
