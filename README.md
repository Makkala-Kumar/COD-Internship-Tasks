**Name:** KUMAR MAKKALA  
**Company:** CODTECH IT SOLUTIONS
**ID:** CT08WD39  
**Domain:** Data Analytics  
**Duration:** May to June 2024  
**Mentor:** SRAVANI GOUNI


# Task 1: Exploratory Data Analysis (EDA)

## Task Description
The goal of this task is to explore the characteristics, distributions, correlations, and outliers present in a dataset. I gained insights into the data through visualizations such as histograms, scatter plots, and heatmaps. This repository contains the code and visualizations for the task of Exploratory Data Analysis (EDA) performed on a dataset using Python libraries like pandas, matplotlib, and seaborn.

## Dataset
The dataset used for this analysis is the World Population Dataset. It contains population data from 1970 to 2022 for countries around the world. The dataset provides insights into population trends over time

## Contents
- **EDA_on_world_population_Dataset.ipynb**: Google Colab Notebook containing the Python code for EDA.![image](https://github.com/Makkala-Kumar/COD-Internship-Tasks/assets/136322019/75d0836c-587a-4166-a174-094551b1616a)
  - Histograms showing the distribution of population over time. ![image](https://github.com/Makkala-Kumar/COD-Internship-Tasks/assets/136322019/eba80000-718f-43f1-af75-10d3c58e95b8)
  - Scatter plots showing the relationship between different population years. ![image](https://github.com/Makkala-Kumar/COD-Internship-Tasks/assets/136322019/43e76354-c187-4ee6-9f3b-5a44bf22937a)
  - Heatmap showing the correlation between population years. ![image](https://github.com/Makkala-Kumar/COD-Internship-Tasks/assets/136322019/5a06c94b-4991-4540-839c-9b04e75dd06e)
  - Heatmap showing the correlation between population years. ![image](https://github.com/Makkala-Kumar/COD-Internship-Tasks/assets/136322019/72bf6fc9-cfb2-492b-95f0-cd0e833cd148)

## Dependencies
- Python
- pandas
- matplotlib
- seaborn


# Task 4: SOCIAL MEDIA SENTIMENT ANALYSIS
### Introduction
This project aims to analyze social media data (tweets) to detect hate speech, specifically racist or sexist content. The objective is to classify tweets as containing hate speech or not using machine learning techniques.

### Dataset
- **Size**: 31,962 labeled tweets.
- **Features**: Text content of tweets.
- **Labels**: Binary classification (1 for hate speech, 0 for non-hate speech).

### Methodology
1. **Data Preprocessing**: 
   - Removal of Twitter handles, special characters, and numbers.
   - Tokenization and stemming.
   
2. **Exploratory Data Analysis (EDA)**:
   - Visualization of frequent words and hashtags.
      ![image](https://github.com/Makkala-Kumar/COD-Internship-Tasks/assets/136322019/8a4b751c-d860-4774-8110-2a3a77f639b0) ![image](https://github.com/Makkala-Kumar/COD-Internship-Tasks/assets/136322019/66d96e2e-4bd6-46bf-acab-51af7b00305c) ![image](https://github.com/Makkala-Kumar/COD-Internship-Tasks/assets/136322019/0c36e1a8-e179-40b3-a6b3-49918b632367)
     
3. **Feature Extraction**:
   - Conversion of text data to numerical matrices using CountVectorizer.


4. **Model Training and Evaluation**:
   - Logistic Regression model trained on bag-of-words representation.
   - Performance evaluation using accuracy, F1-score, and ROC AUC score.
   - Confusion matrix visualization for analyzing predictions.

### Results
- Trained model achieved 95% accuracy.
- F1-score was 54% and ROC AUC score were 94%, respectively.
- Confusion matrix provided insights into model performance.

### Conclusion
This project demonstrates the application of NLP and machine learning for social media sentiment analysis, aiding in the detection of hate speech. Future work includes exploring advanced NLP models and real-time deployment.
