Research 

# 🛡️ Combating Spam with NLP and Machine Learning  
## A Step Towards Safer Digital Communication

---

## 🚀 Introduction

We’ve all been there—our phones buzz or our email pings, and it’s yet another message trying to sell us something sketchy, trick us into clicking a shady link, or just waste our time. That’s **spam**—and while it may seem like just an annoyance, it’s actually a serious and growing issue in today’s digital world.

From **phishing scams** to **malware links**, spam can lead to **data theft, financial losses**, and even impact our **mental well-being**. This project is my attempt to explore how we can use **Natural Language Processing (NLP)** and **Machine Learning (ML)** to fight back.

---

## 📈 How Big Is the Spam Problem?

Let’s break it down with some real numbers:

- **Email Spam**: In 2023, about **45.6% of all emails** sent around the world were spam. That’s nearly **1 out of every 2** emails.
- **SMS Spam**: In the U.S. alone, people received a jaw-dropping **225 billion spam texts** in 2022 — a **157% increase** from the previous year.
- **Phishing Attempts**: Around **3.4 billion phishing emails** are sent **every single day**, trying to trick people into sharing sensitive information.

📊 These numbers show that spam isn’t just annoying—it’s dangerous.

---

## 💥 Why Should We Care?

Spam has real-world consequences:

- 💸 **Financial Loss**: Businesses lose **~$1,934 per employee per year** due to spam-related disruptions.  
- 😩 **Mental Health Impact**: Over **68% of users** report feeling stressed, anxious, or annoyed due to spam or phishing attempts.  
- 🔐 **Security Breaches**: The average


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

