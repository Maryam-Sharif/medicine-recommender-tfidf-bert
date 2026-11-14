Medicine Recommender: TF-IDF vs BERT

A learning project that recommends medicines from a text query (for example "treatment of high blood pressure") using TF-IDF and BERT embeddings with cosine similarity.

Disclaimer: research and learning project only. It is not medical advice.

Dataset

Kaggle "11000 Medicine Details": https://www.kaggle.com/datasets/singhnavjot2062001/11000-medicine-details The CSV is not included here. Download it and place Medicine_Details.csv next to the notebook.

What the notebook does
Explores the data (11,825 rows, no missing values, 84 duplicate rows, only 712 unique Uses values)
Cleans the text (lowercase, remove symbols, stop words, lemmatize)
Builds a TF-IDF recommender and a BERT (all-MiniLM-L6-v2) recommender
Tests both with synthetic queries (Top-1, Precision@5, precision / recall / F1)
Based on

Nagalakshmi R et al., SLAS Technology 31 (2025) 100238, https://doi.org/10.1016/j.slast.2024.100238
