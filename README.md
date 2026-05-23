# AI Resume Screener

An AI-based Resume Screening System built using Machine Learning and NLP techniques.

## Project Overview

This project automatically screens resumes and matches them with a job description using Natural Language Processing (NLP) and Machine Learning.

The system:
- Extracts text from resumes
- Cleans and processes resume data
- Converts text into vectors using TF-IDF
- Calculates similarity scores
- Ranks resumes based on job relevance

---

# Features

- PDF Resume Reading
- DOCX Resume Reading
- TXT Resume Reading
- NLP Text Cleaning
- TF-IDF Vectorization
- Cosine Similarity Matching
- Resume Ranking System
- CSV Result Export

---

# Technologies Used

- Python
- Google Colab
- Scikit-learn
- Pandas
- NLTK
- PyPDF2
- pdfplumber

---

# Machine Learning Concepts Used

- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Cosine Similarity
- Text Classification

---

# Project Structure

```bash
AI-RESUME-SCREENER1/
│
├── AI_Resume_Screener.ipynb
├── requirements.txt
├── README.md
│
├── sample_resumes/
│   ├── resume1_data_science.pdf
│   ├── resume2_web_developer.pdf
│   ├── resume3_java_developer.pdf
│   └── resume4_android_developer.pdf
│
└── results/
    └── resume_screening_results.csv
```

---

# How to Run the Project

## Step 1
Open the notebook in Google Colab.

## Step 2
Install required libraries.

```python
!pip install PyPDF2 python-docx nltk scikit-learn pandas pdfplumber
```

## Step 3
Upload resumes.

## Step 4
Add job description.

## Step 5
Run all cells.

## Step 6
View ranked resumes and output CSV file.

---

# Sample Job Description

```python
job_description = """
Looking for a Data Scientist with skills in:
Python,
Machine Learning,
Deep Learning,
SQL,
NLP,
Flask,
Data Analysis
"""
```

---

# Example Output

| Resume Name | Match Score |
|-------------|-------------|
| resume1.pdf | 92.45% |
| resume2.pdf | 71.20% |
| resume3.pdf | 54.11% |

---

# Future Improvements

- Deep Learning Resume Screening
- BERT NLP Model
- Streamlit Web Application
- Resume Skill Extraction
- ATS Score Prediction
- Interview Recommendation System

---

# Author

Abdul Hafiz

---

# GitHub Repository

Upload this project to GitHub and use it for:
- Resume
- Portfolio
- Internship Applications
- Final Year Projects
- LinkedIn Showcase
