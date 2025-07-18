# 🧪 Toxic Comment Classification

This project focuses on building a machine learning model to detect and classify toxic comments from online text data. It is inspired by the growing need for automated moderation systems to identify harmful, offensive, or inappropriate content in social media, forums, and public discussion platforms.

---

## 📌 Project Overview

Toxic comments on the internet can harm communities and individuals. This project uses natural language processing (NLP) and machine learning techniques to classify comments into categories such as:

* **Toxic**
* **Severe Toxic**
* **Obscene**
* **Threat**
* **Insult**
* **Identity Hate**

The classification helps in filtering and flagging inappropriate content to maintain healthy online discussions.

---

## 📁 Dataset

The dataset used is the [Jigsaw Toxic Comment Classification Challenge dataset](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge).
It contains over **150,000** labeled comments from Wikipedia’s talk page edits, each annotated for different types of toxicity.

---

## 🔧 Technologies Used

* **Python**
* **Pandas / NumPy**
* **NLTK / re (Regular Expressions)**
* **Scikit-learn** – for vectorization and modeling
* **Matplotlib / Seaborn** – for data visualization
* **Jupyter Notebook**

---

## 🧹 Key Steps

1. **Data Cleaning**: Removal of stopwords, punctuation, and special characters.
2. **Text Preprocessing**: Lowercasing, tokenization, and basic stemming.
3. **Feature Extraction**: TF-IDF vectorization of comment texts.
4. **Model Building**: Logistic Regression and other baseline models.
5. **Evaluation**: Accuracy, Precision, Recall, F1-score on test data.
6. **Prediction**: Classifies new comments into one or more toxic categories.

---

## 📊 Results

The models were evaluated using multi-label metrics. The logistic regression model showed strong performance in classifying toxic comments with reasonable precision and recall.

---

## 🚀 Future Enhancements

* Integrate **BERT/RoBERTa** models using HuggingFace Transformers for better accuracy.
* Use **LIME/SHAP** for model explainability.
* Deploy using Flask/Streamlit for live toxic comment filtering.
* Add span-level toxic word detection (for tools like **ToxiCR**).

---

## 🤝 Contributing

Contributions are welcome! You can fork the repo and submit a pull request for:

* New models (BERT, LSTM, etc.)
* Data cleaning improvements
* UI for comment moderation
* Deployment integration

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for details.

---

## 🙋‍♂️ Author

**Kishan Vyas**
🔗 [LinkedIn](https://www.linkedin.com/in/kishanmvyas)
📬 Email: [kishanvyas.m@gmail.com](mailto:kishanvyas.m@gmail.com)

---

