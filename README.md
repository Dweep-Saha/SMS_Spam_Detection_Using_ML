# SMS Spam Detection Using Machine Learning

A machine learning project that classifies SMS messages as **Ham** (legitimate) or **Spam** using NLP techniques.

## Project Overview
This project builds an SMS spam detection system using machine learning and natural language processing techniques. The goal is to classify messages as either Ham or Spam using text vectorization and classification models.

## Features
- Text preprocessing and label encoding
- CountVectorizer and TF-IDF feature extraction
- Naive Bayes and Linear SVM model comparison
- Confusion matrix visualization
- Precision, recall, and F1-score evaluation
- Real-time custom message prediction

## Dataset
The dataset contains 5,572 SMS messages with two classes: Ham and Spam.

- Total Entries: 5,572
- Classes: Ham, Spam
- Class Distribution: Imbalanced, with more Ham messages than Spam messages

## Dataset Source
The dataset used in this project is the SMS Spam Collection dataset.

## Installation
Install the required dependencies using:

```bash
pip install -r requirements.txt
```

## How to Run
1. Clone this repository.
2. Open the notebook file in Jupyter Notebook or Google Colab.
3. Ensure `spam.csv` is in the same folder as the notebook.
4. Run all cells in order.

## Results
| Model Configuration | Accuracy |
|---|---:|
| CountVectorizer + Naive Bayes | 98.85% |
| TF-IDF + Naive Bayes | 96.27% |
| CountVectorizer + SVM | 98.64% |
| TF-IDF + SVM | 99.07% |

## Conclusion
TF-IDF + SVM performed best on the test set. This project shows that combining strong text features with a linear classifier works very well for spam detection.

## Notebook
- `SMS_Spam_Detection_Using_ML.ipynb`

## Dataset File
- `spam.csv`
