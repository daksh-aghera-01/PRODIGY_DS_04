# 📊 Twitter Sentiment Analysis on Entities

This project analyzes public sentiment from Twitter data related to different entities (brands, topics, people) using a labeled dataset. It includes sentiment classification (positive, neutral, negative) and visual insights to understand public opinion.

## 📁 Dataset
- Source: [Kaggle - Twitter Entity Sentiment Analysis](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)
- It includes tweet texts, entity names, and sentiment labels.

## 📁 Folder Structure
```
decision-tree-bank-marketing/
├── data/
│   ├── twitter_training.csv
│   └── twitter_validation.csv
├── notebooks/
│   └── Task 4.ipynb
├── outputs/
│   ├── Overall Sentiment Distribution.png
│   ├── Top 10 Most Discussed Topics.png
│   ├── Sentiment Breakdown for Top 10 Topics.png
│   ├── WorldCloud - Positive.png
│   ├── WorldCloud - Neutral.png
│   ├── WorldCloud - Negative.png
│   └── WorldCloud - Irrelevant.png
├── requirements.txt
└── README.md
```

## ✅ Key Tasks
- Data Cleaning & Preprocessing
- Exploratory Data Analysis
- Sentiment-wise Visualization (Bar Plot, WordClouds)
- Entity Mention Analysis

## 📷 Visualizations
- Sentiment distribution bar chart
- WordClouds for each sentiment
- Pie charts for entity-specific sentiment ratios

## 🧪 Libraries Used
- pandas
- matplotlib
- seaborn
- wordcloud
- nltk

## ▶️ Run the Notebook
1. Clone the repository
2. Install requirements:  
   ```
   pip install -r requirements.txt
   ```
3. Open the notebook and run all cells:
   ```
   jupyter notebook Task_4.ipynb
   ```

## 🔖 Internship Info
This project was completed as part of my internship at **Prodigy Infotech** under the task title:  
**"Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands."**

