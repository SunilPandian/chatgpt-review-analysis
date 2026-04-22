# 📊 ChatGPT Review Analysis (Sentiment & NLP Project)

## 🔍 Project Overview
This project analyzes customer reviews of ChatGPT to understand user sentiment, satisfaction levels, and key feedback patterns. Using Natural Language Processing (NLP) techniques, the project extracts meaningful insights from textual data and visualizes trends in user opinions.

---

## 🎯 Objective
The main objectives of this project are:

- Analyze overall user sentiment (positive, neutral, negative)
- Measure subjectivity (opinion vs factual reviews)
- Identify frequently mentioned keywords
- Understand user satisfaction patterns
- Generate actionable insights from customer feedback

---

## 💼 Business Problem
Customer reviews provide valuable insights into user experience. This project answers:

- Are users satisfied with ChatGPT?
- What features do users appreciate the most?
- What are common complaints?
- How does sentiment align with ratings?

---

## 📁 Dataset Information

- **Total Records:** ~196,000 reviews  
- **Columns:**
  - `Review Id` – Unique identifier
  - `Review` – User feedback text
  - `Ratings` – User rating (1–5)
  - `Review Date` – Timestamp of review  

---

## 🧹 Data Cleaning & Preparation

- Handled missing values in review text
- Converted `Review Date` to datetime format
- Ensured correct data types
- Removed inconsistencies

---

## 📊 Exploratory Data Analysis (EDA)

- Rating distribution analysis
- Review length distribution
- Review trends over time
- Relationship between ratings and review length

---

## 🤖 Sentiment Analysis

Used **TextBlob** to calculate:

- **Polarity** → Range [-1, +1]
- **Subjectivity** → Range [0, 1]

### Sentiment Classification:
- Positive → Polarity > 0  
- Neutral → Polarity = 0  
- Negative → Polarity < 0  

---

## 🧠 Text Analysis

- Removed stopwords using NLTK
- Extracted frequent keywords
- Generated:
  - Word Cloud
  - Keyword frequency charts

---

## 📈 Key Insights

- Majority of users expressed **positive sentiment**
- Strong correlation between **ratings and sentiment**
- Most reviews are **subjective (opinion-based)**
- Frequently used positive words:
  - "helpful"
  - "easy"
  - "fast"
- Negative feedback highlights:
  - occasional incorrect responses
  - accuracy concerns

---

## 📊 Visualizations

The project includes:

- Rating Distribution (Bar Chart)
- Review Length Distribution (Histogram)
- Reviews Over Time (Line Chart)
- Sentiment Distribution (Bar Chart)
- Ratings vs Sentiment (Stacked Bar Chart)
- Word Cloud (Text Visualization)
- Top Keywords Frequency Chart

---

## 🚀 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- NLTK
- TextBlob
- WordCloud

---

## 📂 Project Structure

chatgpt-review-analysis/
│
├── data/
│ └── chatgpt_reviews.csv
│
├── notebook/
│ └── analysis.ipynb
│
├── visuals/
│ ├── rating_distribution.png
│ ├── sentiment_distribution.png
│ ├── wordcloud.png
│
├── README.md

---

## ▶️ How to Run

1. Clone the repository:

git clone https://github.com/yourusername/chatgpt-review-analysis.git

---

2. Install dependencies:

pip install pandas numpy matplotlib nltk textblob wordcloud

3. Run the notebook:

jupyter notebook

---

## 📹 Project Demonstration

This project was demonstrated by explaining the complete workflow, including:

- Problem statement and objectives
- Data understanding and preprocessing steps
- Exploratory Data Analysis (EDA)
- Sentiment analysis using NLP techniques
- Keyword extraction and visualization
- Key insights and conclusions

The demonstration focused on clearly communicating how raw textual data can be transformed into meaningful business insights using data analysis and NLP methods.

---

## 📌 Conclusion

This project successfully analyzes ChatGPT user reviews to uncover sentiment patterns and user feedback trends.

Key takeaways:

- Majority of users show **positive sentiment**, indicating overall satisfaction
- Strong alignment between **ratings and sentiment polarity**
- Most reviews are **subjective**, reflecting user opinions
- Frequently mentioned words like *helpful*, *easy*, and *fast* highlight key strengths
- Some negative feedback points to **accuracy-related concerns**

Overall, this project demonstrates how Natural Language Processing (NLP) can be used to extract actionable insights from unstructured text data.

---

## 🔮 Future Improvements

- Implement advanced NLP models such as **BERT** or **Transformers**
- Perform **aspect-based sentiment analysis** for deeper insights
- Build an **interactive dashboard** using Power BI or Tableau
- Automate real-time sentiment analysis pipeline

---

## 🙌 Author

Sunil Pandian. J

