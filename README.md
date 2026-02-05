![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![AI](https://img.shields.io/badge/Domain-Multimodal%20AI-green.svg)
![Gradio](https://img.shields.io/badge/Framework-Gradio-orange.svg)
![BERT](https://img.shields.io/badge/Model-BERT-green.svg)
![FAISS](https://img.shields.io/badge/VectorDB-FAISS-orange.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/asif-khan-ak/resume_course_recommender/blob/main/resume_aware_course_recommendation_system.ipynb

# 🧠 Ultimate Resume-Aware Course Recommendation System

---

## 📌 Project Overview

This project demonstrates a **semantic, resume-aware recommendation system** that can **suggest online courses based on a user’s resume and skills** from the **Coursera** platform to develop an individual's personal growth and skills.  

The system leverages **BERT embeddings** for semantic similarity and **FAISS** for fast scalable search. It generates **personalized learning paths** and provides **explainable recommendations**. The interactive web app is built using **Gradio** and runs entirely in **Google Colab**.

This project is perfect for **personal portfolios, EdTech applications, or career guidance tools**.

---

## 🎯 Objectives

- Extract **skills automatically from resumes** (PDF or TXT)  
- Convert resume skills to **semantic embeddings** using **Sentence-BERT**  
- Search for top matching courses using **FAISS vector similarity**  
- Filter courses by **difficulty level** and generate a **learning path**  
- Provide **explainable recommendations** to users  
- Implement an **interactive Gradio web interface** for end-users  

---

## 📂 Dataset

The project uses a **custom dataset of Coursera courses (`Coursera.csv`)**, including:  
- Course Name
- University
- Difficulty Level  
- Course URL  
- Course Description  
- Skills  

> ⚠ Note: You can expand this dataset with more courses from other platforms like Udemy, edX, or LinkedIn Learning.

---

## 🔄 Project Pipeline

1. **Resume Upload & Skill Extraction**  
   - Parse PDF/TXT resumes and detect relevant skills  
2. **Semantic Embedding**  
   - Convert skills and course tags to embeddings using **Sentence-BERT**  
3. **Vector Similarity Search (FAISS)**  
   - Search for top matching courses based on cosine similarity  
4. **Filtering & Ranking**  
   - Rank courses by relevance and filter by difficulty level  
5. **Explainable Recommendations**  
   - Provide reasoning for each recommended course  
6. **Learning Path Generation**  
   - Suggest a structured roadmap: Beginner → Intermediate → Advanced  
7. **Interactive Web UI**  
   - Deployable with **Gradio** inside Google Colab  

---

## 🧠 Model & Tools

- **Sentence-BERT** for semantic embeddings  
- **FAISS** for scalable vector search  
- **Gradio** for interactive UI  
- **Python libraries**: Pandas, NumPy, Scikit-learn, NLTK, PyPDF  
- **Frameworks**: Google Colab, BERT embeddings, vector search  

> Semantic similarity allows **resume skills and course tags to be compared in the same feature space**, giving personalized and meaningful recommendations.

---

## 🖥️ Tech Stack

* Python | Pandas | NumPy  
* Scikit-learn | NLTK  
* Sentence-Transformers (BERT) | FAISS  
* Gradio | PyPDF | Google Colab  

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/asif-khan-ak/resume_course_recommender.git
cd resume_course_recommender
```

Open the notebook **resume_aware_course_recommendation_system.ipynb** in Google Colab, run all cells, and launch the Gradio app.

📌 Use Cases

- Personalized upskilling and course recommendations
- Resume-based career guidance
- Structured learning path for career transition
- EdTech & AI-powered learning assistants

🔮 Future Improvements

- Advanced resume parsing with NER models
- User feedback learning loop to improve recommendations
- Analytics dashboard for skills and popular courses
- Multi-language resume support
- Authentication & profile management

👤 Author

**Asif Khan** – Data Science & AI Enthusiast
⭐ If you like this project, star the repo!

⭐ Acknowledgments

* Inspired by NLP & Semantic Search research

* Hugging Face Transformers & PyTorch communities

* Gradio team for interactive ML apps
