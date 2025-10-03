# 🎥 YouTube Text Data Analysis – Case Study

This project focuses on **Text Data Analysis** using YouTube video data. The main goal is to analyze comments, titles, and metadata to extract insights about audience behavior, engagement patterns, and content trends. By applying text processing and visualization techniques, the study highlights how creators and brands can better understand their viewers.

## 📜 Project Overview

YouTube generates millions of comments and metadata entries every day, providing a rich source for text-based analysis. This project examines:

* Patterns in video comments and engagement.
* People Sentiment Analysis
* Emoji Analysis
* Frequently used keywords and sentiments.
* Topic trends across different categories.
* The relationship between audience feedback and video popularity.
* Channels having maximum number of trending videos

The study demonstrates the value of Natural Language Processing (NLP) in uncovering actionable insights from unstructured text data.

## 📂 Dataset

* **Source**: YouTube dataset (Kaggle / Collected via API)
* **File**: `youtube_data.csv`

### 🔑 Key Columns

* **video_id** → Unique identifier for each video
* **title** → Title of the video
* **channel_title** → Name of the channel
* **category_id** → Category of the video
* **publish_time** → Date and time of publishing
* **views** → Number of views
* **likes** → Number of likes
* **dislikes** → Number of dislikes
* **comment_count** → Total number of comments
* **comments_text** → Text of user comments

## 🛠️ Tools & Libraries

* **Python** → Data cleaning & preprocessing
* **NLTK / spaCy** → Text processing and NLP tasks
* **TextBlob / VADER** → Sentiment analysis
* **WordCloud** → Visualization of frequent words
* **Emoji** -> List of all emojis
* **Matplotlib / Seaborn / Plotly** → Data visualization
* **Jupyter Notebook** → Interactive workflow

## 📊 Methodology

1. **Data Cleaning** → Removed duplicates, handled missing values, and standardized text.
2. **Preprocessing** → Tokenization, stopword removal, stemming/lemmatization.
3. **Exploratory Data Analysis (EDA)** → Analyzed distributions of views, likes, comments.
4. **Sentiment Analysis** → Classified comments into positive, negative, and neutral.
5. **Keyword & Topic Trends** → Identified trending words and topics from comments.
6. **Visualization** → Created plots, charts, and word clouds for insights.

## 📈 Key Insights

* Audience engagement often correlates strongly with **positive sentiment** in comments.
* Certain categories (like entertainment and music) attract the most **viewer interaction**.
* **Word clouds** and frequency analysis highlight recurring themes in audience discussions.
* Negative sentiment often spikes around **controversial topics** or **policy-related videos**.

<img width="649" height="333" alt="image" src="https://github.com/user-attachments/assets/dc684ad2-68d8-4d42-85f9-bdc99885888d" />
<img width="646" height="340" alt="image" src="https://github.com/user-attachments/assets/a240aee4-f63c-4ab1-b878-d250f4da93ff" />
<img width="745" height="316" alt="image" src="https://github.com/user-attachments/assets/647bff00-c280-4237-a27b-2a326eb42aab" />
<img width="833" height="696" alt="image" src="https://github.com/user-attachments/assets/8b348315-fd92-425d-ba12-4b4f30f59c03" />
<img width="832" height="767" alt="image" src="https://github.com/user-attachments/assets/af1d9d8a-769e-41b7-a865-aced6c037ac4" />
<img width="692" height="557" alt="image" src="https://github.com/user-attachments/assets/32befa13-4442-44d4-a157-3ee885ff7d66" />
<img width="673" height="540" alt="image" src="https://github.com/user-attachments/assets/800e69da-8d58-489a-b64d-485cf898fcb4" />
<img width="744" height="457" alt="image" src="https://github.com/user-attachments/assets/74b3123d-95f5-4c5b-985c-1de9f2765338" />
