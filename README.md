# 🚀 AI Resume Analyzer

## 👨‍💻 Developed By
**Lalit Mittal**

---

## 📌 Project Description
AI Resume Analyzer is a web-based application that analyzes resumes using Natural Language Processing (NLP).  

It extracts important information like:
- Name
- Skills
- Email
- Experience

and provides:
- Resume score
- Skill recommendations
- Job role prediction
- Improvement suggestions

---

## 🛠️ Technologies Used
- Python
- Streamlit
- NLP (spaCy, NLTK)
- MySQL
- Pandas

---

## ✨ Features

### 👤 User
- Upload resume (PDF)
- Get extracted details
- Resume score
- Skill recommendations
- Job prediction

### 🔐 Admin
- Login system
- View user data
- Download data as CSV
- View analytics (charts)

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/your-username/ai-resume-analyzer.git

cd AI-Resume-Analyzer/App

python -m venv venv
venv\Scripts\activate

pip install -r requirements.txt
python -m spacy download en_core_web_sm