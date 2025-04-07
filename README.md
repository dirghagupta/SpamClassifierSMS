# 📩 Spam SMS Classifier using NLP and Machine Learning

This is a simple machine learning project that classifies SMS messages as **Spam** or **Not Spam (Ham)** using Natural Language Processing (NLP).

---

## 🚀 Features

- Text preprocessing using **TF-IDF Vectorization**
- Classification using **Naive Bayes**
- Model evaluation with **accuracy, confusion matrix, and classification report**
- Test predictions with custom input
- Spam vs Ham visualization using **matplotlib**

---

## 📁 Dataset

- **Source**: [Kaggle - SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- File used: `spam.csv`
- Format: Two columns: `label` (spam/ham) and `text` (message content)

---

## ⚙️ How to Run

1. Clone the repository or download the files.
2. Make sure you have Python 3 installed.
3. Install required libraries:
   ```bash
   pip install pandas scikit-learn matplotlib
Run the Python script:

bash
Copy
Edit
python your_script_name.py
📊 Output Sample
bash
Copy
Edit
Accuracy: 0.96
Confusion Matrix:
[[965   0]
 [ 37 113]]
🔍 Test with Custom Input
You can test your own message like:

python
Copy
Edit
custom_msg = ["Congratulations! You've won a $1000 Walmart gift card. Call now!"]
prediction = model.predict(vectorizer.transform(custom_msg))
📊 Spam vs Ham Visualization
A pie chart is displayed showing the ratio of Spam vs Not Spam messages in the dataset.

🛠️ Tech Stack
Python 🐍

scikit-learn

pandas

matplotlib

TF-IDF Vectorizer

Naive Bayes

🙋‍♂️ Author
Dirgha Gupta

📄 License
This project is open-source and free to use.
