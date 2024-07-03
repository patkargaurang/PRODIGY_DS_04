# PRODIGY_DS_04
## Objective 
   My fourth task as Data Science Intern at Prodigy InfoTech, focused on Sentiment Analysis on product review dataset.

## Overview
   In this project, I conducted a sentiment analysis of Amazon product reviews using the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool. The analysis began with data preprocessing and visualization to understand the distribution of star ratings. A sample review was tokenized to illustrate the text processing steps, and the SentimentIntensityAnalyzer was employed to calculate polarity scores for the reviews, quantifying sentiments as positive, neutral, or negative. By applying these scores across the dataset, we could correlate sentiment with star ratings, offering valuable insights into customer opinions. The visualizations effectively depicted the relationship between sentiment scores and star ratings, highlighting trends and patterns in customer feedback.

   Sample Dataset : https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews
### 1. Data Overview & Pre-Preprocessing
<img width="1430" alt="4 1" src="https://github.com/patkargaurang/PRODIGY_DS_01/assets/173181353/0279715a-f460-4d8e-84c0-917fd0da0a8d">
<img width="1430" alt="4 2" src="https://github.com/patkargaurang/PRODIGY_DS_01/assets/173181353/7235d83e-484d-49a8-bbce-94ac23c8cfc4">
<img width="1428" alt="4 3" src="https://github.com/patkargaurang/PRODIGY_DS_01/assets/173181353/e0d040fa-6914-48a9-8fcf-2713b7c766e7">
<img width="1431" alt="4 4" src="https://github.com/patkargaurang/PRODIGY_DS_01/assets/173181353/06753137-8c92-45cf-a6ac-a302dff3ebf6">

### 2. Data Visualization 
### Distribution of Review Score 
<img width="1429" alt="4 5" src="https://github.com/patkargaurang/PRODIGY_DS_01/assets/173181353/8d6be05b-6b84-4a1d-840c-426fd01f9c74">
<img width="1428" alt="4 6" src="https://github.com/patkargaurang/PRODIGY_DS_01/assets/173181353/c25b7624-79e2-4081-8b48-580aba4b0bd2">

### Vectorize review statements & implement Sentiment Intensity Analyser (SIA)
<img width="1431" alt="4 7" src="https://github.com/patkargaurang/PRODIGY_DS_01/assets/173181353/eadc2d97-4735-4579-9683-c630e4a195eb">
<img width="1431" alt="4 8" src="https://github.com/patkargaurang/PRODIGY_DS_01/assets/173181353/ebda16f8-3596-43d1-a64e-7a1bc1d03054">

### VADER Sentiment Scoring on the Dataset
<img width="1431" alt="4 9" src="https://github.com/patkargaurang/PRODIGY_DS_01/assets/173181353/9272a81e-751f-48ac-ba17-6cab8ce1ad1b">
<img width="1429" alt="4 10" src="https://github.com/patkargaurang/PRODIGY_DS_01/assets/173181353/119b0b8d-1f20-4987-b529-c78c8ce2659b">

### Sentiment vs Review Score 
<img width="1430" alt="4 11" src="https://github.com/patkargaurang/PRODIGY_DS_01/assets/173181353/c810971b-90a1-4f01-8a96-81c28104847f">
<img width="1431" alt="4 12" src="https://github.com/patkargaurang/PRODIGY_DS_01/assets/173181353/c8c18c59-e07a-41d9-8e1c-db19ecc02ff8">

### Sentiment with respective Compound Score [Negative(-1),  Positive(+1)  &  Neutral(0)]
<img width="1432" alt="4 13" src="https://github.com/patkargaurang/PRODIGY_DS_01/assets/173181353/12ce7568-d52c-4542-88a5-76eaac63eb0e">
<img width="1430" alt="4 14" src="https://github.com/patkargaurang/PRODIGY_DS_01/assets/173181353/246905c4-c978-41fd-87d3-4edcbd998e1e">


## Conclusion 
In conclusion, this sentiment analysis of Amazon product reviews using the VADER sentiment analysis tool successfully quantified and visualized the relationship between textual sentiment and star ratings. The analysis revealed clear correlations between sentiment polarity scores and customer ratings, demonstrating that higher star ratings are associated with more positive sentiment scores, while lower star ratings align with negative sentiment scores. This project underscores the effectiveness of natural language processing techniques in extracting actionable insights from large volumes of text data, providing a robust framework for understanding customer feedback and enhancing product and service quality.
