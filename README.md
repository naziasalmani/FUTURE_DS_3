🎓 College Event Feedback Analysis

📌 Project Overview
This project analyzes student feedback collected through survey responses to evaluate overall satisfaction levels and identify areas for improvement. The analysis combines rating-based data analysis with NLP-based sentiment analysis to provide actionable insights for improving course and event quality.

🎯 Objectives
Understand overall student satisfaction using survey ratings
Identify high- and low-performing feedback categories
Apply NLP techniques to analyze feedback sentiment
Visualize trends and patterns in student responses
Provide data-driven recommendations for improvement

🧰 Tools & Technologies
Google Colab – Online notebook environment
Python – Data analysis
pandas – Data cleaning & manipulation
matplotlib & seaborn – Data visualization
TextBlob – NLP-based sentiment analysis
WordCloud – Text visualization

📂 Dataset
Student Feedback Survey Responses (Kaggle)
Note: The dataset does not contain open-ended feedback. For demonstrating NLP techniques, feedback text was programmatically generated based on satisfaction scores.

🔄 Data Cleaning & Preparation
Converted rating columns to numeric format
Handled auto-generated index column by setting it as a serial number
Identified and separated rating columns from identifier fields

📊 Analysis Performed
🔹 Rating-Based Analysis
Calculated average scores for each feedback category
Created an Overall Satisfaction Score per student
Classified satisfaction levels into:
Highly Satisfied
Satisfied
Needs Improvement

🔹 NLP-Based Sentiment Analysis
Generated representative feedback text based on satisfaction scores
Applied TextBlob to classify sentiment into:
Positive
Neutral
Negative
Visualized sentiment distribution and key terms using a Word Cloud

📌 Key Insights
Most students fall into the Satisfied category, indicating generally positive feedback with scope for improvement.
Only a small proportion of students are Highly Satisfied, suggesting opportunities to enhance engagement.
Course relevance and subject understanding received higher average ratings.
Course structure and assignment difficulty showed comparatively lower satisfaction.
NLP analysis revealed predominantly Neutral and Positive sentiment, indicating moderate but favorable student perceptions.

🎯 Recommendations
Improve course structuring and pacing to enhance student understanding.
Introduce more interactive teaching methods and effective presentations.
Provide additional academic support for students facing assignment difficulties.
Collect open-ended feedback in future surveys for deeper qualitative insights.
