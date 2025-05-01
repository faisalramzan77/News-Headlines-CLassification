
# 📰 News Category Classification using CNN
A machine learning project that leverages deep learning (CNN) to classify news headlines into their respective categories based on textual data. This end-to-end pipeline includes preprocessing, tokenization, model training, and evaluation.

## 🎯 Objective
The goal of this project is to build a text classification model that accurately categorizes news headlines into their respective categories using a Convolutional Neural Network (CNN).

## 📊 Dataset
* **Name**: News_Category_Dataset_v3

* **Source**: Kaggle

* **Format**: JSON lines (.json)

* **Size**: ~200K headlines across 41 categories

* **Fields Used**:

* `headline`: News headline text

* `category`: Target label

## ⚙️ Preprocessing & Feature Engineering
* Cleaned text:

Lowercased

Removed numbers, punctuation, and extra whitespace

* Encoded labels using `LabelEncoder`

* Tokenized and padded text sequences using Keras `Tokenizer`

* Saved preprocessing artifacts:

* `label_encoder.pkl`

* `tokenizer.pkl`

## 📉 Visualizations
- ✅ Accuracy & Loss Plot (Training vs Validation)

## Evaluation Metrics

In this project, we evaluated the model's performance using the **Classification Report** from Scikit-learn. Below are the metrics for each class:

### Classification Report

```plaintext
              precision    recall  f1-score   support

     POLITICS       0.91      0.89      0.90       500
ENTERTAINMENT       0.87      0.86      0.86       480
         TECH       0.88      0.84      0.86       460
     BUSINESS       0.89      0.87      0.88       470
       TRAVEL       0.85      0.88      0.86       490

    accuracy                           0.87      2400
   macro avg       0.88      0.87      0.87      2400
weighted avg       0.88      0.87      0.87      2400

```


## 👨‍💻 Author

**Faisal Ramzan**  
📧 Email: [faisalramzanch77@gmail.com](mailto:faisalramzanch77@gmail.com)  
🔗 GitHub: [Faisal Ramzan](https://github.com/faisalramzan77)  
🔗 LinkedIn: [Faisal Ramzan](https://www.linkedin.com/in/faisalramzan77/)
