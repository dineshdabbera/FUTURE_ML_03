# 📄 Resume Screening & Candidate Ranking System

## 🚀 Project Overview

Recruiters often receive hundreds of resumes for a single job opening. Manually reviewing every application is time-consuming and inefficient.

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to automatically screen resumes, rank candidates based on job relevance, and identify missing skills.

Developed as part of **Future Interns Machine Learning Task 3 (2026)**.

---

## 🎯 Objectives

* Analyze resume text data.
* Compare resumes with a given job description.
* Calculate similarity scores.
* Rank candidates according to role fit.
* Identify missing skills.

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib

### Machine Learning Techniques

* Natural Language Processing (NLP)
* TF-IDF Vectorization
* Cosine Similarity
* Skill Gap Analysis

---

## 📂 Dataset

Dataset Used:

**Resume Dataset**

### Features

| Column     | Description  |
| ---------- | ------------ |
| Resume_str | Resume text  |
| Category   | Job category |

---

## 🔄 Workflow

### 1. Data Loading

* Import resume dataset
* Select relevant columns

### 2. Text Preprocessing

* Convert text to lowercase
* Remove special characters
* Remove stopwords
* Remove extra spaces

### 3. Feature Extraction

* TF-IDF Vectorization

### 4. Similarity Calculation

* Compare resumes with job description using cosine similarity

### 5. Candidate Ranking

* Sort candidates according to similarity scores

### 6. Skill Gap Analysis

* Identify missing skills required for the job role

---

## 📊 Example Output

### Job Role

Data Scientist

### Required Skills

* Python
* Machine Learning
* SQL
* Pandas
* NumPy
* TensorFlow
* Deep Learning

### Top Ranked Candidate

Similarity Score: 92.3%

Missing Skills:

* TensorFlow

---

## 📁 Project Structure

```text
resume-screening-system/
│
├── Resume.csv
├── resume_screening_system.py
├── top_10_candidates.csv
├── README.md
├── requirements.txt
└── screenshots/
```

---

## 📋 Requirements

```text
pandas
numpy
nltk
scikit-learn
matplotlib
```

---

## 🎓 Learning Outcomes

Through this project, I gained experience in:

* Natural Language Processing
* Text preprocessing
* TF-IDF Vectorization
* Cosine Similarity
* Candidate Ranking Systems
* Skill Gap Analysis
* Real-world HR-Tech applications

---

## 👨‍💻 Author

**Dabbera Dinesh**

B.Tech CSE, VIT-AP University

📧 [dinesh07148@gmail.com](mailto:dinesh07148@gmail.com)

🔗 LinkedIn:
https://www.linkedin.com/in/dinesh-dabbera

---

## 📜 License

This project is created for educational and internship purposes.
