# Sentiment Analysis on Amazon Product Reviews

## Description
This project classifies Amazon product reviews into Positive or Negative sentiments using Logistic Regression and TF-IDF vectorization. The model can predict the sentiment of any new product review text.

## Dataset
- Source: [Kaggle Amazon Reviews Dataset](https://www.kaggle.com/datasets/promptcloud/amazon-product-reviews-dataset)
- Columns used:
  - `Review Content`: Text of the review
  - `Review Rating`: Used to create sentiment label (Positive/Negative)
- Sample Size: 50 reviews (for demo)

## Technology Stack
- Python
- Pandas
- NLTK
- Scikit-learn
- Logistic Regression
- TF-IDF
- Jupyter Notebook

## How to Run

### 1. Clone this repository:
```bash
git clone https://github.com/PriyaShrivastava25/Sentiment-Analysis-Amazon-Reviews.git
```

## #2. Navigate to the project folder:
```bash
cd Sentiment-Analysis-Amazon-Reviews
```

### 3. Install required libraries:
```bash
pip install -r requirements.txt
```

###  4. Open the notebook in Jupyter Notebook:
```bash
jupyter notebook sentiment_analysis.ipynb
```

###  5. Run all cells step by step to see results.


Evaluation Metrics:-
Accuracy
Precision
Recall
F1-Score
Confusion Matrix (visualized using Seaborn)

Author
Priya Shrivastava