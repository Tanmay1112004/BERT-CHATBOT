# 🤖 BERT Chatbot with Streamlit

A sleek, AI-powered chatbot built using **BERT (Bidirectional Encoder Representations from Transformers)** and **Streamlit**.
This project delivers an interactive web interface where users can ask questions and receive intelligent responses powered by semantic similarity using pre-trained BERT embeddings.

---

## 🌟 Overview

This chatbot leverages **contextual embeddings** from BERT to understand user queries beyond simple keyword matching. Instead of rule-based responses, it computes cosine similarity between user input and a predefined knowledge base to deliver the most relevant answer.

The result?
⚡ Fast
🧠 Context-aware
🎨 Clean & modern UI

---

## ✨ Key Features

* 🔥 **BERT-powered NLP engine** for semantic understanding
* 💬 **WhatsApp-style chat bubbles** for a modern UX
* 🎨 **Gradient & customizable backgrounds** for premium UI feel
* ⚡ **Efficient inference with PyTorch**
* 📊 **Cosine similarity matching** using scikit-learn
* 🧩 Easily extendable Q&A knowledge base
* 🏷️ Developed by **Tanmay**

---

## 🖼️ Screenshots

### 💬 Chat Interface

*(Modern WhatsApp-style conversation layout)*

![Chat Screenshot](screenshots/chat_ui.png)

---

### 🎨 Gradient Background UI

*(Clean gradient background for enhanced aesthetics)*

![Gradient Background](screenshots/gradient_bg.png)

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Tanmay1112004/bert-chatbot.git
cd bert-chatbot
```

### 2️⃣ Install Dependencies

Make sure you are using **Python 3.10+**

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application

```bash
streamlit run app.py
```

The app will launch in your browser automatically.

---

## 🛠️ Tech Stack

* **Python 3.10+**
* **Streamlit** – Interactive web UI
* **HuggingFace Transformers** – BERT model
* **PyTorch** – Model inference & embeddings
* **scikit-learn** – Cosine similarity computation

---

## 🧠 How It Works

1. User enters a query
2. BERT generates embeddings for the query
3. Cosine similarity compares it with predefined Q&A embeddings
4. The most similar response is returned

If similarity score exceeds a defined threshold (default: `0.5`), the chatbot responds confidently. Otherwise, it returns a fallback response.

---

## 📚 Predefined Knowledge Base

Sample supported queries include:

* 🤖 *What is AI?*
* 📊 *What is Data Science?*
* ☁️ *What is Microsoft Azure?*
* 🧠 *What is BERT?*
* 😂 *Tell me a joke*
* 🙋 *How are you?*

You can expand the chatbot by simply updating the `qa_pairs` dictionary in `app.py`.

---

## 🎨 Customization Guide

| Feature              | How to Modify                              |
| -------------------- | ------------------------------------------ |
| Background Style     | Update `set_background()` in `app.py`      |
| Add New Q&A          | Modify `qa_pairs` dictionary               |
| Similarity Threshold | Adjust `if similarities[best_match] > 0.5` |
| UI Styling           | Modify Streamlit CSS blocks                |

---

## 📂 Project Structure

```
bert-chatbot/
│
├── app.py
├── requirements.txt
├── screenshots/
│   ├── chat_ui.png
│   └── gradient_bg.png
└── README.md
```

---

## 📈 Future Improvements

* 🔄 Integration with real-time LLM APIs
* 🌍 Multi-language support
* 💾 Database-backed knowledge base
* 📊 Logging & analytics dashboard
* 🧩 Fine-tuned domain-specific BERT

---

## 👨‍💻 Author

Built with passion by **Tanmay**

* 🔗 LinkedIn: [https://linkedin.com/in/tanmay-kshirsagar](https://linkedin.com/in/tanmay-kshirsagar)
* 💻 GitHub: [https://github.com/Tanmay1112004](https://github.com/Tanmay1112004)

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.
It helps more than you think.

---
