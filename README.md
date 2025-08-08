# Sprint 16 - Project: Movie Review Classification - Film Junky Union

The project is an opportunity to apply machine learning knowledge to a real-world problem.

---

## Project Objective

Develop a machine learning model capable of **automatically classifying movie reviews as positive or negative** using a dataset from IMDB. The model must achieve a **minimum F1 score of 0.85**.

---

## Dataset

The dataset is located in the `imdb_reviews.tsv` file and contains the following relevant columns:

- `review`: Review text.
- `pos`: Target label (0 = negative, 1 = positive).
- `ds_part`: Part of the dataset (`training` or `test`).

Source: *Maas et al. (2011). Learning Word Vectors for Sentiment Analysis.*

---

## Project Instructions

1. **Data Loading**
2. **Initial Preprocessing**
3. **Exploratory Data Analysis (EDA)**
   - Class distribution visualization
   - Observations on imbalance
4. **Text Vectorization**
   - TF-IDF, CountVectorizer, etc.
5. **Model Training**
   - At least three different models (e.g., Logistic Regression, Random Forest, Gradient Boosting)
6. **Model Evaluation**
   - Metrics: F1, Precision, Recall, Accuracy
   - Use of `evaluate_model()`
7. **Classification of New Reviews**
   - Comparison of predictions between models
   - Analysis of differences
8. **Conclusions and Findings**

---

## Models Used

- Logistic Regression
- Gradient Boosting (LightGBM)
> Optional: BERT is used for a small sample of the dataset.

---

## Best Practices

- Clean and modular code
- No unnecessary duplication
- Clear and orderly structure
- Explanatory comments

---

## Checklist

- Data loading and preprocessing
- Text vectorization
- Model training and evaluation
- F1 threshold reached
- Error-free executable code
- Clear conclusions

---

## Tools

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Re
- Sklearn
- tqdm
- NLTK
- spaCy
- Lightgbm
- Torch
- Transformers
- Logging