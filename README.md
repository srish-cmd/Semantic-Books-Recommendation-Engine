# 📚 Semantic Book Recommender with LLMs 

🚀 This repository contains all the codes of the project, **"Semantic Book Recommender with LLMs"**

## 📌 Overview
This project uses **Large Language Models (LLMs)** and **vector databases** to build an advanced **book recommendation system**. Users can discover books based on **semantic search, sentiment analysis, and zero-shot classification.**

## 🛠️ Components of Project
The project is structured into five key parts:

1️⃣ **Text Data Cleaning** 🧹
   - Preprocessing and cleaning the book data.
   - Code in: `data-exploration.ipynb`

2️⃣ **Semantic Search & Vector Database** 🔍📖
   - Implementing **vector-based search** to find books matching a natural language query (e.g., "a book about a person seeking revenge").
   - Code in: `vector-search.ipynb`

3️⃣ **Zero-shot Text Classification** 🏷️
   - Classifying books as **"fiction"** or **"non-fiction"** to enable filtering.
   - Code in: `text-classification.ipynb`

4️⃣ **Sentiment Analysis & Emotion Extraction** 😃😢😱
   - Sorting books based on their emotional tone (e.g., suspenseful, joyful, sad).
   - Code in: `sentiment-analysis.ipynb`

5️⃣ **Interactive Web App with Gradio** 🎨
   - Deploying a simple **Gradio-based UI** for users to get book recommendations.
   - Code in: `gradio-dashboard.py`

---

## 💾 Installation & Dependencies
This project was developed using **Python 3.11**.

### 📦 Required Libraries
Make sure you have the following dependencies installed:

```bash
pip install -r requirements.txt
```

### 📜 Key Packages Used
✅ [kagglehub](https://pypi.org/project/kagglehub/)  
✅ [pandas](https://pypi.org/project/pandas/)  
✅ [matplotlib](https://pypi.org/project/matplotlib/)  
✅ [seaborn](https://pypi.org/project/seaborn/)  
✅ [python-dotenv](https://pypi.org/project/python-dotenv/)  
✅ [langchain-community](https://pypi.org/project/langchain-community/)  
✅ [langchain-opencv](https://pypi.org/project/langchain-opencv/)  
✅ [langchain-chroma](https://pypi.org/project/langchain-chroma/)  
✅ [transformers](https://pypi.org/project/transformers/)  
✅ [gradio](https://pypi.org/project/gradio/)  
✅ [notebook](https://pypi.org/project/notebook/)  
✅ [ipywidgets](https://pypi.org/project/ipywidgets/)

---

## 🔑 Setting Up Your Environment
To create your **vector database**, you'll need an **OpenAI API key**. 

1. **Create a `.env` file** in your root directory.
2. Add your OpenAI API key like this:
   ```env
   OPENAI_API_KEY=your_api_key_here
   ```

More detailed instructions are available in the tutorial.

---

## 📥 Downloading Data
The dataset for this project is available on **Kaggle**. 

Follow the instructions in the repo to **download and set up the dataset**.

---

## 🚀 Running the Project
Once everything is set up, you can run the project components step by step using the provided **Jupyter notebooks** or launch the **Gradio app**:

```bash
python gradio-dashboard.py
```

---


📌 Repo Link: [Book Recommendation System](https://github.com/poisonkissedsk/Book-Recommendation-System)
