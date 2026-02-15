# 🤖 BERT Semantic Chatbot

### Context-Aware AI Chat Interface with Streamlit

> A lightweight, semantic-search powered chatbot built using BERT embeddings and cosine similarity — designed for intelligent Q&A systems without relying on heavy LLM APIs.

---

## 📌 Project Overview

This project implements a **context-aware chatbot** using:

* 🧠 **BERT (Bidirectional Encoder Representations from Transformers)**
* ⚡ **PyTorch for inference**
* 📊 **Cosine similarity for semantic matching**
* 🌐 **Streamlit for interactive UI**

Instead of rule-based keyword matching, the chatbot understands *semantic meaning* by comparing contextual embeddings.

This demonstrates practical NLP system design using transformer-based models.

---

## 🖼️ Application Preview

### 💬 WhatsApp-Style Chat Interface

![Image](https://global.discourse-cdn.com/streamlit/optimized/2X/1/1c3534b3700888360426b38076a3d2e639c90c64_2_690x388.png)

![Image](https://cdn.shopify.com/app-store/listing_images/7c6bb53389031b6758686d279ceea646/desktop_screenshot/CO3Tnb6vhpEDEAE%3D.png?height=720\&width=1280)

![Image](https://global.discourse-cdn.com/streamlit/optimized/3X/5/3/53d052dd9cb413893695f81eb3e524a955a96970_2_467x499.jpeg)

![Image](https://global.discourse-cdn.com/streamlit/original/2X/9/9d57e2c8dfd595a30a2f5ce8a1db93519ba34d02.png)

---

## 🚀 Core Features

### 🧠 Semantic Understanding with BERT

* Converts user queries into contextual embeddings
* Captures meaning beyond keywords
* Handles phrasing variations effectively

### 📊 Cosine Similarity Matching

* Embedding comparison using `scikit-learn`
* Returns the most relevant response
* Confidence threshold control (default: `0.5`)

### 🎨 Premium UI Design

* WhatsApp-style chat bubbles
* Gradient background customization
* Clean, responsive layout

### ⚡ Lightweight & Fast

* No external LLM API dependency
* Runs locally
* Efficient inference pipeline

---

## 🧠 How It Works

```
User Query
     ↓
BERT Tokenization
     ↓
BERT Embedding Generation
     ↓
Cosine Similarity with QA Embeddings
     ↓
Best Match Selection
     ↓
Response Display
```

If similarity score > threshold → return matched answer
Else → fallback response

---

## 🛠️ Tech Stack

| Layer             | Technology                      |
| ----------------- | ------------------------------- |
| NLP Model         | BERT (HuggingFace Transformers) |
| Deep Learning     | PyTorch                         |
| Similarity Engine | scikit-learn                    |
| UI Framework      | Streamlit                       |
| Language          | Python 3.10+                    |

---

## 🚀 Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Tanmay1112004/bert-chatbot.git
cd bert-chatbot
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Application

```bash
streamlit run app.py
```

App launches automatically in your browser.

---

## 📚 Supported Knowledge Base

Example queries:

* 🤖 What is AI?
* 📊 What is Data Science?
* ☁️ What is Microsoft Azure?
* 🧠 What is BERT?
* 😂 Tell me a joke
* 🙋 How are you?

Easily extendable via:

```python
qa_pairs = {
    "Question": "Answer"
}
```

---

## 🎨 Customization Options

| Feature              | Where to Modify                     |
| -------------------- | ----------------------------------- |
| Add new Q&A          | `qa_pairs` dictionary               |
| Similarity threshold | `if similarities[best_match] > 0.5` |
| Background styling   | `set_background()`                  |
| UI CSS               | Streamlit style blocks              |

---

## 🏗️ Project Structure

```
bert-chatbot/
│
├── app.py
├── requirements.txt
├── screenshots/
└── README.md
```

---

## 📈 Why This Project Matters

This project demonstrates:

✔ Transformer-based NLP understanding
✔ Embedding-driven semantic search
✔ Lightweight AI deployment
✔ Clean UI integration
✔ Practical AI system design

It shows understanding of **how contextual embeddings work in real applications**, not just how to call an API.

---

## 🔮 Future Enhancements

* 🔄 Hybrid LLM + BERT fallback system
* 🌍 Multi-language support
* 💾 Database-backed knowledge storage
* 📊 Similarity score visualization
* 🧠 Fine-tuned domain-specific BERT
* 🚀 FastAPI backend deployment

---

## 👨‍💻 Author

Built by **Tanmay**

* 🔗 LinkedIn: [https://linkedin.com/in/tanmay-kshirsagar](https://linkedin.com/in/tanmay-kshirsagar)
* 💻 GitHub: [https://github.com/Tanmay1112004](https://github.com/Tanmay1112004)

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It genuinely helps.

---
