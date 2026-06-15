\# SMS Spam Detection Using Machine Learning



A comprehensive Machine Learning project to classify SMS messages into 'Ham' (legitimate) or 'Spam' using Natural Language Processing (NLP) techniques. 



\## 📊 Dataset Overview

\- \*\*Total Entries:\*\* 5,572 rows

\- \*\*Features:\*\* `Category`, `Message`, `spam`

\- \*\*Class Distribution:\*\* Heavily imbalanced (\~87% Ham, \~13% Spam).



\## ⚙️ Methodology \& Architecture

The project evaluates text vectorization through CountVectorizer and TF-IDF, tested across Naive Bayes and Support Vector Machine (SVM) models.



\## 📈 Model Performance Summary

Evaluated on a test set of 1,393 messages (1,207 Ham, 186 Spam):



| Model Configuration | Precision | Recall | F1-Score | Accuracy |

| :--- | :---: | :---: | :---: | :---: |

| CountVectorizer + Naive Bayes | 0.98 | 0.94 | 0.96 | 99.00% |

| TF-IDF + Naive Bayes | 1.00 | 0.72 | 0.84 | 96.00% |

| CountVectorizer + SVM | 0.99 | 0.90 | 0.95 | 98.64% |

| \*\*TF-IDF + SVM (Champion Model)\*\* | \*\*0.99\*\* | \*\*0.94\*\* | \*\*0.96\*\* | \*\*99.07%\*\* |



\### 🏆 The Champion Model: TF-IDF + SVM

The \*\*TF-IDF + SVM\*\* configuration was selected due to its superior performance:

\- \*\*Accuracy:\*\* 99.07%

\- \*\*False Positives:\*\* Only 2 legitimate messages were misclassified (High Precision).

